# Grammarly Sync

Chrome extension that allows you to **Sync your local text file with Grammarly Website Editor!**

## Usage

1. Open any document in Grammarly -- URL might be `https://app.grammarly.com/ddocs/*`
1. Click on the extension button on the toolbar
1. It will be copied to your clipboard
1. Profit 🚀

## Development

1. Check if your Node.js version is >= 6.
1. Clone the repository.
1. Run `make build`
1. Load your extension on Chrome following:
    1. Access `chrome://extensions/`
    2. Check `Developer mode`
    3. Click on `Load unpacked extension`
    4. Select the `build` folder.

## Credits 

* Chrome plugin based on awesome https://github.com/brunoluiz/grammarly-markdown-extension project!
* It uses the [chrome-extension-webpack-boilerplate](https://github.com/samuelsimoes/chrome-extension-webpack-boilerplate). It will run a webpack server, with hotreload, for your JS (whatever that means...)


