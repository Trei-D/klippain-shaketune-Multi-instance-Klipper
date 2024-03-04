# Klippain Shake&Tune Module

This Klippain "Shake&Tune" repository is a standalone module from the [Klippain](https://github.com/Frix-x/klippain) ecosystem, designed to automate and calibrate the input shaper system on your Klipper 3D printer with a streamlined workflow and insightful vizualisations.

![logo banner](./docs/banner.png)

I have moddified the installation script so it can be installed on a multiple klippers instances.

What you have to do is to update the install.sh script with your desired printer path:
     ```bash
USER_CONFIG_PATH="${HOME}/E3Pro_data/config"
MOONRAKER_CONFIG="${HOME}/E3Pro_data/config/moonraker.conf"
KLIPPER_PATH="${HOME}/klipper"

K_SHAKETUNE_PATH="${HOME}/E3Pro_data/klippain_shaketune"
K_SHAKETUNE_VENV_PATH="${HOME}/E3Pro_data/klippain_shaketune-env"
    ```

