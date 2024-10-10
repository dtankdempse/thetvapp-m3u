**Note:** Due to recent changes on TheTVApp's website, events are currently not being added to the playlist. We are actively looking into the issue.

## What is TheTVApp?

TheTVApp is a platform that offers free live TV and sports streaming across selected categories. Users can stream and watch live TV directly through their browser without the need for an account or subscription.

For added flexibility, this repository provides an M3U playlist featuring TheTVApp's channels. With this, you can load the streams into any IPTV application that supports M3U-formatted playlists.

You can view the full list of channels provided by TheTVApp [here](http://href.li/https://thetvapp.to/).

## How to Use the M3U Playlist

To use M3U playlist in your IPTV application, look for the option to import an M3U playlist within the app's settings. Once you find the import option, simply copy and paste the Playlist URL and EPG URL listed below into the respective fields.

### Playlist URL:
``https://bit.ly/tta-m3u``

### EPG URL:
``https://bit.ly/tta-epg``

## Playlist & EPG Refresh

Since the playlist is dynamically generated, we recommend setting your application to reimport the playlist every 8 hours to ensure it remains up-to-date. If you encounter a 403 error, it indicates that your playlist has expired and needs to be refreshed. Both the playlist and EPG data are updated twice daily, so it's best to sync your playlist and guide information at the same time within your IPTV application. If you see "No information" displayed in the sports section of the guide, manually refreshing the EPG should resolve the issue and load the latest data.

## Rate Limit Information

**Note**: There is a limit of 5 playlist requests per IP address within a 2-hour window.

The rate limit applies per IP address. This means that from a single location, you can request the playlist up to 5 times within 2 hours. After reaching the limit, additional requests will be blocked for the following 2 hours. However, you can easily set up 5 or more devices from your location with a refresh interval of 8 hours, and still remain comfortably within the rate limit.


## Disclaimer:

This repository has no control over the streams, links, or the legality of the content provided by thetvapp.to. It is the end user's responsibility to ensure the legal use of these streams, and we strongly recommend verifying that the content complies with the laws and regulations of your country before use.

