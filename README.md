# Prism.js extension for PTCGO Deck Lists

[Prism.js](https://prismjs.com/) is a wonderful syntax highlighting library.

This repository is an extension to Prism.js to allow syntax highlighting for Pokemon TCG Online decklists.

## Usage

First, follow instructions on [Prism.js website](https://prismjs.com/) to install Prism library.

Then, to add this to your website or blog, download the `prism-ext-ptcgo.js` file and store it in your project. Then, after the line where you import Prism.js, add this to your HTML:

```html
<script src="prism-ext-ptcgo.js"></script>
```

You'll then need to add the CSS definitions to your CSS file.

| CSS class         | Description                                                       |
| ----------------- | ----------------------------------------------------------------- |
| `ptcgo_title`     | Used for the header and footer                                    |
| `ptcgo_subheader` | Used for sub headings of categories (Pokemon, Trainers, Energies) |
| `ptcgo_total`     | Line for declaring Total Cards amount                             |
| `ptcgo_set`       | Set code and number                                               |
| `ptcgo_quantity`  | Quantity of cards                                                 |
| `ptcgo_card_name` | Card name                                                         |

## Contribute

If you notice any issues, please [open an issue](/issues/new) or fork and create a pull request.

## LICENSE

Copyright 2021 Juha-Matti Santala

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
