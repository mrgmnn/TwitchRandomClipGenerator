# TwitchRandomClipGenerator
Twitch Random Clip Generator


A simple random Twitch clip player with zero limitations.
Setup

You are required to create a Twitch developer application in order for this to function. If you have already created one and have the Client ID and Client Secret, skip to Step 8.

    Visit https://dev.twitch.tv/ and Login.
    Press "Your Console" in the top right.
    Under "Applications" press "Register Your Application"
    Give it any name, it doesn't matter. Select the most appropriate category, or just "Other."
    As an "OAuth redirect URL" is required, enter a link to any website - preferably one you own, or just enter a link to google (https://google.com/). The app doesn't use this so it's not important.
    Press "Create"
    Once created, press "Manage" and scroll to the bottom of the page. Take note of the "Client ID" and "Client Secret" (press new secret if there isn't one there)
    Now, download the viewer.html file from here. Save this file somewhere accessible.
    Open the viewer.html file in a text editor of your choice.
    In CLIENT_ID and CLIENT_SECRET enter the Client ID and Client Secret respectively, between the quotes.
    In BROADCASTER_NAME enter your Twitch username, between the quotes.
    Adjust any of the other settings as you wish.
    Once this is complete, save and close the file.
    In OBS/other streaming software, simply add this file as a Browser Source. You may need to tick "local file" in order for this to be possible.
    In OBS, adjust the width and height of the Browser Source in the "Properties" panel rather than scaling it, this ensures that the clips play at the highest possible quality without becoming blurry when scaled.
    Optionally, you may also want to consider enabling "Shutdown source when not visible" and "Refresh browser when scene becomes active" for the most flexibility.
