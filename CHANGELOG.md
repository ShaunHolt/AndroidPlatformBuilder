### 1.90.9 (2017-03-14) ###
 * do not use patchPluginXml rule

### 1.90.8 (2017-03-14) ###
 * add ninja workaround
 * update platform version to IC-2016.1
 * bump up kotlin to 1.1.0
 * bump up intellij gradle plugin to 0.2.5
 * bump up gradle version to 2.14.1

### 1.90.7 (2016-03-19) ###
 * use kotlin 1.0.1
 * when project is directory base (has .idea), load properly
 * support n preview

### 1.90.6 (2016-03-12) ###
 * some widgets are disabled while build or sync
 * show warning notification when project sdk is invalid

### 1.90.5 (2016-03-04) ###
 * quick fix for auto exclude directories function

### 1.90.4 (2016-03-04) ###
 * quick fix for Android Studio 2.0beta

### 1.90.3 (2016-03-04) ###
 * save state of all comboboxes and load when open project
 * fix extra commands combobox behaviors when have whitespace
 * file chooser will open when press flash button, instead of argument combobox
 * while flashing with device, disable components related flash function
 * internally, ui releated codes are rewritten with kotlin

### 1.90.2 (2016-03-03) ###
 * fix IndexErrorException when cannot find LUNCH_COMBO_MENU value
 * find platform api level, and show notification when module sdk is set invalid
 * use intellij logger instead of print stdout

### 1.90.1 ###
 * add android facet to module forcibly

### 1.90.0 ###
 * toolbar can be working when project is indexing
 * all features are ported to idea components
 * add dependency with android support plugin

### 1.5.1 ###
 * generate buildspec.mk to apply persistent build settings

### 1.5.0 ###
 * restore latest selected item when project is opened
 * fix mm build action in menu

### 1.4.4 ###
 * fix broken mm function
 * strip clang color code in build output when cyanogenmod build
 * enable ccache as default
 * fix to handle build menu action
 * fix to handle mProductOut directory

### 1.4.3 ###
 * fix build output process
 * initial cyanogenmod build support

### 1.4.2 ###
 * fix to handle mProductOut directory

### 1.4.1 ###
 * plugin now supports idea 14.0
 * handle IOException while run executable

### 1.4.0 ###
 * use gradle build system
 * port core api to kotlin
 * exclude out directories automatically
 * kill build and sync processes when close project
 * fix save bug when start to build

### 1.3.0 ###
 * initial public release
