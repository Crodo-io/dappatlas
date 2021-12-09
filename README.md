# dApp Atlas

Open source registry of dApps.

## List Your dApp

### 1. Fork this project

### 2. Add your dApp 

* Add your logo to the `logos` folder (`.png` or `.jpg` are supported)
* Add your dApp details in the `dapps.json` file, with the following format:

```json
{
    "name": "OlympusDAO",
    "description": "Olympus is a decentralized reserve currency protocol based on the OHM token. Each OHM token is backed by a basket of assets (e.g. DAI, FRAX) in the Olympus treasury, giving it an intrinsic value that it cannot fall below.",
    "logo": "olympusdao.png",
    "categories": ["defi"],
    "ecosystem": ["ethereum", "avalanche", "arbitrum"],
    "website": "https://olympusdao.finance",
    "external": {
        "twitter": "https://twitter.com/OlympusDAO",
        "discord": "https://discord.com/invite/olympusdao",
        "medium": "https://olympusdao.medium.com",
        "telegram": "https://t.me/OlympusTG",
        "youtube": "https://www.youtube.com/c/olympusdao",
        "reddit": "https://www.reddit.com/r/olympusdao",
        "github": "https://github.com/OlympusDAO",
    }
}
```

### 3. Open a pull request

Open a pull request to merge your contribution into the `main` branch.
