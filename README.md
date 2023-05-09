# LaunchScreen-Slow-show-run-application


Hi! I was suffering from the same problem.

My development environment is as follows.

Xcode 11.3.1, iPhone 7 iOS 13.3.1, MacBook Pro (2016) macOS Catalina version 10.15.3

I was able to solve it in the following way.

1. Quit Xcode.

2. Open the Mac desktop application Terminal.app.

3. Execute command "rm -rf ~/Library/Developer/Xcode".

4. Open Xcode.

5. Select the Xcode menu "Product - Scheme - Edit Scheme".

6. Check the "debug executable" in "Run - Info"

7. Then I was able to debug.

thanks.
