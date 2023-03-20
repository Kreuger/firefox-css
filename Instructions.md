## How to setup Firefox for custom CSS.
1. Open the browser and go to about:config
2. Search for toolkit.legacyUserProfileCustomizations.stylesheets and change the value to true. 
3. Open about:support
4. Click on "Profile Folder" -> "Open Folder"
5. Create a sub-folder named "chrome"
6. Change into the new folder
7. Download and save the files from here (any .css file) into that folder
8. Restart Firefox
9. ???
10. Profit!

## How to setup the custom start page.
1. Install the nightTab extension [See here](https://addons.mozilla.org/en-US/firefox/addon/nighttab/)
2. Open the nighTab_backup.json file and switch to raw view. (Saving off github wont allow import). 
3. Copy and paste the raw data into a file in the extension directory. Save as nightTab_backup.json.
4. Open the nighTab settings page.
5. Click on data, then click import data and select the nightTab backup.json file you previously saved.
