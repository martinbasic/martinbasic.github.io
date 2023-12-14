# MartinBasic's Tree of Links

## About this site 

This site is based on [johnggli/Linktree](https://github.com/johnggli/linktree), which let me to list all the social media on [fediverse](https://en.wikipedia.org/wiki/Fediverse) and related links.

johnggli/Linktree is a lightweight, customizable open source project that can be used as a free alternative to the Linktree website.

Font credit to [Perfect DOS VGA 437 Font](https://www.dafont.com/perfect-dos-vga-437.font).

## What are the differences, compared to the original one?

* All background animation has been removed.
* The modal/popup window for displaying the profile picture has been removed.
* The quote inside the modal/popup window has been moved underneath the user name.
* Support displaying multiple sections of `<div class='links'>` instead of `<div id='links'>` to easier classifing all the social links.
* To match the customized terminal user interface (TUI) style, `<fieldset>` and `<legend>` will be used inside the main link list block.
* Supports labels (`link readonly`) and disabled link (`link disabled`) in link lists.
* Footer has been added to display additional message.
* A (fake) blinking cursor.

## Getting Started

To use this project on your site:

1. Download the ZIP from the repository directly.
2. Extract the ZIP file. 
3. Open the folder just downloaded using any preferred text editor, for example in VSCodium, click `File` > `Open folder`, and then select the folder that contains all the extracted file contents from Linktree repository.
4. Edit the files to match your profile requirements if needed, this including but not limited to:
    - Changing the profile image, username, quotes, hashtags and footer messages inside `index.html`.
    - Chnaging colors, fonts and background color inside the `--root` section of  `css/style.css`.
    - If you want to use image as background instead, navigate to the `body` section, replace 
        ```css
        background: var(--bgColor);
        ```
        with
        ```css
        background-image: url('../img/background_image.png');
        ```
5. Open `index.html` to preview your result using any preferred web browser.

## License

Please refer to the [license](LICENSE.md)