# Chrome Web Bookmark Extension

> Turn a link as a visual bookmark, just like `Twitter` cards or `Notion` web bookmark.

## Preview

| Bookmark Layout | Light Mode | Dark Mode |
| :---: | :---: | :---: |
| horizontal | ![](./assets/chrome-web-bookmark_03.png) | ![](./assets/chrome-web-bookmark_04.png) |
| vertical | ![](./assets/chrome-web-bookmark_02.png) | ![](./assets/chrome-web-bookmark_01.png) |

## Concepts

This extension is built on top of [metafy](https://github.com/xiaoluoboding/metafy), which provides serverless api to fetch websites metadata easily and turn the metadata into the visual bookmark. like Twitter does.

## Features

* 🔮 Turn any tabs as a visual web bookmark
* 🐦 Twitter card like
* 🔖 Notion web-bookmark like
* 🖼️ Copy image to your clipboard
* 📷 Toggle the QRCode on the bookmark
* 🌛 Dark mode support

## Usage

### Install

Install the dependencies

```bash
yarn
# or
pnpm install
```

### Development

Run the development server

```bash
yarn dev
# or
pnpm dev
```

Then load uppacked extension in browser with the `extension/` folder.

### Production

Build the extension

```bash
yarn build
# or
pnpm build
```

Then load uppacked extension in browser with the `extension/` folder.

## Template

[This repo is created from this template on GitHub](https://github.com/xiaoluoboding/vitesse-modernized-chrome-ext/generate).

## License

[MIT](./LICENSE) - [@xiaoluoboding](https://github.com/xiaoluoboding)
