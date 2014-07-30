YO iOS SDK
======

A simple YO SDK for iOS

API Sign Up
======
http://yoapi.justyo.co/

How to Start
======
Drag YO folder into your project in Xcode. Include #import "YO.h"


How to Use
======
In AppDelegate, include the following code in didFinishLaunchingWithOptions:

    // Put your APIKey
    NSString *APIKey = @"20af1dd2-93af-869f-446c-0675f8694095";
    [YO startWithAPIKey:APIKey];


In your code:

    // Send A Yo To All Subscribers
    [YO sendYO];
    
    // Yo Individual Usernames
    [YO sendYOToIndividualUser:@"YIQIN1"];
    
    // Count Total Subscribers
    [YO countTotalSubscribers];


How to Contribute
======
1. Fork it.
2. Create your feature branch (git checkout -b new-feature).
3. Commit your changes (git commit -am 'Added new-feature').
4. Push to the branch (git push origin new-feature).
5. Create new Pull Request.
