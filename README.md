![PhotoVault Banner](https://i.imgur.com/kNdO8jx.png)
# PhotoVault-Server
## Overview
Server code for PhotoVault, a FLOSS alternative to SnapChat which uses PGP for encryption.
## Philosophy
When dealing with potentially personal information, user privacy is of the utmost importance. With proprietary messaging systems, it's impossible to know how your data is being used. By using completely open server and app technology, one can be certain that their data isn't being used commercially or for unethical purposes. In addition, it allows users to be confident that their data is being treated securely using up to date encryption methods that prevent even the server from reading the contents of messages.
## Core Server functionality
* Handle registration of users
* Store usernames and corresponding public keys in database
* Handle messages
 * Send client public key for receiving user
 * Receive encrypted image from client
 * Send encrypted image to receiving user

## TODO
Basically everything
## Disclaimer
This is my first time doing Android App Development. There will certainly be things which are done in a sub-par way. I am 100% open to suggestions - either open an issue or a a PR if you feel like fixing it yourself and I'll be more than happy to take advice.
