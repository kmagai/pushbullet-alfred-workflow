Pushbullet Alfred Workflow
==========================

An Alfred workflow to use with the [Pushbullet](https://www.pushbullet.com) service.

## Configuration

For the Workflow to work, you have to add your own API-Key and the ID of your device. Double click the /bin/bash-Script and enter your things.

You can find you API-Key in your account settings here: https://www.pushbullet.com/account

and as soon as you got that, you can paste this into your Terminal to get a JSON-Response containing `iden: <your iden>`

```
curl -u <your api key here>: https://api.pushbullet.com/api/devices
```

Have fun.