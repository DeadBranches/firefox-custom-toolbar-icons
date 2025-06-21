# Firefox Bookmark Toolbar Customization

Firefox includes no way to customize bookmark toolbar icons nor label. This css allows you to define icons to use, or to hide/change labels.

### Usage
The contents of this repo must be located in a directory named `chrome` with the local user profile on Linux, macOS, or Windows.

### Installation
1. Locate the active profile local directory from `about:profiles`
2. Clone this repository into the chrome subfolder of your local profile directory
   ```
   mkdir -p <local-profile-directory>/chrome
   git clone git@github.com:DeadBranches/custom-firefox-toolbar-icons.git <local-profile-directory>/chrome
   ```
