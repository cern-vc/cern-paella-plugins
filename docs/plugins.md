## Details about the plugins

### ch.cern.paella.liveStreamIndicatorPlugin

This plugin adds an indicator to the player to show if the video is a live stream or not.

### ch.cern.paella.liveStreamingProgressIndicator

This plugin adds an indicator to the player to show the progress of the video when it is a live stream.

```json
"ch.cern.paella.liveStreamingProgressIndicator": {
    "enabled": true,
    "layer": "foreground",
    "side": "left",
    "margin": 10,
    "textColor": "#AA0000",
    "circleColor": "#FF0000"
}
```

### ch.cern.paella.matomoAnalyticsPlugin

This plugin adds the Matomo Analytics to the player.

```json
"ch.cern.paella.matomoAnalyticsPlugin": {
  "enabled": false,
  "trackingId": "126",
  "domain": "https://weblecture-player.web.cern.ch",
  "category": true,
  "context": [
      "matomoUserTracking"
  ]
},
```

### ch.cern.paella.matomoAnalyticsUserTrackingPlugin

This plugin adds the Matomo Analytics User Tracking to the player.

```json
"ch.cern.paella.matomoAnalyticsUserTrackingPlugin": {
    "enabled": true
},
```

### ch.cern.paella.nextTimeButtonPlugin

This plugin adds a button to the player to go to the next time in the list. The list of times is given in the url with the parameter `time`. The format of the parameter is `&time=3m,4m,5m`.

```json
"ch.cern.paella.nextTimeButtonPlugin": {
    "enabled": true,
    "side": "right",
    "order": 2
},
```

### ch.cern.paella.prevTimeButtonPlugin

This plugin adds a button to the player to go to the previous time in the list. The list of times is given in the url with the parameter `time`. The format of the parameter is `&time=3m,4m,5m`.

```json
"ch.cern.paella.prevTimeButtonPlugin": {
    "enabled": true,
    "side": "right",
    "order": 1
},
```

### ch.cern.paella.vttManifestCaptionsPlugin

This plugin adds the captions from the VTT Manifest to the player.

```json
"ch.cern.paella.vttManifestCaptionsPlugin": {
    "enabled": false,
    "downloadOptions": {
        "xhrFields": {
            "withCredentials": true
        }
    },
    "crossDomain": true
},
```
