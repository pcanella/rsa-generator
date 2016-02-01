# rsa-generator
AppleScript that auto-runs your RSA token and copies it for you! Saving you tons of time not having to type out your RSA PIN.

Original AppleScript and instructions [here](http://marcovaltas.com/2012/10/09/scripting-token-retrieval-on-osx.html). 

#Instructions:

### TL;DR Add a key named "rsatoken" to your Keychain with your pin as password.

* Go to "Keychain Access" Application
* Go to top left and click the lock (enter user/pass to unlock these settings)
* Click on "Passwords" under the "Category" bar
* Go to the bottom panel and click the big "+" to add a new password
* Keychain Item Name and Account Name should both be `rsatoken`
* Password field is your PIN for RSA Token generation (what you initially type in to SecurID)

Download the .app (application file for mac)
https://www.dropbox.com/s/wq5gomjtx6jl5sc/rsa-generator.app.zip?dl=0
