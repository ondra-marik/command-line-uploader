TestFairy Command Line Uploader
===============================

TestFairy's Command Line Uploader is a shell script to upload your IPA or APK files to TestFairy for monitoring and distribution.

There are 4 shell scripts in this repository:

* `testfairy-uploader.sh`
  Will upload iOS IPA files or Android APK files to TestFairy for distribution.

* `testfairy-upload-android-no-sdk.sh`
  Will upload APK files that do not include the TestFAiry SDK to TestFairy. The script Will sign the APK with your keystore and certificate. This is for adnaced users only.

* `testfairy-upload-android-windows.bat`
  Will upload APK Files from Windlows servers.

* `iOS`
  Special script for iOS, which can be used to automatically export IPA and upload in to TF in one step. To use it, you can for example add ${PROJECT_DIR}/tf_export_upload.sh and provide build settings in scheme archive Post-action script (don't forget to make sh file executable). Both files need to be in project root directory (or script needs to be modified).

When working with these shells scripts, notice that you will have to edit them and provide your **API KEY** and (optionally) other values such as testers groups to invite, metrics to record and other settings.

Support
=======

For support, please visit our FAQ at http://docs.testfairy.com/FAQ.html
For questions not covered there, please contact support via the developer dashboard.

License
=======

Released under Apache License.
