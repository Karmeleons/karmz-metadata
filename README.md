# karmz-metadata

## Official Metadata of the Karmz NFT collection on Ethereum

Help us keep track of the 2,000 Karmz NFTs being burned by updating metadata of burnt assets. Burned Karmz belong to a `BurnAddress` wallet and are no longer purchasable/tradable on the secondary market.

The contract this collection minted from does not have a public burn method, so although the NFTs get transferred to the burn wallet, they are not physically removed from the total supply.

The goal of this repo is to crowdsource updates and curate the collection's metadata so it is easy to see which Karmz were burned when browsing marketplaces.

To make updates, pull down this repo and update the `.json` files belonging to the burned assets. Here's an example of a burned asset, and the changes that need to be made to its metadata:


### Example of current metadata of Karmz #1:

```
{
  "name": "Karmz #1",
  "description": "The Karmeleons thought they were the only lifeforms left on Earth, until one day they sensed the same Karmic energy that allowed them to thrive come from an island off the coast of Karma City. There they discovered the Karmz! A similar but less refined species than themselves, they decided to begin mentoring the Karmz and working together to restore the planet.",
  "image": "ipfs://QmTUgC516tKkD6VSFfX35WK7iLK5GxPBBhHpCgr2icmikH/1.png",
  "animation_url": "ipfs://QmTUgC516tKkD6VSFfX35WK7iLK5GxPBBhHpCgr2icmikH/1.mp4",
  "dna": "e9a64d84260d79ce12467b1d5823ff28c2d6daf7",
  "edition": 1,
  "date": 1652737540853,
  "attributes": [
    {
      "trait_type": "Background",
      "value": "Karmic Woods"
    },
    {
      "trait_type": "Metaholo",
      "value": "True"
    },
    {
      "trait_type": "Skin",
      "value": "Chango"
    },
    {
      "trait_type": "Headwear",
      "value": "Yellow Krew Cap"
    },
    {
      "trait_type": "Clothing",
      "value": "Stealth LFG Hoodie"
    },
    {
      "trait_type": "Type",
      "value": "Chill"
    }
  ],
  "compiler": "Karmeleons Art Engine"
}
```

### Example of updating the metadata of Karmz #1 if the asset was burned:

```
{
    "name": "Karmz #1",
    "description": "This Karmz has transcended. To gain access to The KREW community, visit https://thekrew.xyz for more info.",
    "image": "ipfs://__CID__/1.png",
    "edition": 1,
    "attributes": [
        {
            "trait_type": "Transcended",
            "value": "Yes"
        }
    ]
}
```

Make sure the updated metadata has the same number in the `"name"` field as the one you're updating. I will update the `__CID__` values shortly. Thanks fam!