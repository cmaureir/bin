bin
===

Small scripts that currently I have in my ~/bin directory

 * `brightness`: Check brightness on */sys/class/backlight/intel_backlight*,
    manipulating the values using `+` and `-` options.
 * `check_repos`: Uses a simple `git status` check to see which repositories need
    to be updated. Since is based in the `find` command, you can specify the
    *maxdepth* option using the first argument, to reach a deeper level.
    e.g. `check_repos 2`
 * `cl-clock`: Get time in America/Santiago, Chile.
 * `clone`: Simple script to clone my repositories using only `clone <reponame>`.
 * `connect_wep`: Connect to WEP network.
 * `fixhwtime`: Fix the problem when the *hwclock* has a wrong time.
 * `indent_cpp`: Uses the `indent` command to improve indentation of any files
    using a determinated extension. e.g. `indent_cpp c` (will indent all C files)
 * `makevideo`: Make videos using *ffmpeg* from many PNG images.
 * `ping_quad`: Ping flood to a range of hosts inside the AEI network.
 * `psapdf`: PS to PDF script using EPS as middle point.
 * `signal`: Launch *signal* from chrome-apps.
 * `trackpad-toggle.sh`: Power off the touchpad of my thinkpad.
 * `volume`: Control volume via command line using `pamixer`. Options are *+*, *-*
    and *m*, for increase, decrease and mute, respectively.
 * `wificonnectsimple`: Connect to Wireless network using `nmcli` command.
    e.g. `wificonnectsimple <network name> <password>`
