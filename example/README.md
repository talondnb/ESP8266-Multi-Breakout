***Alarm Panel***

This example uses the LM339 comparator to read the voltages of alarm sensors/PIR connected to an existing alarm panel and convert them to binary to be detectable by a smart home instance as a binary sensor. Refer to [here](https://www.instructables.com/id/Alarm-PIR-Movement-to-Home-Automation/).

I have also used both relay outputs on the board, wired into a wireless keyfob which can arm/disarm the alarm panel through existing RF integration.


***Garage Opener***

This example is uses a single relay output, wired directly to a garage door opener to trigger open/close. A cheap, wired [reed switch](https://www.aliexpress.com/item/Hot-Sale-1-Set-High-Sensitive-White-0-5A-100V-10W-ABS-1-Set-Door-Window/32672580621.html) is wired to D4 and GND to enable state detection of the garage door. The HC-SR04 ultrasonic sensor is also utilised as vehicle presence detection and the device is mounted above the vehicle parking area.
