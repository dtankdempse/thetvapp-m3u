## What is TheTVApp?

TheTVApp is a platform that offers free live TV and sports streaming across selected categories. Users can stream and watch live TV directly through their browser without the need for an account or subscription.

For added flexibility, this repository provides a way to create an M3U Playlist of TheTVApp's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.

You can view the full list of channels provided by TheTVApp [here](http://href.li/https://thetvapp.to/).

## Direct M3U Playlist URL

Due to ongoing abuse, the previous setup allowing you to easily load the Bit.ly URL into your application has been temporarily removed. However, I’m actively working on a solution to bring this feature back and will provide updates in the coming days. In the meantime, if you're able to use one of the options below, you can continue accessing TheTVApp's M3U Playlist.

---

## Windows Users

Download and extract the zip file below. Once the files are extracted, run the setup_service.bat file to begin installing the TheTVApp-M3U playlist on your computer. After the installation is complete, you can access the local server to locate both the playlist and EPG URLs. These URLs can then be used to load the playlist into your application, such as Firestick, Android, or other devices.

[![Download ZIP](https://img.shields.io/badge/Download-ZIP-brightgreen)](https://github.com/dtankdempse/thetvapp-m3u/raw/refs/heads/main/win/thetvapp-m3u.zip)

---

## Docker Users

TheTVApp-M3U Playlit is also available as a Docker image, allowing you to easily deploy it in a containerized environment.

### Pulling the Docker Image

To get started, pull the latest version of the Docker image with the following command:

`docker pull dtankdemp/thetvapp-m3u:latest`

### Running TheTVApp-M3U Container

Once you’ve pulled the image, you can start the container using:

`docker run -d -p <port>:4124 dtankdemp/thetvapp-m3u:latest`

This command runs thetvapp-m3u on port 4124, allowing your IPTV application to connect to it locally or remotely (depending on your setup).

The playlist and EPG details will be available at either:

---

### Accessing the Server

To access the server, use one of the following URLs:

- **Local Access:** `http://localhost:4124`
- **Network Access:** `http://IP_ADDRESS:4124`

If you plan to use the playlist on other devices within your network, make sure to use your computer's actual IP address instead of `localhost`. To locate your computer's IP address, refer to these video guides for [Windows](https://www.youtube.com/watch?v=_FHuWzC8BKE) or [Linux](https://www.youtube.com/watch?v=gaIYP4TZfHI).

#### Playlist and EPG URLs

- **M3U Playlist:** `http://IP_ADDRESS:4124/playlist`
- **EPG Guide:** `http://IP_ADDRESS:4124/epg`

---

## Disclaimer:

This repository has no control over the streams, links, or the legality of the content provided by thetvapp.to. It is the end user's responsibility to ensure the legal use of these streams, and we strongly recommend verifying that the content complies with the laws and regulations of your country before use.

