# THIS IS A WORK-IN-PROGRESS
*I have no idea what I’m doing...*

### Custom OBD-II diagnostics device.

I’m cheap so this is getting made with the least amount of money. Most things are hacked out of random electronics I have laying around, and I’m talking shit like 15-year-old portable DVD players, not fancy-ass robot parts. Few things have come from thrift shops for dirt cheap and I bought them before I decided to do this. I’m also not any kind of engineer, electrical or mechanical, so all this has been figured out but cutting shit open and blankly staring at the insides of VCR’s and trying to become one with them. Telling you to not do what I do would be boring and lame so, go take apart the cable box in your living room. Unplugging it is suggested but, I’m not your mother so, fuck it.

#### A list of things I used. Probably incomplete.
- Portable DVD players (video-in helpful)
- Raspberry Pi 3b (I chopped off some ugly fat trash to make it fit better. I don’t even know if it still works but, we will find out later)
- OBD-II connector (impulsively bought for cheap without reading the package. It was Android bluetooth only. iPhone life so it got cut up)
- DC-DC step-down regulator from Aliexpress (I only want a single power supply for this mess; 12v for DVD player and 5v for RPi)
- Power from the wall. Temporary. (fuck going to the car to test it constantly. It’s going to use the +12v constant from pin-16 on the OBD-II port eventually)
- Datasheets (for everything you dont know what its function is, find its datasheet. Can’t find it? Probe the bitch or move on)

## Progress
*(Yeah, I actually did some shit)*

###### April 13, 2019
> The RPI can output to the LCD. Using the component video from the pi and wiring it to the video input on the DVD players board. They use different pinouts for their TRRS connections. This was fucking aggravating. Why is this shit not a standard?!
