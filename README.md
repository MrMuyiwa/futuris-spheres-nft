# Futuris Spheres NFT Drop

This repository contains the metadata CSV, images, and GitHub Actions workflow to automate the lazy minting of the **Futuris Spheres** NFT collection on the Base blockchain using the thirdweb CLI.

## What’s inside?

- `futuris_spheres_metadata.csv` — Metadata for 111 NFTs, including rarity and attributes.
- `futuris_images/` — Folder with all 111 PNG sphere images.
- `.github/workflows/lazy-mint.yml` — GitHub Actions workflow to lazy mint NFTs using thirdweb.

## How to use

1. Add your thirdweb secret API key as a GitHub secret named `THIRDWEB_API_KEY`.
2. Update the contract address in the workflow file.
3. Run the GitHub Action to start the lazy mint.

---

### Important:

- The `THIRDWEB_API_KEY` secret must be kept private.
- This repo can be public since it contains only images and metadata, **not your private keys or sensitive info**.

---

## Contact

If you need help, reach out to Muyiwa Arowolo.
