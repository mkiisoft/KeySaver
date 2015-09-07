KeySaver
=================
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/mkiisoft/KeySaver)

Light & Fast Shared Preference. Only 2Kb

KeySaver is a data store simplifier to save, check and remove keys and values with a single line.

# Install

## Android Studio:

Save **KeySaver.jar** file, copy in your "libs" folder (normally inside "app" folder) > Right Click your project > Open Module Settings > over "app" go to Dependencies tab and hit the + button > Select "File Dependency" and Select "KeySaver.jar" > OK to finish

# Changelog

First release v.1.0

# Howt to use:

## Save Data
``` 
KeySaver.saveShare(this, "your-key", "your-value");
```
## Check Data
``` 
if(KeySaver.isExist(this, "your-key")){
            // Do anything here if true
            Toast.makeText(this, "hello world!", Toast.LENGTH_SHORT).show();
        }
```
## Remove Data
``` 
KeySaver.removeKey(this, "your-key");
```

# NOTE:

It works with Activity and Context. Save, Check and Remove anywhere!
