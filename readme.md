# GithubCorner Web Component

This repository contains the `GithubCorner` web component, a customizable, reusable piece of UI that can be easily integrated into any web page. This component is designed to provide a GitHub corner banner, typically used for linking back to the GitHub repository of the project.

## Features

- Customizable `href` for setting the URL of your GitHub repository.
- Customizable colors for the SVG icon, with default and hover states.
- Easy integration with any web project.
- Shadow DOM encapsulation to prevent style conflicts.

## Installation

To use the `GithubCorner` component in your project, follow these steps:

1. Clone this repository or download the `github-corner.js` file.
2. Include the script in your HTML file:

```html
<script type="module" src="github-corner.js"></script>
```

## Usage

After including the script in your HTML, you can use the github-corner element anywhere in your HTML:

``` html
<github-corner href="https://github.com/your-repo" fill-color="#fff" hover-color="blue"></github-corner>
```

Attributes
----------

* `href (string)` The URL to your GitHub repository.
* `fill-color (string)` The fill color of the SVG icon.
* `hover-color (string)` The color of the SVG icon on hover.



Customization
-------------

You can customize the component by setting the following attributes:

*   **href**: Change this to point to your own GitHub repository.
*   **fill-color**: Set the default color of the GitHub icon.
*   **hover-color**: Set the color of the GitHub icon when hovered.

Example:

htmlCopy code

`<github-corner href="https://github.com/example" fill-color="black" hover-color="green"></github-corner>`

Browser Support
---------------

This component uses modern web standards and is best suited for use in modern browsers.

Contributing
------------

Contributions are welcome! Feel free to open issues or submit pull requests to improve the `GithubCorner` web component.

License
-------

This project is open source and available under the MIT License.