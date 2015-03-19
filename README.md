# WP Media Cleaner

Plugin for WordPress that helps cleaning the Uploads Directory and the Media Library. Since the process involves deleting files, the user should be particularly careful and backup the files and database before using it, especially the first time.

This project most recent files will be here, on GitHub, and every stable version will be pushed to the official WordPress repository.

## Installation

Clone it or install it through the WordPress repository.

## Usage

Check the settings then go in the Media > Cleaner.

## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -am 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :) Thanks!

## History

### 2.4.0
* Fix: Cross site scripting vulnerability fixes.
* Change: Many enhancements and fixes made by Matt (http://www.twistedtek.net/). Please thanks him :)
* Info: Please perform a "Reset" in the plugin dashboard after installing this new version.

### 2.2.6
* Fix: Scan for multisite.

### 2.2.4
* Change: options are now all enabled by default.

### 2.2.0
* Fix: DB issue avoided trashed files from being deleted permanently.

### 2.0.2
* Works with WP 4.

### 2.0.0
* Gallery support.

### 1.9.4
* I did something but not sure what.
* Ah yeah, I got married :)

### 1.9.2
* Fix: IGNORE function was... ignored by the scanning process.

### 1.9.0
* Add: thumbnails.
* Add: IGNORE function.
* Change: cosmetic changes.

### 1.8.0
* Add: now detects the custom header and custom background.
* Change: the CSS was updated to fit the new Admin theme.

### 1.7.0
* Change: the MEDIA files are now going to the trash but the MEDIA reference in the DB is still removed permanently.

### 1.6.0
* Stable release.

### 1.4.2
* Change: Readme.txt.

### 1.4.0
* Add: check the meta properties.
* Add: check the 'featured image' properties.
* Fix: keep the trash information when a new scan is started.
* Fix: remove the DB on uninstall, not on desactivate.

### 1.2.2
* Add: progress %.
* Fix: issues with apostrophes in filenames.
* Change: UI cleaning.

### 1.2.0
* Add: options (scan files / scan media).
* Fix: mkdir issues.
* Change: operations are buffered by 5 (faster).

### 0.1.0
* First release.

## License

The MIT License (MIT)