# Brave-Fox
Firefox Stylesheet To Add Brave-Like Elements

## Versions
There are two versions to Bave-Fox: `Overflow` & `Non-Overflow`.

### Overflow vs Non-Overflow
Chromium-based browsers do this thing where with every new tab, each other tab gets smaller and smaller, till you open enough tabs that newer ones stop displaying after a certain number of tabs. Firefox said "nah", and just decided to add a scroll wheel onto the tab bar.

Adding the `Remove Overflow.css` file to the Brave-Fox folder will disable Firefox's tab scrolling and enable chromium-like tab behaviour.

## Explanation
I highly recommend you read the [documentation](https://brave-fox.notion.site/Overflow-Files-adf332802aab4dcf98785f9b7307ea5f) I spent hours on as it explains every line of code in each file, some also have before and after pictures to show off differences.

## Installation
1. Install the pack you'd like to use, (including the Non-Overflow version if you'd like) (other than ReadMe.md).
2. Move all files to `Chrome Folder`
3. Add the following code to your `userChrome.css` & `userContent.css` files:
```css
/*--------------------------------------------- Brave Fox --------------------------------------------*/
@import url("Brave-Fox/Import.css");
/*----------------------------------------------------------------------------------------------------*/
```
4. Save & restart Firefox.
