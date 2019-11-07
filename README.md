# Visual Studio Code Accent
This is intended to be added to the settings.json file on Visual Studio Code. This will give a sort of Accent colour to Visual Studio which is of whatever colour you wish it to be.

![example](https://i.imgur.com/FsMyOq6.png)

The default Colour is set to `#ff0080`, a pink colour to show which areas are changed. However this can be changed easily with a quick replace.

![default colour](https://via.placeholder.com/300x30/ff0080/ff0080/)

## Installation
1. Open up Visual Studio Code.
2. Open the Command panel by using `CTRL/CMD + SHIFT + P`
3. Search for `Open Settings JSON`
4. Copy all of the content from the `settings.jsonc` file in this GitHub repsoitory and paste it into the `settings.json` in Visual Studio Code.
    
    Note it should have the brackets at the start and end still.
    ```
    {
        "workbench.colorCustomizations": {
            ...
        }
    }
    ```
5. Save the file

You should see some things update, Most notably the Bottom bar.

## Change the colour.
As mentioned the default colour is set to `#ff0080`, which is only used to be a bright colour to show off where things are.
to change this colour (skip to step 3 if you already have `settings.json` open):

1. Open the Command panel by using `CTRL/CMD + SHIFT + P`
2. Search for `Open Settings JSON`
3. Open the Search by using `CTRL/CMD + F`
4. Click the Arrow on the left side to show 2 Textboxes.
5. In the top box pick the current colour that is used. Default is `ff0080`
6. In the bottom box pick the new colour you would like. I.E. a nice Dark blue `0d47a1` (You require a 6 character hex code for replacing)
7. Select the Replace all Button or use the Keybind of `CTRL/CMD + ALT + Enter`
8. Save the `settings.json` file.

You should see some things update, Most notably the Bottom bar.

## Choice of Colour
Currently this has been developed for Dark Theme with a Darker colour, meaning that using some Light Colours / Light theme may have some issues such as text being hard to read due to the contrast.
I plan to make updated/additional sections for fixing these issues.

Additionally each person has different preference towards how they would like the application to look, and is why I have commented the sections breifly to allow for easier access and change of items that people might want to adjust the colours themselves. Some Darker colours require a higher opacity on Highlighting to be visible compared to brighter colours.
