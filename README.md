# Roblox Role Dropdown
**Roblox Role Dropdown (RRD)** is a simple tool that adds a dropdown menu to change the role of your group members directly from the group wall.

![Screenshot of RRD in action](https://i.imgur.com/z1e7kPZ.png)

## Installation
This script is designed for use with the Tampermonkey userscript manager, which can be installed [here](https://www.tampermonkey.net/).

The easiest way to install this userscript is through its Greasy Fork page [here](https://greasyfork.org/en/scripts/427430). On this page, click on the "Install" button at the top of the page.

Alternatively, you can copy paste this script's source from [its GitHub](https://github.com/HotDog640/roblox-role-dropdown) into Tampermonkey.

## How to use
1. Go to the group wall of a group you have "Manage lower-ranked member ranks" permissions in.
2. Click the dropdown on the post of a member whose role you wish to change.
3. Click on the desired role.

## Config
At the top of this script's source, there's an object called RRDConfig. You can change these properties to customise its behaviour.
```js
const RRDConfig = {
    enabled: true,              // Set this to false if you want to disable RRD.
    dropdown_width: '12rem'     // The width of dropdown. Can be any CSS length.
};
```

## Disclaimers
- This code is written in ES6 syntax. This may not work on older browsers. As far as I'm aware, if you use a modern version of Chrome, Edge, Firefox, or Opera; you should be fine.
- This should work fine in tandem with BTRoblox and Roblox+, though, this has not been thoroughly tested. (It should work with BTRoblox's "Make Group Wall Paged").
- This does not yet work with Greasemonkey.

## TODO
- Make this work with Greasemonkey.
