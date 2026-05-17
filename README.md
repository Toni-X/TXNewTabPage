TX Humble New Tab Page
======================

Redesigned new tab page featuring your bookmarks, apps, most visited, and recently closed in a custom layout.

This is a fork of the original [Humble New Tab Page](https://github.com/ibillingsley/HumbleNewTabPage) by ibillingsley.

![](media/shot.1.png)

### Features

- Simple, clean design
- Highly customizable
- Fast loading and lightweight
- **10 independent pages** with page switcher (new in v2.0.0)

This extension replaces the default new tab page. Drag and drop folders to create new columns or reorder them. The font, colors, spacing, and more can be customized from the options menu.


Screenshots
-----------
![](media/shot.2.png)
![](media/shot.3.png)
![](media/shot.4.png)
![](media/shot.5.png)


License
-------

This project is licensed under the **MIT License**, see [LICENSE_MIT.txt](LICENSE_MIT.txt) for details.


Changelog
---------

### Version 2.2.0 - May 17, 2026

- Drag & drop to reorder bookmarks within a folder (syncs with Chrome)

### Version 2.1.1 - March 13, 2026

- Show bookmark favicons in search results
- Increased max search results from 10 to 20
- Show total count when more than 20 results found
- UI refinements: larger page buttons and search input
- Search results now wider (700px) with higher max-height
- Multi-line bookmark titles now wrap properly without going under the icon
- Fixed z-index: options panel now always appears above search results

### Version 2.1.0 - March 12, 2026

- Added search bar next to page switcher
- Search bookmarks in real-time while typing
- Press Enter to search Google
- Navigate results with arrow keys, Enter to open selected bookmark
- Auto-focus search bar when typing non-numeric keys
- Press Escape to clear search

### Version 2.0.3 - January 25, 2026

- Fixed empty background-image CSS rule when no image file is set
- Fixed reset button visibility not updating when switching pages
- Content visibility options (Apps, Most visited, etc.) are now independent per page

### Version 2.0.0 - January 25, 2026

Development continues independently from the original project.

- Added 10 independent pages with page switcher in top-left corner
- Each page maintains its own bookmark layout and folder open/close state
- Keyboard shortcuts: press 1-9 for pages 1-9, press 0 for page 10
- Last active page is remembered across sessions
- Renamed extension to "TX Humble New Tab Page"

### Version 1.26.2 - April 9, 2025

- (Firefox) Removed Favicon Kit and Qwant favicon providers, added Ecosia and Icon Horse

### Version 1.26.1 - October 15, 2023

- (Chrome) Fixed navigating to file:/// URLs (enable "Allow access to file URLs" in Manage Extensions > Details)
- (Vivaldi) Hide bookmark separators

### Version 1.26 - July 2, 2023

- Added font-weight option
- (Chrome) Replaced Apps folder with a link to chrome://apps
- (Firefox) Set home page to new tab page (change in Firefox settings)
- (Firefox) Updated Google favicon provider

### Version 1.25 - March 11, 2023

- Manifest V3
- Updated favicon
- (Firefox) Added Qwant and Yandex favicon providers

### Version 1.24.2 - February 21, 2020

- (Firefox) Added DuckDuckGo favicon provider

### Version 1.24.1 - May 14, 2019

- (Firefox) Set addon ID for consistent page URL

### Version 1.24 - February 10, 2019

- Temporarily disabled weather feature
- Improved keyboard navigation
- Fixed bug opening options
- (Firefox) Changed extension name to HNTP
- (Firefox) Fixed broken favicons
- (Firefox) Fixed context menu not opening

### Version 1.23.3 - December 3, 2018

- (Firefox) Fixed folder closing animation

### Version 1.23.1 - December 2, 2018

- (Firefox) Removed unused "management" permission

### Version 1.23 - December 2, 2018

- Added tooltips for truncated text
- Added option to remember open folders
- (Firefox) Added option for favicon provider

### Version 1.22 - October 15, 2017

- Firefox support

### Version 1.21 - November 20, 2016

- Added HiDPI icons
- Fixed export settings not selectable

### Version 1.20 - June 1, 2016

- Added import/export settings
- Fixed recently closed max items

### Version 1.19 - April 14, 2016

- Fixed weather not updating

### Version 1.18 - April 3, 2016

- Removed geolocation
- Fixed weather error

### Version 1.17 - January 24, 2016

- Fixed weather error

### Version 1.16 - August 29, 2014

- Added other devices folder
- Recently closed tabs preserve history
- Removed background process
- Chrome version 37 or later required

### Version 1.15 - July 6, 2014

- Fixed freezing issues

### Version 1.14 - May 11, 2014

- Reduced memory usage
- Added option to set number of items for recently closed, recent bookmarks, and most visited
- Added option for background image size
- Added link to bookmark manager in folder context menu

### Version 1.12 - August 18, 2013

- Reorder apps via drag and drop

### Version 1.11 - August 3, 2013

- Fixed launching packaged apps (Google Keep)
- Fixed launching file:/// and chrome:// URLs
- Fixed Mobile Bookmarks folder not being removable
- Disable weather if geolocation is denied
- Default layout changed to 2 columns
- Uninstall apps from the context menu
- Hide Google Wallet Service from apps

### Version 1.9 - December 30, 2012

- Uses geolocation for weather by default
- Fixed bug with drag and drop
- Added Chrome Web Store to apps

### Version 1.8 - November 9, 2012

- Redesigned options panel
- Added several new settings
- Performance tweaks
- Source code released under the MIT license

### Version 1.7 - September 8, 2012

- Added custom CSS field for advanced users
- Added option to hide Bookmarks bar and Other bookmarks

### Version 1.6 - August 30, 2012

- Added option to open links in new tabs
- Support local file for background image
- Weather errors fixed

### Version 1.5 - August 29, 2012

- Weather forecast now uses Yahoo
- System font list enabled on supported versions

### Version 1.4 - August 10, 2012

- Added option to disable the weather and other special folders
- Minor bug fixes

### Version 1.3 - August 9, 2012

- Fixed error on old Chrome versions

### Version 1.2 - August 8, 2012

- Added apps, most visited, recently closed, and weather
- More flexible layout with unlimited columns
- Open all links in folder from context menu
- Color themes and new default style
- Added smooth animation and highlight shadow
- Drag and drop to reorder folders and columns
- Background image support
- Bug fixes
- New name (formerly New Tab + Bookmark Tree)

### Version 1.1 - July 20, 2011

- Added options menu

### Version 1.0 - July 17, 2011

- Initial release



