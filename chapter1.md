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



## Dock

These are my preferred dock settings. Feel free to use your own.

Navigate to **Apple Icon > System Preferences > Dock**.

* 