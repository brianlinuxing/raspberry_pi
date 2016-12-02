# raspberry_pi
Repo for Raspberry Pi script, etc

Need to set up the wireless on a Raspberry Pi or Banana Pi via the command line?

These network files will allow the use of WPA2 encoding on your wireless set-up

So copy over the files after making suitable backups.

Change the wpa_supplicant.conf to match your wireless setup.

Run wpa_passphrase <SSID> <password> to generate the hash code, copy it into the wpa_supplicant.conf replacing my example.

These have been tested on standard Raspbian and Bananian Jesse 8 lite.
