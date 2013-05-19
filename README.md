# SPSS Bundle for TextMate

SPSS Bundle for IBM SPSS Syntax files. Does very basic syntax highlighting for most commands and subcommands (based on the IBM SPSS Statistics 19 Command Syntax Reference). Includes a few handy snippets (e.g. for defining macros) and a command for loading the current file into SPSS.

## Author

* Bart Kamphorst

## Project status disclaimer

This bundle is not actively developed. After yet another expired license, I have decided to try my luck with R instead. However, if you have specific requests for this bundle, feel free to create a github issue and I'll see what I can do. Or, even better, fork the project, modify the bundle, and send me a pull request.

## Install

The quickest way to install the bundle is by using git on the command line.

### Install with Git

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone https://github.com/bartkamphorst/SPSS.tmbundle.git 
    osascript -e 'tell app "TextMate" to reload bundles'

Alternatively, the bundle may be installed graphically.

### Install from the GUI

1. Download the zip from [https://github.com/bartkamphorst/SPSS.tmbundle/zipball/master](https://github.com/bartkamphorst/SPSS.tmbundle/zipball/master).
2. Unzip the downloaded zip file. 
3. Rename the unzipped directory to 'SPSS.tmbundle'.
4. Double-click the 'SPSS.tmbundle' file.
5. open TextMate and select the following menu item: _Bundles > Bundle Editor > Reload Bundles_

## A note about the commands

For the interaction with SPSS to work, make sure to define the TM_SPSS environment variable in TextMate and have it point to the stats command (by default found in the SPSS .app bundle under Contents/MacOS).

