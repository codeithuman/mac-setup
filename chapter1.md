# System Preferences

- **OS X** updates
- **Finder**
- **Dock**
- **Menu bar**
- **Spotlight**
- Accounts


## Update OS X

First thing to do is make sure you are running the latest version of OS X. Navigate to **Apple Icon > App Store... > Updates**. Install any updates listed here.


## Finder

#### Show Hidden Files/Folders
Show hidden files and folders in Finder. Open Terminal and enter the following commands:

```
defaults write com.apple.finder AppleShowAllFiles YES; killall Finder;
```

To hide hidden files and folders, enter the following commands:

```
defaults write com.apple.finder AppleShowAllFiles NO; killall Finder;
```


#### Default Finder Window

Under **Finder > Preferences**:
- **General** > Show these items on desktop: Check only "Hard disks" and "External disks"
- **General** > New Finder window show: Select your user name
- **Tags**: Deselect all tags
- **Sidebar** > Only Select: "Applications", "Desktop", "Documents", "Downloads", "Pictures", "Username", "Connected servers", "Username's MacBook Pro", "Hard disks", and "External disks"
- **Advanced**: Check all 3 boxes and select "Search This Mac" from the drop down

## Dock

These are my preferred dock settings. Feel free to use your own.

Navigate to **Apple Icon > System Preferences > Dock**.

- Dock size, close to "small"
- Deselect "Magnification"
- Position on screen: "bottom"
- Select "Automatically hide and show the Dock" along with other 3 options already selected by default


## Power Settings

Navigate to **Apple Icon > System Preferences > Engery Saver**.

- Select "Automatic graphics switching"
- Computer Sleep - Battery: 15 minutes, Power Adapter: Never
- Display Sleep - Battery: 2 minutes, Power Adapter: 10 minutes
- Leave other check boxes as default