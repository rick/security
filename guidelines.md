# Online Security

Background reading:

 - [How to stay safe online: A cybersecurity guide for political activists](https://www.revealnews.org/article/how-to-stay-safe-online-a-cybersecurity-guide-for-political-activists/)

## Guidelines

In increasing order of risk mitigation (i.e., the earlier guidelines are generally useful, later guidelines are geared towards protecting against more advanced threats, and generally require more effort and discipline to carry out):

### Disk Encryption

Encrypt your computer’s disk(s).  On Apple this is via [FileVault](https://support.apple.com/en-us/HT204837). Do it first thing when you set up your computer. Do it for any disks you add later. [Use a good passphrase](https://www.schneier.com/blog/archives/2014/03/choosing_secure_1.html) and don’t lose it (see discussion of password managers below).

### Operating System Protections

Depending upon your operating system (Windows, Mac OSX, Linux, etc.) there are various concerns that are more or less prominent. Some general guidelines:

 - Do not allow access to your system without a password.
 - Ensure that a login screen with password is present when you boot into your computer.
 - Ensure that a password must be entered to return from a locked screen (screen saver).
 - Know how to trigger your screen lock / screen saver quickly and easily.
 - Always lock your screen when you leave your computer.
 - Ensure that screen lock / screen saver starts after a short inactivity timeout.
 - [Choose a good system password](https://www.schneier.com/blog/archives/2014/03/choosing_secure_1.html), do not write it down, and do not share it with others.
 - If relevant (e.g., if you’re using Microsoft Windows), install a good malware / virus scanner and keep it updated.
 - Back up your system regularly (preferably automatically), including on-site and [off-site backups](https://en.wikipedia.org/wiki/Comparison_of_online_backup_services). Choose an off-site backup service that uses encryption that you choose the passphrase for (and which the service does not possess).

### Browser Privacy

Depending upon which browser you use the particular plugins or extensions that can help you protect your privacy may vary. Generally, you want to be able to accomplish a number of things:

 - Stop Flash programs from running automatically
 - Limit the lifetime of cookies, especially when visiting third-party sites. For example, facebook.com cookies can track you across most news sites and blogs via “share on facebook” widgets found on those sites.
 - Run ad blockers and specialized privacy protection plugins which attempt to limit information sharing and privacy-undermining code from running.

For Chrome browsers a plugin list:

 - [Adblock Plus](https://adblockplus.org/)
 - [Flashcontrol](https://chrome.google.com/webstore/detail/flashcontrol/mfidmkgnfgnkihnjeklbekckimkipmoe?hl=en)
 - [Ghostery](https://www.ghostery.com/try-us/download-browser-extension/)
 - [Privacy Badger](https://www.eff.org/privacybadger)
 - [uBlock Origin](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm?hl=en)
 - [Vanilla Cookie Manager](https://chrome.google.com/webstore/detail/vanilla-cookie-manager/gieohaicffldbmiilohhggbidhephnjj?hl=en)

### Private Browsing

This refers to browser modes which do not keep local history. “Private Browsing Session”, “Incognito Tab”, etc.

### Public Computers

Could you never use them?

If you have to use a public or shared computer be highly suspicious of some of the real risks:

 - Keystroke loggers can capture every keypress from the keyboard, including password/passphrase information, credit card/payment information, etc.
 - Malware may be running which can intercept or redirect network traffic, or read/save/modify the contents of any given webpage -- are you comfortable with the contents of every page you looked at being accessible to a third party?
 - Are you confident that the site you are accessing is really the site it purports to be? Visit SSL sites whenever possible, and check that "the lock" (or "the green bar") denoting a secured site, is present.

If you must use a shared computer there are ways to browse more securely (e.g., [run tails from a USB thumb drive](http://lifehacker.com/5916551/browse-like-bond-use-any-computer-without-leaving-a-trace-with-tails)).

### Password Management

There are a number of principles of good password hygiene:

 - Choose strong passwords (this is difficult to do without automated help)
 - Do not write down passwords
 - Do not share passwords with other people
 - Never re-use a password anywhere (this is nearly impossible to do with good passwords, not written down, and without a photographic memory or software to help)
 - Don’t give up your password to systems impersonating a system you trust

All of these principles can most easily be satisfied by using a modern password management tool. So, the overriding principle is: Use a password manager and use it well.  The two password managers most often cited are:

 - 1Password: solid tool, great UX, strong encryption, syncable, phone apps, etc.; does not run on Linux; can work with teams
 - LastPass: also solid, UX is not great, decent for automation and team use, will run on Linux

I personally recommend 1Password if you are in a position to be able to use it. It will sync via DropBox and other syncing methods, and the synced files are all encrypted. The feature set is extensive and the password generator is first-class.

When using a password manager, some tips:

 - Choose a very strong passphrase for the manager itself and do not share this passphrase with anyone.
 - Choose the strongest passphrase a site will allow, created with the password manager’s cryptographic password generator. Don’t worry about remembering the password.
 - Always choose a new password with every site. Never re-use a password.
 - Use the password manager’s “browser fill” function to find and fill the correct password for a site. If the site is an imposter (a rogue site attempting to capture your login information) the password manager can tell the difference and will not provide your credentials. Trust your password manager.
 - Some password managers will let you audit passwords based on age -- do this periodically, and change passwords every 6-12 months.
 - Some password managers will let you know when sites have had a leak or compromise of account information. Change your passwords on these sites.
 - You can store non-website account information, encrypted disk passphrases, credit card information, and “secure notes” in your password manager.

### Two-factor Authentication (2FA)

For sites and systems that allow it, enable [two-factor authentication](https://en.wikipedia.org/wiki/Multi-factor_authentication). This means that in addition to providing a username/email and a password to access a system, you will also have to provide another piece of information. This can either be generated by an authenticator application on your phone, or could be contained in an SMS (text) message sent to you.

Some guidelines:

 - Prefer authenticator applications over SMS. SMS has a number of weaknesses and has been compromised (e.g., via “lost phone” scams registering new SIM cards to phone accounts).
 - Always download 2FA “recovery codes” and store as encrypted notes in your password manager.
 - Use 2FA for all email accounts.
 - Use 2FA if it is available for google accounts, bank accounts, money service accounts (venmo, paypal, coinbase, etc.), domain registrars, etc.
 - Consider going a step further and establishing a passphrase for use with telephone calls to your bank(s) and other critical service providers. If your service provider doesn’t provide this service, consider whether it’s possible to move to a more security-minded provider.

### Communications tools

To enable secure communications with other specific individuals, there are a number of tools and services that can help. Some things to look for when choosing those tools:

 - Is the software based on [open-source software](https://en.wikipedia.org/wiki/Open-source_software) which has been audited by third parties with a good track record
 - For hosted systems, does the software provide protections from disclosure by those people running the system? ("We can't even read your message because we don't have access to your passphrase and everything is encrypted end-to-end").
 - Do groups who have strong privacy and security requirements use and recommend this software? (Dissidents, whistle-blowers, news agencies, etc.) If Snowden used it, that's a pretty good vote of confidence.

Some specific applications that might be useful:

 - [Signal](https://whispersystems.org/) - for encrypted 1:1 and group messaging / SMS; supports encrypted voice calling as well.
 - [Semaphor](https://spideroak.com/personal/semaphor) - encrypted group chat and file sharing
 - [ProtonMail](https://protonmail.com/) - encrypted email; automatically encrypts between PhotonMail users.  Can also encrypt to arbitrary email addresses using pre-shared keys (i.e., I tell you a password in advance and now I can send you encrypted emails to your hotmail address from ProtonMail).

Note that these tools are only as secure as the devices you're running them on: if your computer has malware, or your phone has been hacked, you can't trust a good encryption tool to protect your communications.


### Proxies, etc.

_coming soon: a discussion of proxies, Tor, privacy operating systems like Tails, etc._

