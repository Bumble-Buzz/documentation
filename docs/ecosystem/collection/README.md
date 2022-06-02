# Collection

A collection is a representation of a `ERC 721` contract. For every `ERC 721` contract that is verified on BumbleBuzz, there is an associated collection to it.

There are 3 types of collections. You can consider each collection type as a bucket, and in each bucket there are one or more collections.

{% tabs %}
{% tab title="Verified" %}
This bucket consists of only collections that have been verified.

When a creator wants to verify their `ERC 721` contract on BumbleBuzz, they must create a collection and wait for it to be verified.

Once the collection is verified, the collection is marked as `verified`. What this means is that all the NFTs belonging to this collection is given a blessing from BumbleBuzz that it's authentic. There is a visual representation of this on the NFT itself to give users confidence that this NFT has been vetted.
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
