# Collection

A collection is a representation of a `ERC 721` contract. For every `ERC 721` contract that is verified on BumbleBuzz, a collection is associated with it.

Every varified `ERC 721` contract on BumbleBuzz has a collection assosiated with it.

There are 3 types of collections. Each type of collection can be consodered as a bucket, and each bucket contains one or more collections.

{% tabs %}
{% tab title="Verified" %}
This bucket consists of verified collections only.

Creator seeking verification for their `ERC 721` contract on BumbleBuzz must submit their creation for verification.

Once the collection is verified, the collection is marked as `verified`. This means the NFTs belonging to the verified collection has been reviewd and approved as authentic by Bumblebuzz. All verified NFTs present with a verified mark on them for users interested in varified NFTs.&#x20;
{% endtab %}

{% tab title="Unverified" %}
This bucket consists of only collections that have not been verified. There is only 1 unverified collection in this bucket (of type `unverified`).&#x20;

Any NFT belonging to a `ERC 721` contract that has not been verified on BumbleBuzz is associated with this collection. This means that all NFTs start off as unverified, until their `ERC 721` contracts go through a successful verification process.

There is a visual representation of this on the NFT itself to warn users that this NFT has not been vetted.
{% endtab %}

{% tab title="Local" %}
This bucket consists of only collections that have been marked as `local`. This is a special `verified` bucket. This `local` collection is associated with the `ERC 721` contract for minting NFTs on the BumbleBuzz website. There is only 1 local collection in this bucket (of type `local`).&#x20;

This collection has special rules in place to give out artist commissions. All NFTs minted on the website and automatically marked as verified.
{% endtab %}
{% endtabs %}

Representation of a collection page.

![](../.gitbook/assets/collection\_page.png)
