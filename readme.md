Wake lock API has been released (https://github.com/WebKit/WebKit/tree/main/Source/WebCore/Modules/screen-wake-lock) on iOS 16.4


I use NoSleep.js to handle Wake Lock API. NoSleep.js is correctly handled with iOS 16.4.


Here the issue, on iOS 16.4.
- When using the Wake Lock API, on Safari, in a browser mode, the Wake Lock API work properly. 
- On the same website, opened after have done "Add to home screen", the Wake Lock API don't work properly. The Wake Lock API seem to not be able to be acquired.

Here the test page:
https://pelord.github.io/wakeLockApiAddHomeScreen/


To test the Wake Lock API, you have to toggle the ZZZ button.

- Unchecked ZZZ = Wake Lock API released
- Checked ZZZ = Wake Lock API acquired
