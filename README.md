# Chrome Extension - Web Visual Bookmark

> One-click turn any link into a visual bookmark, and it looks like `Twitter` cards or `Notion` web bookmark.

## Preview

| Bookmark Layout | Light Mode | Dark Mode |
| :---: | :---: | :---: |
| Twitter card like | ![](./assets/chrome-web-bookmark_03.png) | ![](./assets/chrome-web-bookmark_04.png) |
| Notion web bookmark like | ![](./assets/chrome-web-bookmark_02.png) | ![](./assets/chrome-web-bookmark_01.png) |

## Concepts

This extension is built on top of [metafy](https://github.com/xiaoluoboding/metafy), which provides serverless api to fetch websites metadata easily and turn the metadata into the visual bookmark. like Twitter does.

## Articles

* [ãHow to create a visual web bookmark?ã](https://www.xlbd.me/posts/2021-08-16-how-to-create-a-visual-web-bookmark.html)

## Features

* ð® Turn any tabs into a visual web bookmark
* ð¦ Twitter card like
* ð Notion web-bookmark like
* ð¼ï¸ Copy image to your clipboard
* ð· Toggle the QRCode on the bookmark
* ð Dark mode support

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
