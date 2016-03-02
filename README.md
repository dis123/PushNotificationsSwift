IBM MobileFirst Platform Foundation
===
## PushNotificationsSwift
A sample application demonstrating use of push notifications in iOS applications.

### Tutorials
https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/notifications/

### Usage

1. From a command-line window, navigate to the project's root folder and run the command: `mfpdev app register`.
2. In the MobileFirst console, under **Applications** → **PushNotificationsSwift** → **Security** → **Map scope elements to security checks**, add a mapping for `push.mobileclient`.
3. Via the MobileFirst Operations Console, setup the MobileFirst Server with either GCM details or APNS certificate, and add tags.
4. Import the project to Xcode, and run the sample by clicking the **Run* button.

Notes:

* Must be tested on physical devices.
* The BundleID must relate to an AppID configured with push notifications.
* The certificate must be uploaded via the MobileFirst Operations Console.

### Supported Levels
IBM MobileFirst Platform Foundation 8.0

### License
Copyright 2015 IBM Corp.

Licensed under the Apache License, Version 2.0 (the "License");
you may not use this file except in compliance with the License.
You may obtain a copy of the License at
att
http://www.apache.org/licenses/LICENSE-2.0

Unless required by applicable law or agreed to in writing, software
distributed under the License is distributed on an "AS IS" BASIS,
WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
See the License for the specific language governing permissions and
limitations under the License.
