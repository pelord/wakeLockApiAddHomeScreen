Refer to https://bugs.webkit.org/show_bug.cgi?id=205104

on iOS 16.4 

When using the new feature Wake Lock API, on Safari, in a browser mode, this app work properly.
To test the Wake Lock API, you have to toggle the ZZZ button. 

Unchecked ZZZ = Wake Lock API released

Checked ZZZ   = Wake Lock API acquired

Now the issue, on Safari, when you do "Add to home screen", the Wake Lock API is not able to be acquired.

there the test page:

https://pelord.github.io/wakeLockApiAddHomeScreen/
