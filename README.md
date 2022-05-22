# Important
Yea... this isn't getting updated anytime soon.

___

![Brave-Fox Banner](https://preview.redd.it/7ilia7199au71.png?width=2736&format=png&auto=webp&s=2bb02f857421d02dc86246baece4b20b41caf698)
# Brave-Fox
Brave-Fox is a Firefox Theme that brings Brave's design elements into Firefox.

## Versions
There are two versions of Brave-Fox: `Overflow` & `Non-Overflow`.

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

# Extras
[Fluent Reveal Tabs](https://github.com/aminomancer/uc.css.js/blob/master/JS/fluentRevealTabs.uc.js)

This adds Chromium's "flashlight" hover effect on tabs, just like Brave & Chrome have. Be warned tho, this is a JS script and needs a [script manager](https://github.com/MrOtherGuy/fx-autoconfig)
