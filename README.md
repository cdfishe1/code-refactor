[![Generic badge](https://img.shields.io/badge/license-MIT-<COLOR>.svg)](#license)


# Horiseon Code Refactor Project

I was hired by Horiseon Social Solution Services Inc. to refactor their landing page in order to enhance its accessibility for search engines.

## Table of Contents
* [Horiseon Social Solution Services Landing Page](#horiseon-landing-page)
* [Deployment](#deployment)
* [Scope of Project](#scope-of-project)
* [Installation](#installation)
* [Featured Code](#featured-code)
* [Testing](#testing)
* [Credits](#credits)
* [License](#license)

## Horiseon Landing Page

![Image of Horiseon Landing Page](assets/images/01-html-css-git-homework-demo.png)

## Deployment

Site deployed at [Horiseon Social Solution Services Inc.](https://cdfishe1.github.io/code-refactor/)

## Scope of Project

* Replaced All `<div>` elements with semantic elements.
* Gave non-icon images `alt` attributes.
* Fixed anchors in the navigation bar to link to their respective page section.
* Reorganized headings to show site structure better.
* Added hidden headings to sections without visibile section headings. [See Featured Code](#featured-code)
* Reorganized CSS to correspond to section structure.
* Refactored CSS to eliminate repetitious code.
* Added comments in both html and css files to allow for easier site maintenance.

## Installation

Deploy the html file and assets folder that contains the images and css file on your website host server.

## Featured Code

I added hidden headings to sections that lacked a visible heading. In order to implement this without change to the layout of the landing page, I used the following css in Chris Coyer's CSS-Tricks article [Accessibility/SEO Friendly CSS Handling](https://css-tricks.com/snippets/css/accessibilityseo-friendly-css-hiding/)

```
.screen-reader-text {
  
  position: absolute;
  top: -9999px;
  left: -9999px;
}
```

## Testing

Tested accessibility using [WAVE web accessbility evaluation tool](https://wave.webaim.org/report#/https://cdfishe1.github.io/code-refactor/)

* Generates 0 errors.
* Contrast errors unavoidable due to requirement to maintain the design of the landing page.

## Credits

* Chris Coyer [Accessibility/SEO Friendly CSS Handling](https://css-tricks.com/snippets/css/accessibilityseo-friendly-css-hiding/)
* Lilian Besson [README.md badges](https://github.com/Naereen/badges/blob/master/README.md)

## License

Copyright (c) Horiseon Social Solution Services Inc. All rights reserved.

<details><summary>Licensed under the MIT License</summary>

Copyright (c) 2021 - present | Horizon Social Solution Services Inc.

<blockquote>
Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
</blockquote>
</details>