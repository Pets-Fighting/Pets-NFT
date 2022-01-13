# Pets NFT Distribution Contract

** This series of NFTs consist of 8888 collections with different properties.**

Discord:

Twitter:

Website:

## Whitelist

## Shuffle

Choose a seed and shuffle the images with the seed. The seed will be public.

## Provenance

image_hash = sha256(image metadata)

PROVENANCE = sha256(abi.encodePacked(image1_hash, image2_hash, ... image8888_hash));

We will set the provennace before mint.

## Mint Process

Whitelist 4000 + Reserve 100 + Public Sale 4788

- Community choose a start index. Change the image uri to be correct.

- Set the whitelist to the contract.

- Start the whitelist mint(4000).

- Reserve mint(100).

- Public sale(4788).

## IPFS Storage

tokenURI: ipfs://{file_hash}//{tokenId}

```
{
    "image":"ipfs:\/\/{hash}",
    "name":"Pets #333",
    "description":"A community-driven collectibles project.",
    "attributes":[
        {"trait_type":"face","value":"grumpy"},
        {"trait_type":"hair","value":"blue messy"},
        {"trait_type":"body","value":"spotted hoodie"},
        {"trait_type":"background","value":"grey"},
        {"trait_type":"head","value":"orange"}
    ]
}
```

## Shuffle Example

Initial order:

image1, image2, image3, ..., image8888

Shuffle:

image8, image576, image 1234, ..., image600

Start Index(2):

image576(tokenId = 0), image1234, ..., image600, image8(tokenId = 8887)
