

# ESP32 Chess Engine

Chess coprocessor was migrated from a stand alone Arduino file to PlatformIO. The original [source code](https://www.hackster.io/Sergey_Urusov/esp32-chess-engine-c29dd9) is from Sergey Urusov. I put it here to try to improve it and fix some issues.

## Build and upload

Please install first [PlatformIO](http://platformio.org/) open source ecosystem for IoT development compatible with **Arduino** IDE and its command line tools (Windows, MacOs and Linux). Also, you may need to install [git](http://git-scm.com/) in your system. After install that you should have the command line tools of PlatformIO. Please test it with `pio --help`. 

Clone the source code:

```bash
git clone https://github.com/hpsaturn/esp32-chess-engine.git
cd esp32-chess-engine
``` 

Then please run the next commands for build and upload the firmware:

```bash
pio run --target upload
```

# Credits

Initial source code from Sergey Urusov on [HacksterIO](https://www.hackster.io/Sergey_Urusov/esp32-chess-engine-c29dd9)
