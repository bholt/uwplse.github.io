# Connecting to the Wandboard

Currently the only way to connect directly to the wandboard is by using the USB serial port adapter.

 1. Plug in the adapter
 2. Run (Linux): `screen /dev/ttyUSB0 115200 8N1`
 3. Press enter to get a login prompt
 4. Login as `debian`/`debian`
 5. Run whatever.  Use `sudo` to get root.

When you're done, press `^D` to log out, and then press `^A` `k` `y` to terminate `screen`.

There is an SSH server running on the board, but it's accessible only if you're connected to the UWPLSE router.  Connect over the serial port first to add your public key to the `authorized_keys` file and to get the Wandboard's current IP address.

The `plseaudio` IRC bot runs two processes: a backgrounded `ii` (IRC client) process, and a bash script running under `tmux` to process commands.
