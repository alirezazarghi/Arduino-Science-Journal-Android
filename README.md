<h3 align="center">
  <img src="https://content.arduino.cc/assets/SJ_Banner_Github2.png" alt="Science Journal Logo" width="700">
</h3>

[![Twitter: @Arduino](https://img.shields.io/badge/Contact-%40Arduino-orange)](https://twitter.com/arduino)
[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

[Arduino Science Journal for Android][play-store] allows you to gather data from the world around you. It uses sensors to measure your environment, like light and sound, so you can graph your data, record your experiments, and organize your questions and ideas. It's the lab notebook you always have with you.

![Arduino Science Journal](https://content.arduino.cc/assets/SJ-screen_mockup_Blogpost%20-%20Main%20Pic.png)


## Features

* 📈 Visualize and graph data from a variety of sources including your device's built-in sensor
* 📲 Connect to external sensors over BLE .
* 📷 Annotate with pictures and 📝 notes.

## Building the app

Download the source, go into the OpenScienceJournal directory and run:

    ./gradlew app:installDebug

Alternatively, import the source code in OpenScienceJournal into Android Studio (File, Import Project).

Note: You'll need Android SDK version 27, build tools 23.0.3, and the Android Support Library to
compile the project. If you're unsure about this, use Android Studio and tick the appropriate boxes
in the SDK Manager.

The [Arduino Science Journal README](https://github.com/arduino/Arduino-Science-Journal-Android/blob/main/OpenScienceJournal/README.md)
contains details about the organization of the source code, and the relationship of this published source
to the [published app][play-store].

### Google Drive Sync

In order to enable Google Drive Sync, you must first create a Google API project and enable the Drive API 
for your app. See instructions in the 
[Google Drive API documentation](https://developers.google.com/drive/api/v2/enable-drive-api)


## Contributing

Please read our [guidelines for contributors][contributing].

## License

Open Science Journal is licensed under the [Apache 2 license][license].

## More

Science Journal formerly brought to you by Making & Science, an initiative by Google. Arduino Science Journal is now an official [Arduino Education] product.

## Security

If you think you found a vulnerability or other security-related bug in the Arduino Science Journal, please read our [security policy](https://www.arduino.cc/en/Main/Security) and report the bug to our Security Team 🛡️ Thank you!

e-mail contact: [security@arduino.cc](mailto:security@arduino.cc)

[play-store]: https://play.google.com/store/apps/details?id=cc.arduino.sciencejournal
[contributing]: https://github.com/arduino/Arduino-Science-Journal-Android/blob/main/CONTRIBUTING.md
[license]: https://github.com/arduino/Arduino-Science-Journal-Android/blob/main/LICENSE
[Arduino]:https://arduino.cc
[Arduino Education]: https://www.arduino.cc/education
