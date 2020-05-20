# Dark WhatsApp Web

Incredibly simple Chrome extension that enables WhatsApp Web's secret Dark Mode.

## Installation

Clone this repository and then add the `src` folder as an unpacked extension to Chrome.
See [this StackOverflow answer](https://stackoverflow.com/a/24577660) for more details.

## How it works

The extension registers a one-liner content script for [web.whatsapp.com](https://web.whatsapp.com)
which adds the `.dark` class to `body`.
