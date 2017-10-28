# ChaiLove: Floppy Bird

[Flappy Bird](https://en.wikipedia.org/wiki/Flappy_Bird) re-implementation using [ChaiLove](https://github.com/RobLoach/ChaiLove).

![Floppy Bird Screenshot](screenshot.png)

## Play

1. Run [RetroArch](http://retroarch.com/)

2. Install the [ChaiLove](https://github.com/robloach/chailove) core through RetroArch's Online Updater → Core Updater → ChaiLove

3. Download the latest [ChaiLove Floppy Bird release](https://github.com/RobLoach/ChaiLove-FloppyBird/releases) at Online Updater → Content Downloader → ChaiLove → Floppy Bird

4. Load the `.chailove` or `main.chai` file through Load Content

### Command Line

Alternatively, it is possible to run it through the command line:

    retroarch -L chailove_libretro.so FloppyBird.chailove

## Development

    retroarch -L chailove_libretro.so main.chai
