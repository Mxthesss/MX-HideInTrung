# MX-HideInTrung

Hide In Trunk is a FiveM resource that allows players to hide themselves in the trunk of a vehicle using OX_Lib notifications.

## Installation

1. Download the Hide In Trunk resource from this repository.
2. Copy the `MX-HideInTrung` folder into your FiveM server's `resources` directory.
3. Add `start MX-HideInTrung` to your server.cfg file.
4. Start or restart your FiveM server.

## Usage

To use Hide In Trunk in-game, follow these steps:

1. Approach a vehicle with a trunk (boot).
2. Stand close to the trunk and press a specified key (by default, the key is `E`) to hide yourself in the trunk.
3. You will receive a notification using OX_Lib for a successful hiding in the trunk.
4. To exit the trunk, press the same key (by default, the key is `E`) again.
5. You will receive a notification using OX_Lib for a successful exit from the trunk.

## Configuration

The configuration of Hide In Trunk can be done in the `mx_config.lua` file located in the `MX-HideInTrung` resource folder. You can customize the distance to the trunk, the key to trigger hiding in the trunk, and the OX_Lib notifications.

## Requirements

- FiveM server with access to run server-side resources.
- OX_Lib (https://github.com/Owen-M/OX_Lib) for displaying notifications.

## Credits

Hide In Trunk was created by [Mxthess]. 

## License

Hide In Trunk is open-source software released under the [MIT License](LICENSE).
