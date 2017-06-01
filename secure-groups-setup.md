## Secure Groups Setup

This is a checklist for setting up secure SMS communication via Signal, secure
email via ProtonMail, and secure group chat and file sharing via Semafor.
Additional guidelines on securing phones and computers are added as optional
steps inline.

### Secure SMS via Signal

 - [ ] Download Signal Private Messenger for your phone from either the Apple App Store or the Google Play Android store
 - [ ] Start the Signal app and create an account for your phone number
 - [ ] Add a friend as a Signal contact and send a secure text message
 - [ ] Make a secure Signal phone call with a friend. Be sure to verify the challenge phrase that appears on your screens. If the phrase does not match, do not continue the call.
 - [ ] Enable Signal as your SMS application (optional)

### Secure email via ProtonMail

 - [ ] Go to [ProtonMail](https://protonmail.com/) and create an email address.
 - [ ] Test ProtonMail by sending an encrypted email to a friend outside ProtonMail. Note: the "lock" button at the bottom of the message will allow you to specify the encryption password. Share the decryption password with them via Signal.
 - [ ] Test ProtonMail by sending an encrypted email to a friend using ProtonMail.
 - [ ] Notifications:
   - [ ] Either: install ProtonMail on your mobile device(s).
   - [ ] Or: set up ProtonMail settings to notify you by email.

### Secure group chat and file sharing via Semaphor

 - [ ] Download [Semaphor](https://spideroak.com/personal/semaphor) from https://spideroak.com/opendownload and install on your computer.
 - [ ] Create a Semaphor account, and use your ProtonMail email as your email address.  **Do not misplace your recovery key!** If you have a password vault such as 1Password, store it there.
 - [ ] Have an existing Semaphor user invite you to their Semaphor Team via URL. This URL should be sent through ProtonMail.
 - [ ] Connect to the existing Semaphor chat.
 - [ ] Create your own Semaphor Team.
 - [ ] Invite your same friend to your Semaphor team using Semaphor chat or ProtonMail to send the invite.
 - [ ] Upload a file to Semaphor
 - [ ] Verify that your uploaded file can be downloaded from Semaphor by you and your friend.
 - [ ] **WARNING**: Note that the free version of Semaphor expires chats and files after 30 days. Plan accordingly.

### Secure password management with 1Password (optional, but recommended)

Note: 1Password is only one of the widely used password vaults. Some other
options are [LastPass](https://www.lastpass.com/) and
[KeePass](http://keepass.info/). Using any good password vault is a huge
improvement over not using one at all.  Instructions below are for 1Password,
but adjust accordingly for other tools.

 - [ ] Download and install [1Password](https://1password.com/) from https://1password.com/downloads/
 - [ ] Create your vault with a secure passphrase. [Help for creating a strong passphrase](https://www.schneier.com/blog/archives/2014/03/choosing_secure_1.html)
 - [ ] Always use 1Password to create passwords. Generate strong, random, unique passwords for every login.
 - [ ] (optional) Sync your 1Password vault via Dropbox
 - [ ] (optional) Install 1Password on your mobile devices
 - [ ] (optional) Use Dropbox to sync between your devices.

### Secure your phone

 - [ ] Enable an unlock code or passphrase on your phone, preferably more than 4 digits.
 - [ ] Enable encryption on your phone. [iphone](https://ssd.eff.org/en/module/how-encrypt-your-iphone), [android](https://www.howtogeek.com/141953/how-to-encrypt-your-android-phone-and-why-you-might-want-to/)
 - [ ] Disable location services for photos and videos.
 - [ ] Disable location services in social media applications.
 - [ ] Enable device location and remote deactivation if available.

### Secure your computer

 - [ ] Enable a locking screen saver with a password.
 - [ ] Enable login at boot time with a password.
 - [ ] Turn on disk encryption.

### Secure your services with two-factor authentication (optional)

Two-factor authentication (2FA) provides an additional step to secure your
accounts when logging in. Preferably do not use SMS texts for authentication,
but use an authenticator app. SMS texts are becoming easier and easier for third
parties to spoof.  Note that 1Password also supports storing 2FA credentials if
an authenticator app is not handy. This makes 1Password more of a single point
of failure, but this is better than not using 2FA at all. Record your "recovery
codes" for 2FA accounts, these can be stored as "secure notes" in 1Password, or
printed and placed in your wallet, etc.

 - [ ] Enable two-factor authentication on DropBox
 - [ ] Enable two-factor authentication on your email account.
 - [ ] Enable two-factor authentication on your ProtonMail account.
 - [ ] Enable two-factor authentication on your bank accounts.
 - [ ] Enable two-factor authentication at your domain name registrar if you own any Internet domain names.
