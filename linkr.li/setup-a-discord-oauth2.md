# Setup a Discord OAuth2

## Go to the Discord Developer Portal

* Go to [https://discord.com/developers/applications](https://discord.com/developers/applications)
* And create an Application
* Then Configure your Application
* After that navigate to the OAuth2 Tab



## Create the Redirect & get the URL

* Set your Domain or your manager URl from the Dasboard as Redirect&#x20;
* Then hit the Save Button and scroll down
* After this you Select identify and email as Scope
* Then Select the Redirect URL and Copy the link in the ENV Variable

The Discord URL looks like this

```
https://discord.com/oauth2/authorize?client_id=1294691315233329254&response_type=code&redirect_uri=https%3A%2F%2Flinks.xyzjesper.link%2Fapi%2Fdiscord&scope=identify+email
```

