# Sonarr-Transmission Torrent Download Readme

## How to use
* Accessing Sonarr Web-UI:
```
    192.168.0.36:8989
```
* Accessing Transmission Web-UI:
```
    192.168.0.37:9091
```
* Files Download location:
```
    /vagrant/Downloads
```
* Sonarr Library location (you need to specify this directory when adding a new series):
```
    /vagrant/TVShows
```
## Limitations to be fixed
* Sonarr does not remove the torrent from the history of transmission, even though Remove Completed Download Handling is enabled
* File does not get deleted from transmission download location, after being copied over by Sonarr. Probably transmission needs to automatically remove the torrent file, so that Sonarr can move the video instead of copying it.
