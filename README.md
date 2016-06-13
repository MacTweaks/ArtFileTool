**Hosted by https://www.mactweaks.net**

##Built copy of artFileTool for 10.7, 10.8, 10.9, 10.10

Downloads have been included where there isnt one available directly from the developer


**Source**

http://ctf0.deviantart.com/journal/Mountain-Lion-Mavericks-Theme-Resources-319281804


**Developer**

https://github.com/alexzielenski/artFileTool

**Instructions**

1) In Finder go to /System/Library/ and search for ArtFile.bin

2) Copy ArtFile.bin to the folder that contains artFileTool

3) In Terminal cd to the directory containing artFileTool

4) Decode ArtFile.bin by pasting this command into Terminal

```./artFiletool -d ArtFile.bin artfiles```

5) Open the files in an image editor and make changes by drawing over the image

6) Export the design using the same dimensions and format as the original image

7) Replace the original image with the edited version

8) Encode artfiles folder by pasting this command into Terminal 

```./artFiletool -e artfiles ArtFile.bin ArtFile.new.bin```

9) Replace the default ArtFile.bin with the edited version

10) Logout to see the changes

**Notes**

• I couldnt change the colour of the status bar or add a border to the context menu like Flavours can but you can still use flavours in combination with a modified .bin file to do that. flavours must be activated last.

• The contents of the .bin files are different for each version of OS X and they are not compatiable with one another.

• Note the amount of files that have been decoded and encoded they must match up. If they don't there is a problem.

• Use pixel preview in an image editor and quicklook in the finder to make sure that everything is pixel perfect.

• Make alias folders or scripts to reopen specific files and folders at log in.

• If something goes wrong the GUI will look very messy and you may not be able to navigate through it. I recommend installing another copy of OS X to a second partition so that you can easily restore the .bin file from there

• Edit .pdf files directly by opening them in a vector graphics editor

• The s/artFileTool will decode and encode the .bin file located in the same folder as s/artFileTool and will never edit that file, that is your default .bin file unless you replace it. 

• You can specify a different file by replacing ‘artfiles’ in the command with the path to a different file. 

• You can change the name and location of the output file by replacing ArtFile.new.bin with a new name and location, for example, you could put it straight back into its system location in conjuction with sudo. 

• Turn off flavours to see the full effect of modified .bin files.
