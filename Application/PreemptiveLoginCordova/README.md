IBM MobileFirst Platform Foundation
===
## PreemptiveLoginCordova
A sample application demonstrating implementation of Preemptive Login.

### Tutorials
https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/authentication-and-security/user-authentication/

### Usage

1. Use either Maven, MobileFirst CLI or your IDE of choice to [build and deploy the available `ResourceAdapter` and `UserLogin` adapters](https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/adapters/creating-adapters/).


2. From a command-line window, navigate to the project's root folder and run the commands:
 - `cordova platform add` - to add a platform.
 - `mfpdev app register` - to register the application.
 - `mfpdev app push` - to map the `accessRestricted` scope to the `UserLogin` security check.
 - `cordova run` - to run the application.

### Supported Levels
IBM MobileFirst Platform Foundation 8.0

