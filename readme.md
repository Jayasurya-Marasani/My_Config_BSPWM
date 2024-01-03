# My_Config_BSPWM

## Overview
Welcome to `My_Config_BSPWM`! This repository contains my personal configuration files for BSPWM (Binary Space Partitioning Window Manager). These configurations are tailored to my workflow but feel free to use them as a starting point for your own BSPWM setup.

## Features
- Custom keybindings for efficient window management
- Aesthetic and minimalistic status bar configuration
- Startup script for setting up the environment
- Multi-monitor support with dynamic workspace allocation

## Installation
To use these configurations, first ensure that BSPWM and SXHKD are installed on your system.

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/My_Config_BSPWM.git

2. **Copy Configurations:**
    ```cp -r My_Config_BSPWM/* ~/.config/

## Restart BSPWM
After making changes to the configurations, you can apply them by either:
- Restarting BSPWM: `bspc wm -r`
- Logging out and back in to your session.

## Customization
Feel free to modify the keybindings and other settings in the `bspwmrc` and `sxhkdrc` files to suit your needs. These files are located in `~/.config/bspwm/` and `~/.config/sxhkd/` respectively.

## Contribution
Contributions are welcome! If you have improvements or suggestions, please open an issue or submit a pull request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
- Thanks to the BSPWM community for the amazing window manager.
- Inspired by various configurations found on [r/unixporn](https://www.reddit.com/r/unixporn/).
