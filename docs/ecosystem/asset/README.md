# Asset

An asset is a Non-Fungible Token (NFT). Either this NFT is minted on BumbleBuzz or belongs to a `ERC 721` contract created anywhere on chain. Any given NFT is considered as an asset.

A given asset, depending on which collection it belongs to can be considered `verified` or `unverified`.&#x20;

{% tabs %}
{% tab title="Verified" %}
If the asset belongs to a collection that is `verified`, then this asset will also be considered as `verified`.&#x20;

There is a visual representation of this on the NFT itself to give users confidence that this NFT has been vetted.
{% endtab %}

{% tab title="Unverified" %}
If this asset does not belong to any verified collection, then this asset will be considered as `unverified`.

There is a visual representation of this on the NFT itself to warn users that this NFT has not been vetted.
{% endtab %}
{% endtabs %}

This is how a typical asset page looks like.

![](../../.gitbook/assets/asset\_page.png)
