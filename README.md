First adjust `a.cmd` to have correct paths to Android SDK, Android NDK and Java SDK.
Then set `APK` varible to desired apk package name.

Use `a.cmd` to build & run the application:

    a.cmd command

    Where command is:
      go        - builds, installs and runs .apk file
      run       - installs and runs .apk file
      build     - only builds .apk file
      remove    - removes installed .apk
      install   - only installs .apk file on connected device
      launch    - ony runs already installed .apk file
      log       - show logcat
