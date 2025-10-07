# Metal Archives Visual Tweaks - Userscript

This userscript customizes the appearance of the [Metal Archives](https://www.metal-archives.com/) website by hiding specific elements, styling the login input fields, and adjusting the width of the news section.

## Features

- **Hide specific elements** by ID (e.g., `topStats`, `latest`, etc.)
- **Style login inputs** by setting a custom width (128px) for the username and password fields.
- **Adjust the width** of the news section to 1024px.
- **Easy to configure**: Add or remove elements to be hidden and modify styles directly in the script.

## Installation

1. Install a userscript manager, such as [Tampermonkey](https://www.tampermonkey.net/) or [Greasemonkey](https://www.greasespot.net/).
2. Create a new userscript.
3. Copy and paste the contents of this script into the userscript manager.
4. The script will automatically run on [Metal Archives](https://www.metal-archives.com/) once you load the site.

## Usage

- Once installed, the script will:
  - Hide the `topStats` and `latest` elements (you can add more in the configuration).
  - Style the login form inputs to have a width of 128px.
  - Change the width of the `news` section to 1024px.

## Customization

- You can customize the elements to hide by modifying the `idsToHide` array.
- You can also change the width values for the login inputs and the news section by editing the script.

## License

This project is open-source and available under the MIT License. See the [LICENSE](LICENSE) file for more information.
