**better-pgrep:**
Short Bash script/function (to be appended to _.bashrc_ Linux system file, remember about entering _exec bash_ into console/terminal emulator) to extend & even fix the pgrep Linux system command
Handy bash function that can pass additional option to the ps xarged command, and fixes a certain pgrep &amp; bash interop.

The function **wraps ** the in-system command. Takes string and optionally one extra argument to pass to the script-called standard _ps_ command, after another standard system _pgrep_ is invoked by script.
If no process match can be found, colored message is written. For me this is clear advantage above the Linux command „/usr/bin/pgrep” used in alone manner.
