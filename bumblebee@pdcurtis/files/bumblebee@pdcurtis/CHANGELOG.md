## Changelog for recent versions

### 3.2.0

Major changes to support vertical panels and to use icons instead of text to harmonise with other cinnamon applets such as nvidia-prime

 * Allow use of vertical as well as horizontal panels after version number check to see if they are supported ie Cinnamon 3.2 and higher
 * Change to TextIcon applet
 * Addition of setting to hide temperatures on horizontal panel.
 * Improved Translation function and translation strings.
 * Changed temporary output file to /tmp/.gpuTemperatureBB

### 3.1.2

Changes to README.md to:

 * Strengthen Rationale for Applet
 * Add Status section noting testing under Mint 17.3 and 18.1 with Cinnamon 3.2
 * Acknowledge first translations.

### 3.1.1

 * Add translation support to applet.js
 * Identify strings for translation and remove leading and trailing spaces and replace with separate spaces where required.
 * Version numbering harmonised with other Cinnamon applets and added to metadata.json so it can show in 'About...'
 * icon.png copied back into applet folder so it can show in 'About...'

### 3.1.0

Initial changes to harmonise with new Cinnamon applets web site and use of new Spices Github Repository for applets.

* Changed help file from help.txt to README.md and copied from applet folder to UUID folder so it shows on web site.

### 3.0.4

Completion of changes to work with Mint 18 and Cinnamon 3.0

 * Added version checks and selection of text editor to display help and changlog  (gedit -> xed)
* Minor enhancements and bugs corrected.

### Previous versions


These versions were developed using my own github repository at ```https://github.com/pdcurtis``` where full details can still be found. In summary:

 * This applet uses a standard framework I first developed for stopwatch@pdcurtis.

 * The Release candidate was available in December 2013 and relatively little further development was required other than some additional error checking.

 * They were comprehensively tested with Cinnamon 2.4 in Mint 17.1, the last LTS version currently supported.
