Firmware V1.2

-Bug-fix: ESC calibration.

There where two uninitialized variables when entering ESC calibration. (flagMutePwm and ServoFilter) Of course this was the one function I forgot to test in V1.1. Sorry about that.

Note that ESC calibration is a bit simpler now. You can plug in the battery and then press the buttons, since the welcome screen adds a bit delay. No need for 4 hands

Also note that the ESC calibration amplifies the throttle signal a bit to make sure the ESC receive the full range of 1 to 2 ms. (in all versions)
This why it it is best to do the ESC calibration though the KK2. 