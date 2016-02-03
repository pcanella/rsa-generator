# rsa-generator
AppleScript that auto-runs your RSA token and copies it for you! Saving you tons of time not having to type out your RSA PIN.

* [Original AppleScript and instructions](http://marcovaltas.com/2012/10/09/scripting-token-retrieval-on-osx.html). 

* Have issues with your RSA token? [Check out the RSA Self Service site](https://tokenaccess.corp.ebay.com/)!

#Latest Updates
* Added Notification when copy is successful
* Closes SecurID Application when completed


#Instructions:

### TL;DR Add a key named "rsatoken" to your Keychain under "login" category with your pin as password.

* Go to "Keychain Access" Application
* Go to top left and click the lock (enter user/pass to unlock these settings)
* Click on "Passwords" under the "Category" bar (NOTE: Make sure you're under the "login" selection under "Keychains" on the top left)
* Go to the bottom panel and click the big "+" to add a new password
* Keychain Item Name and Account Name should both be `rsatoken`
* Password field is your PIN for RSA Token generation (what you initially type in to SecurID)

[Download](http://bit.ly/autorsa) (.zip)

