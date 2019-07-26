# soundcast-VAST-documentation
Soundcast VAST integration

This guide covers the latest version of the SoundCast VAST Integration. It uses VAST 2.0, and helps to integrate with the SoundCast platform.

## VAST query

The query should look like this :
```
http://delivery.api.soundcast.fm/soundcastid/$SOUNDCASTID?format=VAST&ip=$IP&ua=$USER_AGENT&cookieId=$COOKIE
```

### Parameters

* $SOUNDCASTID : Is the tag id, it will be provided by us
* $IP : IP (Optional)
* $USER_AGENT : User Agent (Optional)
* $COOKIE : Listener cookie (Optional)

### Sample query

```
https://delivery-stg.api.soundcast.fm/soundcastid/5bfc551a4cb2e?format=VAST?ip=92.154.10.41&ua=Postman&cookieId=listenerId
```

## Any Question

Please contact our support team.
