UVCCamera
=========

library and sample to access to UVC web camera on non-rooted Android device

Copyright (c) 2014-2017 saki t_saki@serenegiant.com

 Licensed under the Apache License, Version 2.0 (the "License");
 you may not use this file except in compliance with the License.
 You may obtain a copy of the License at

     http://www.apache.org/licenses/LICENSE-2.0

 Unless required by applicable law or agreed to in writing, software
 distributed under the License is distributed on an "AS IS" BASIS,
 WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
 See the License for the specific language governing permissions and
 limitations under the License.

All files in the folder are under this Apache License, Version 2.0.
Files in the jni/libjpeg, jni/libusb and jin/libuvc folders may have a different license,
see the respective files.

How to compile library  
=========
If you want to use Android Studio(unfortunately NDK supporting on Android Studio is very poor though),
1. make directory on your favorite place (this directory is parent directory of `UVCCamera` project).
2. change directory into the directory.
3. clone this repository with `git  clone https://github.com/saki4510t/UVCCamera.git`
4. start Android Studio and open the cloned repository using `Open an existing Android Studio project`
5a. sdk manager -> sdk tools -> check show package details -> select ndk 16.1
5b. Android Studio raise some errors but just ignore now. Android Studio generate `local.properties` file. Please open `local.properties` and add `ndk.dir` key to the end of the file. The contents of the file looks like this.
```
sdk.dir={path to Android SDK on your storage}
ndk.dir={path to Android NDK 16.1.4479499 on your storage}
```
Please replace actual path to SDK and NDK on your storage.  
Of course you can make `local.properties` by manually instead of using automatically generated ones by Android Studio.
6. Synchronize project
7. execute `Make project` from `Build` menu.



