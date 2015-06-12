Cordova PhoneCall Trap
=======================

It is a Apache Cordova plugin to simplify handling phone call status and events in Android devices.


## Install

    $ cordova plugin add com.antonpaar.phonecalltrap


## Quick Example

    PhoneCallTrap.onCall(function(state) {
        console.log("CHANGE STATE: " + state);

        switch (state) {
            case "RINGING":
                console.log("Phone is ringing");
                break;
            case "OFFHOOK":
                console.log("Phone is off-hook");
                break;

            case "IDLE":
                console.log("Phone is idle");
                break;
        }
    });


## Supported platforms

- Android 2.3.3 or higher

