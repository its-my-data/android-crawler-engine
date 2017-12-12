# App-Crawler-Engine
An Android app crawling framework, making automatic fetching contents from mobile screen super easy!

The purpose was crawling highly encrypted data from mobile apps.

## Working plan

1. Using Xposed framework to write a crawler for fetching content from WeChat Tiny Programs. (This might come with `adb shell` command, however, `adb shell` cannot dump WebView, and that's why I need Xposed framework.)
2. Extract the crawler as a framework and modify the previous work as an example.
3. Using root without Xposed.
4. Using legitimate Android permissions without root.
5. Future plans on supporting other mobile OSs ...
