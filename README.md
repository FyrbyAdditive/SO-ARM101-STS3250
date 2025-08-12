<img src="https://raw.githubusercontent.com/FyrbyAdditive/SO-ARM101-STS3250/refs/heads/main/Media/SO-ARM101-ST3250%20-%20Right%20Side.png" width="400" /><img src="https://github.com/FyrbyAdditive/SO-ARM101-STS3250/blob/main/Media/SO-ARM101-ST3250%20-%20Extended%20Horizontally.png?raw=true" width="400" />

This is an updated follower arm for the [SO-ARM101 by TheRobotStudio](https://github.com/TheRobotStudio/SO-ARM100) used by [Huggingface Lerobot](https://huggingface.co/docs/lerobot/index), to fit STS 3250 servos from Feetech. All the parts needed minor changes to fit these servos better. I made this as I wanted more torque, and also the 3250s have nicer metal cases with proper mounting points.

This robot can be used for training AI models, teleoperation, and also recording and playing back actions.

There are some other minor changes but it is functionally the same. Various options, and some files for 3D printing are also provided.

The main model is on the first plate of the separate prepared files, for the Prusa XL and Bambu H2D - if you select another printer in Bambu studio it will should. The options are on the second plate. The options include:

- TPU lined jaws. Note this has M3 heat set insert holes for the camera mount.
- Mount for the Waveshare Bus Servo Driver HAT (A), a different controller board that works
- A larger base which is easier to clamp, with TPU parts

To build this arm you need:

- A supported Waveshare controller board, either the Waveshare "Bus Servo Driver HAT (A)" or "Bus Servo Adapter (A)"
- Six Feetech ST 3250 servos. I got mine from Alibaba
- A 12V power supply
- 3D printer and some filament

The only screws needed are included with the servos. Obviously you will need a SO-101 leader arm also, which you can build from the [TheRobotStudio SO-100 ARM page](https://github.com/TheRobotStudio/SO-ARM100).

If printing the options with TPU parts, you must use PETG as the main plastic so they stick.
