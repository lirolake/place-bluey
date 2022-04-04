## Automatic placement

### How to get your reddit_session cookie
**NOTE: People have reported that this is annoying to do on chrome because text gets unselected. Therefore, we recommend that you use Firefox.**
People have reported that you can find it in: Dev Tools -> Application -> Cookies -> reddit_session
You could also use a cookie editor extension such as [https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm](https://chrome.google.com/webstore/detail/cookie-editor/hlkenndednhfkekhgcdicdfddnkalmdm)

1. Go to [r/place](https://reddit.com/r/place) (make sure you are logged in on the account you want to get the cookie for)
2. Open dev tools (F12 on Chrome) and go to the network tab
3. Refresh the page
4. Scroll all the way up and click on the first request to reddit.com/r/place
5. Go to the tab called `Cookies`
6. Copy the value of the `reddit_session` cookie

### Installation instructions

1. Download and Install the "LTS" version of [NodeJS](https://nodejs.org/).
2. Download the bot via [this link](https://github.com/lirolake/place-bluey/archive/refs/heads/master.zip).
3. Extract the zip file to your desktop
4. Open the folder that you just extracted, in Windows hold Shift and use right click in the folder -> Click on "open Powershell here"
5. In the Powershell window, type `npm ci`
6. Once complete, you can then type: `node bot.js SESSION_COOKIE_HERE`
Note: This window needs to stay open for it to work, do not close the Powershell window

BONUS: You can repeat these steps for any amount of accounts you'd want. Keep in mind to use different accounts.

Thanks to PlaceNL & PlaceUK for the bot we've based this on!
