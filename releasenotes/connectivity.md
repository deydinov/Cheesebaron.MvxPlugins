### New in 5.0.0

* Updated to MvvmCross 7.0.0
* MonoAndroid10.0 target is now required!

### New in 4.2.0

* Enabled C#8 Nullable Reference Types

### New in 4.1.1

* Updated to MvvmCross 6.4.1

### New in 4.1.0

* Updated to MvvmCross 6.3.1
* Updated Android target to 9.0

### New in 4.0.1

* Added missing netstandard2.0 target

### New in 4.0.0

* Built against MvvmCross 6.2.0
* Namespaces have changed to no longer include .{Platform Name} in the end
* All projects have been converted to multi-target
* Plugin now use new MvvmCross plugin system with `[MvxPlugin]` attribute

### New in 3.2.0

* Built against MvvmCross 5.4.2
* Android implementation accomodates new rules about having to explicitly register broadcast receivers

### New in 3.1.0

* Built against MvvmCross 5.0.2
* Added GetAllWifiInfo implementation on UWP

### New in 3.0.0

* Discontinued Windows Phone 8.1 and Windows 8.1 support in line with latest MvvmCross develop builds
* Added UWP implementation

### New in 2.0.0

* Removed usage of deprecated ConnectivityManager.ExtraNetworkInfo
* Built against MvvmCross 4.2.3
* Aligned version numbers accross all Cheesebaron.MvxPlugins

### New in 2.1.0

* Built against MvvmCross 4.3.0

### New in 2.2.0

* Built against MvvmCross 4.4.0
* Added new IWifi interface for getting Wifi SSID's and other information

### New in 2.2.1

* Now calls connectivity check in Constructor on Android to get initial status

### New in 2.2.2

* Added PreserveAttribute to help linker