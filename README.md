# Tumblr Activity Box Gradients
A recent tumblr update removed the highlighting around mutuals in the activity box/page, and replaced it with highlighting around "unread" activity, as well as colored labels next to mutuals and blogs you follow (but who don't follow you back).

This script replaces the text labels with colored transparent-to-opaque background gradients. At the top of the script are several variables to easily control whether the "Following" gradient shows up (default off), whether to hide the tags in addition to adding the gradient (default on), the loading delay to allow the activity box to open (default 1 sec), and two strings to control the gradient color (default dark mode label bg color).

## Installation
If you have a userscript browser addon/extension like Greasemonkey, clicking [this link](https://raw.githubusercontent.com/dzamie/tumblr-activity-gradient/main/user.js.user.js) should install it automatically. If not, simply save user.js and import it using the addon/extension.

Please note that, while it will work on the tumblr.com/activity page elements, the script only runs when the activity box appears or disappears.
