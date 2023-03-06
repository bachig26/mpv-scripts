# mpv-scripts
This repository contains the scripts / config / keybindings that is customized to my personal interest.

If anyone interested in using the scripts, you can download or clone and extract it to the mpv config dir (`~/.config/mpv/`) or if you're using the mpv installed via scoop (example: `C:\Users\USER\scoop\apps\mpv\current\portable_config`).

_Note: This script is last tested on mpv v0.35.1 installed via scoop on a Windows 10. There might be some changes needed to the scripts in case if need to use these on Linux._

The original repository from which I modified the scripts are hyperlinked below.

### [mpv-config](https://github.com/hl2guide/better-mpv-config)
The `mpv-conf` and `input.conf` included here are configured a lot and maybe have different keybinds in comparison to the default/stock mpv.

### [uosc](https://github.com/tomasklaen/uosc)
Feature-rich minimalist proximity-based UI for MPV player. An alternative to the mpv's stock osc.

### [thumbfast](https://github.com/po5/thumbfast)
An High-performance on-the-fly thumbnailer for mpv, this script might interests many who need the . This script does not display thumbnails on its own, thus needing an OSC UI scripts like uosc, ModernX or others. You can find some of the UI Scripts that supports in the [thumbfast UI Script](https://github.com/po5/thumbfast#ui-support) section.

### [pause-indicator](https://github.com/zenwarr/mpv-config)
This script introduces a small, less-obtrusive pause/buffer indicator alternative to the default indicator. _Note: This script doesn't replace the indicator in some or all UI Scripts like uosc._

### [clock](https://github.com/zenwarr/mpv-config)
clock script shows the system clock and video end time. The placement of the clock, size can adjusted in `~/scripts/clock.lua`; The Date and Time function can be adjusted by changing the numeric values, refer the numeric table in format table here: https://www.lua.org/pil/22.1.html. The script can enabled/disabled by default in `~/script-opts/clock.conf` by changing values `enabled_by_default=`.

### [boss](https://github.com/zenwarr/mpv-config)
boss script pauses and minimizes the player by a keybind.

### [SmartCopyPaste_II](https://github.com/Eisa01/mpv-scripts)
SmartCopyPaste II helps to copy/paste the video, image or any files from the sytem into the mpv and also logs them in the clipboard. The keybinds can be configured in `~/script-opts/SmartCopyPaste_II.conf`.

### [SimpleHistory](https://github.com/Eisa01/mpv-scripts)
SimpleHistory helps to remember the history of the files played on the mpv. It also helps in resuming at last played location. The keybinds can be configured in `~/script-opts/SimpleHistory.conf`.

### [SimpleBookmark](https://github.com/Eisa01/mpv-scripts)
This is similar to the SimpleHistory script but helps when you want to bookmark/favorite the files along with the last played time. The keybinds can be configured in `~/script-opts/SimpleBookmark.conf`.

### [UndoRedo](https://github.com/Eisa01/mpv-scripts)
It works as simple Undo/Redo but with the video seeking, remembers the last location and can be used to undo or redo them in case of an accidental seek.

### [quality-menu](https://github.com/christoph-heinrich/mpv-quality-menu)
This allows you to change the streamed video and audio quality (ytdl-format) on the fly.

### [guess-media-title](https://github.com/zenwarr/mpv-config)
This allows you to display the filename as video title by using the guessit python library.
Requirement: [guessit](https://github.com/guessit-io/guessit)
