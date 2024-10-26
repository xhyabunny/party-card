# PARTY CARD GENERATOR!

## Installation
- Git clone this repo
- Execute `npm install`
- Rename `.env.example` file to `.env` and adjust it following the next steps.

## Environment
### STREAMER ID
```
NEXT_PUBLIC_STREAMER_ID=twitch_streamer_id
```
The Id of the streamer that is hosting the party or event.

You can use [this page](https://www.streamweasels.com/tools/convert-twitch-username-to-user-id/) to find the id of an user or streamer.
### REDIRECT URI
```
NEXT_PUBLIC_REDIRECT_URI="http://localhost:3000"
```
The redirect Uri that twitch api is going to use when executing the OAuth2 link.

⚠ Make sure the Redirect Uri matches the link you put in your Twitch Developer console App.
![image](https://github.com/user-attachments/assets/20c2bfc6-8b39-4749-bdc9-c2c8411ef820)

### EVENT NAME
```
NEXT_PUBLIC_EVENT_NAME="Event name"
```
Simply the name of the event

### DEFAULT OWNER NAME
```
NEXT_PUBLIC_DEFAULT_OWNER_NAME="John Doe"
```
The default name that appears in the `Name on card` label.
![image](https://github.com/user-attachments/assets/e9636724-6722-46e8-89c2-b962f48bf424)

### DEFAULT THEME
```
NEXT_PUBLIC_DEFAULT_THEME="smythOs"
```
The default theme the card will appear with when opening the page.
Default is "smythOS"

### TWITCH API CLIENT ID
```
NEXT_PUBLIC_CLIENT_ID=your_twitch_api_client_id
```
The Twitch API Client ID on your Twitch developer console App.

### Logos & Badges
There are two types of images as of rn.
- The Main Logo (icon.png)
- The Sub badge (sub_badge.png)
The sub badge will appear only if the user is following the streamer you specified in your `.env` file
To change the card's images simply replace the images with the new ones and make sure the names of the files match the current ones.
