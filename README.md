# Graph-Editor-Android-bin
built apk of [android app source](https://github.com/Student-Team-Projects/Graph-Editor-Android), [core source](https://github.com/Student-Team-Projects/Graph-Editor-Core)
# Before installation
Make sure you have android-tools installed. If not, type
```sh
$ sudo pacman -S android-tools
```

# Install on your android
Clone this repo. Make sure your phone is connected and developer options are enabled.
```sh
$ cd opt
$ adb install -t graph-editor-for-android.apk
$ adb shell am start -n "com.example.graph_editor/com.example.graph_editor.menu.MenuActivity" -a android.intent.action.MAIN -c android.intent.category.LAUNCHER
```

In order to install plugins, open Extensions Activity and connect to your own server or just use one available at 20.219.148.153