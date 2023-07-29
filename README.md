# nft.storage_upload

---

## Introduction

This is a simple script to upload images and metadata to nft.storage. It will upload all images and metadata in the specified folders.

## Installation

```bash
git clone https://github.com/truethari/nft.storage_upload.git

cd nft.storage_upload
npm install
```

## Configuration

- Open the `config.json` file 
- Add your nft.storage API key.
- Add image folder and metadata folder paths.

```json
{
  "imagesDirectory" : "./images",
  "metadataDirectory" : "./metadata",
  "nftStorageKey" : ""
}

```

## Usage

```bash
node index.js
```
