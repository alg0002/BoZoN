
# Version history

## New in 2.3
- Added : folder size limit for users (if there's no limit, the free space icon will not display)
- Added : display free space in user's folder (this information will not display if admin or if allowed free space is set to 0)
- Added : display folder size
- Added : lazy load for gallery http://dinbror.dk/blazy/
- Added : a minimalist lightbox
- Bugfixes : links lost when moving a file/folder, video name in gallery mode...
- Enhancement : brand new html/css structure by Eauland.
- Enhancement : new table based file list
- Added : some information on homepage
- Added : qrcode on share page
- Added : playlist audio. If a folder only contains mp3/ogg, it'll be shared as a playlist
- Added : a shortcut to share link in links mode
- Added : an icon to go directly to a gallery or a playlist in file mode
- Changed : the dropzone is now hidden by default: click on upload button or drag a file on it to reveal the dropzone
- Added : an option to easily change the colors: just change the values in template/default/css/styles.php !
- Changed : color 
- Removed : old time forgotten javascript in stats.php
- Added : scrolltotop from Cyril MAGUIRE
- Added : download from url allows to specify a local filename
- Added : a required state for important fields in dialog boxes
- Bugfix : remove exif error on thumb generation
- Added : sorting filelist by name or size
- Enhancement : A burn mode id stays in burn mode when accessed by the connected owner (id will be burned only if not connected or not owner)
- Bugfix : security bug
- Added : multiselection to delete filses/folders

## New in 2.2beta
- Added : double check for the password on profile creation
- Added : password change for user connected
- Added : markdown display for md files 
- Added : qrcode to easily get a share on smartphone 
- Added : secured rss feed for log file
- Added : share folders between users \o/
- Added : changes on files/folders only allowed to the owner
- Bugfixes: htaccess problems, catching distant file path problem, some css problems

## New in 2.1
### /!\ Read carefully to avoid data loss !
- added a top bar menu
- added a minimalist auto gallery function: when a folder contains only images, it will be displayed as a gallery for the user.
- bug fix on rss feed and share links
- Added multiuser capacity ! Now, the admin (the first user) can create new users. Each user has his own separated upload folder.
- Added a import script: beacause of multiuser change, the ID file, the upload folder, the users data has a new format...
If you're upgrading from 2.0 or less, keep only private and upload folders, install bozon. 
When you first start, it will ask you if you want to import previous data.

## New in 2.0 beta
- major changes in bozon's structure: all is called from index page
- real home page
- major design improvements: lighter, no more menu etc.
- bugfixes
- all pages'files are now in the template folder (easier to modify)
- html files replace the variable template (easier for designers ;-) 
- language files are now seperated in a locale folder
- language can now also be changed in user mode (not only admin)
- default language: set at browser default if not specified in config

## New in 1.7.5b
- added a function to erase no longuer used ids
- bugfix with file with accent on first char: a basename function bug ! oO

## New in 1.7.5
- change in the templates: templates are now html files, easier to modify
- added the mode in the file list's title.


## New in 1.7.4
bug fixes (thx to chatainsim on Github)
- #56: problem deleting a folder
- #53: error deleting files you just uploaded
- #55: password protection problem when a password is used for several files (caution, this fix is not compatible with old password protection)
- disapearing files and folders until page is refreshed.
- my blog's URL removed (too «hasbeen»: wink to eauland ;-)


## New in 1.7.3
- some bugs fixed (rename bug, home icon bug)
- little changes on resolutions below 600 (switch from icon to list view)
- added handheld rule for media queries


## New in 1.7.2
- new list layout (change layout in config or in menu)
- change theme with get variable theme=xxx
- 

## New in 1.7
* serious security enhancement by Oros ( https://www.ecirtam.net / https://github.com/Oros42 ) (Thanks a lot for this huge job !)
* add: a link to clear stats
* BEWARE! Because of the new data & files structure, all previous generated IDs will no longer be valid. 