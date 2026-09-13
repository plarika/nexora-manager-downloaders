# Contributing to Nexora Manager Downloaders

Contributions are welcome through issues and pull requests in `plarika/nexora-manager-downloaders`.

Please keep changes focused, reproducible, and compatible with the current Nexora Manager downloader host API.

Before submitting a change:

- build with JDK 17;
- run `./gradlew assembleRelease`;
- avoid embedding credentials or tokens;
- document behavioural changes;
- preserve GPL-3.0 licensing and upstream attribution where applicable.

Do not rename compatibility API packages unless the matching Nexora Manager migration is included and tested.