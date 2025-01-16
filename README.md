# Gadvia all-unlocked save data

[中文](https://github.com/UlyssesZh/gadvia-all-unlocked/blob/master/README.zh.md)

The save data of an all-unlocked
[Gadvia](https://web.archive.org/web/20250116194526/https://gadvia.wixsite.com/gadvia/en)
game account.

The game has ceased operation on 2025-01-15
([announcement](https://web.archive.org/web/20250116194112/https://gadvia.wixsite.com/gadvia/en/%E5%89%AF%E6%9C%AC-%E9%97%9C%E6%96%BC%E5%88%AA%E9%99%A4%E5%B8%B3%E8%99%9F)).
However, with these save data, one can still play all the regular charts in the game.

## Disclaimer

These save data are provided as-is, without any warranty.
Use them at your own risk.

The purpose of this repo is to make up for the players
who devoted time and money into playing this game
and to avoid losing the charts that developers spent time creating.

## Importing

Before importing the save data, you need to install the game on an Android device.

### Without root

The method only works for old Android versions (older than Android 12).

1. Follow the instructions [here](https://developer.android.com/tools/adb)
  to use adb to connect to your Android device.
2. Download the file `gadvia-all-unlocked.ab` from this repo.
3. Run the command `adb restore gadvia-all-unlocked.ab`.
4. The Android device should prompt to enter a password.
  Just leave the password empty and proceed.
5. Wait for the process to finish (takes about 1 second).

### With root

1. Launch Gadvia once and exit.
2. Use your favorite file manager or adb to put the file
  `com.hgca.uma.v2.playerprefs.xml` into the directory
  `/data/data/com.hgca.uma/shared_prefs`,
  replacing the original file.

## After importing

After importing the save data, launch the game.
You should see all the regular charts unlocked and unplayed.

The "Store" and "Adventure" sections cannot be accessed
because they require a connection to the server.
