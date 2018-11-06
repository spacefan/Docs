# mwptools

## What is mwptools?

With mwptools one can create and upload missions to INAV based flight controllers.

## How to use it with DroneBridge?

Future releases will have mwptools integrated into the DroneBridge image.

As for now: A Linux operating system is very much recommended.

* Connect to the DroneBridge WiFi access point \(make sure no other devices are connected at the same time\)
* Make sure to read the [documentation](https://github.com/stronnag/mwptools/tree/master/docs) `mwptools.pdf` `ubuntu-dps.txt`
* Download and install [mwptools](https://github.com/stronnag/mwptools)
* Run by typing `mwp`
* Go to Edit --&gt; Preferences
* Add `udp://192.168.2.1:1607` to `Device List`. Make sure you separate it with a comma!
* Save
* In the upper right corner select the added entry and connect
