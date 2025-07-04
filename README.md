# File Explorer

File Explorer is a Windows file manager application that has an interface similar to Windows Explorer.
However, it browses and searches folders with many files faster than Windows Explorer.
It also has many features that are not available in Windows Explorer.

## Features

### Tabbed Browsing

When you click a folder with the middle mouse button or the CTRL key and the left mouse button, the folder opens in a new tab.
Tabbed browsing lets you keep multiple folders open and switch quickly between them.
You can detach the tabs in to a new window by dragging a tab and move it up or down from the tabs bar. 

### Combined Navigation & Content View

File Explorer has a different content view than Windows Explorer: a combination of the navigation pane and the detailed view.
You can navigate through folders by selecting them in the navigation pane or double-clicking them in the main pane, which also sets the current working directory.
In addition, you can also expand the subfolders of the current working directory in the main pane and view both folders and files in a tree-like fashion.

### Batch Rename

You can rename multiple files by using Excel-style formulas.

### Standard Windows and Custom Context Menu

File Explorer normally shows its own context menu when you right-click on an item. If you want to display standard Windows context menu, you can right-click on files or folders while pressing CTRL key.

You can create your own custom context menu items and specify what will happen when you click them.
Custom menu items will appear when you right click files and/or folders.
You can filter which menu items will appear for which item types.

* Extension Filter: Menu will appear in files with the specified extensions
* Selection Filter: Menu will appear if selection is single or multiple.
* Item Type Filter: Menu will appear if selection is file or folder.

You can use expressions while creating custom context menu items.
Assume that you want to create a context menu item that creates thumbnail images when clicked by using a movie thumbnailer software, such as MTN.exe (http://moviethumbnail.sourceforge.net/)

Then you can  use the following expression: '-P -i -o .jpg -c 3 -r 4 "' + [Path] + '"'

It will create a thumbnail .jpg image of 4 rows and 3 columns with the same location and name of the video file.
You can tweak the arguments for your needs.


### Default Columns

By default, FileExplorer displays basic file system information:

* Name
* Type
* Size
* Date Created
* Date Modified

You can add other columns by clicking "Add Column" menu:

* Basic File Info
  * Extension
  * Parent Name
  * Parent Path
  * Path
* Image File Info
  * Width
  * Height
* Video File Info
  * Duration
  * Frame Width
  * Frame Height
* Audio File Info
  * Bitrate
  * Sample Rate
  * Channels
* Music File Info
  * Album
  * Title
  * Genre
  * Album Artists
  * Contributing Artists
  * Composers
  * Year
  * Track
  * Track Count

### Custom Columns

You can create calculated columns by using Excel-style formulas.


### Preview Pane

The Preview Pane at the rightmost of the application supports preview for the following file types:

* Image Files (.avif, .bmp, .dib, .gif, .heic, .heif, .ico, .icon, .jfif, .jpe, .jpg, .jpeg, .jxr, .png, .rle, .svg, .tif, .tiff, .wdp, .webp)
* Word Files (.rtf, .doc, .docx, .docm, .dot, .dotm, .dotx, .odt, .epub, .htm, .html, .mht)
* Excel Files (.xls, .xlt, .xlsx, .xltx, .xlsb, .xlsm, .xltm, .csv)
* Text Files (.txt, .xml, .cs, .sql ...)
* PDF Files (.pdf)

Note that some extensions (such as Word and Excel) may take a long time to load. You can disable them in Extension Manager.
You can also set priority for extensions that can preview the same file types.
For example, both Text and RichText extesions can preview HTML files. If you set one of them as preferred, HTML files will be previewed using this extension.



### Filtering

You can filter file and folders by using Excel-style drop-down filter.



The Filter Editor allows you to build complex filters. You can add filter conditions and use logical operators to group filters.



### Conditional Formatting

File Explorer provides a conditional formatting feature, which allows you to change individual cells or rows' appearance based on specific conditions.
This feature helps to highlight critical information, identify trends and compare data.



### Save&Load Layout

You can save the layout of the current folder (and all its subfolders if you want) with all your customizations: sorting, grouping, filtering, custom columns etc.
The next time you browse this folder, the saved layout will be loaded automatically.



### Tree View Sorting

One of the limitations of Windows Explorer is that it only allows sorting of folders in list view.
File Explorer also allows you to sort the subfolders of the current folder in the tree view.



### Drag&Drop Support

File Explorer fully supports drag-and-drop operations with other applications, including Windows Explorer.



### Row Number

You can show or hide row numbers in the file explorer.



### Printing and Exporting

You can print folder contents with all the customizations you make or export them to different file formats (such as Excel or PDF).



### Themes

File Explorer comes with 12 themes (light & dark) , including Windows 10, Windows 11, Visual Studio and Office 2019.
