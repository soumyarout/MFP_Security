IBM MobileFirst Platform Foundation
===
## PinCodeCordova
A sample application demonstrating use of the CredentialsValidation Security Check.

### Tutorials
https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/authentication-and-security/credentials-validation/

### Usage

1. Use either Maven, MobileFirst CLI or your IDE of choice to [build and deploy the available `ResourceAdapter` and `PinCodeAttempts` adapters](https://mobilefirstplatform.ibmcloud.com/tutorials/en/foundation/8.0/adapters/creating-adapters/).

2. From a command-line window, navigate to the project's root folder and run the commands:
 - `cordova platform add` - to add a platform.
 - `mfpdev app register` - to register the application.
 - `mfpdev app push` - to map the `accessRestricted` scope to the `PinCodeAttempts` security check.
 - `cordova run` - to run the application.

3. Run the application in an Android Rmulator, iOS Simulator or physical device. Press the **Get Balance** button and enter "1234" to display the balance.

