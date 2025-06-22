# Firefox Bookmark Toolbar Customization

Firefox includes no way to customize bookmark toolbar icons nor label. This css allows you to define icons to use, or to hide/change labels.

### Usage
The contents of this repo must be placed inside a `chrome` directory within the Firefox root user profile. This works on any of Linux, macOS, or Windows.

### Installation
1. Locate the active profile's root directory from `about:profiles`
2. Clone this repository into a subdirectory named `chrome`.
   ```
   mkdir -p <root-profile-directory>/chrome
   git clone git@github.com:DeadBranches/firefox-custom-toolbar-icons.git <root-profile-directory>/chrome
   ```

#### Thanks to
Vectors and icons by [SVG Repo](https://www.svgrepo.com)
