![Completion 1.0.0](https://img.shields.io/badge/completion%20v1.0.0-0%25-red) ![Help Wanted](https://img.shields.io/badge/%20-help--wanted-%23159818) ![Version 0.9.3](https://img.shields.io/badge/version-v0.9.7-blue) ![Sponsors](https://img.shields.io/badge/sponsors-0-red)

## qD News

## Description

qD News is a module for [qDesk](https://qDesk.org). It's accessible across qDesk, you can use it with [qD Messages](https://github.com/QuestNetwork/qd-messages-ts), [qD Social](https://github.com/QuestNetwork/qd-social-ts) and other qDesk modules. This module allows peers on the network to exchange, discuss and rate news items democratically.

Use [qOS](https://github.com/QuestNetwork/quest-os-js) in your applications and you can use the underlying channels and data in your own application by booting with [Quest News JS](https://github.com/QuestNetwork/quest-news-js).

qD News allows users to join the newsroom. It offers the ability to share news items and to discuss and collectively moderate news content. qDesk News is a module for [qDesk](https://github.com/QuestNetwork/qDesk) and it's built on [qOS](https://github.com/QuestNetwork/quest-os-js) which makes use of the [Interplanetary Filesystem](https://ipfs.io), [IPFS GossipSub](https://blog.ipfs.io/2020-05-20-gossipsub-v1.1/) and [qDesk](https://github.com/QuestNetwork/qDesk), our example app based on [Angular10](https://angular.io/).

We have chosen Angular/Electron as an example environment because we believe it offers the best accessibility for developers coming from any other language/framework. The Quest Network is already being used in Python on PyQt5 and we aim to provide the underlying library in Go and wherever possible in Rust as well.

[qDesk](https://github.com/QuestNetwork/qDesk) works in the browser, as an Electron on Windows, Mac and Linux and Android using Cordova.

Check out other [Awesome Quest Network dApps](https://github.com/QuestNetwork/awesome/blob/master/README.md)!

## Security

![Completion 1.0.0](https://img.shields.io/badge/OAEP-4096%20Bit-green) ![EC](https://img.shields.io/badge/EC-P&#8208;521-green) ![AES](https://img.shields.io/badge/AES-256%20Bit-yellow)

[qOS](https://github.com/QuestNetwork/quest-os-js) uses [4096 Bit RSA-OAEP](https://en.wikipedia.org/wiki/RSA_(cryptosystem)#Operation) encryption, [256 Bit AES-CBC](https://en.wikipedia.org/wiki/Advanced_Encryption_Standard) encryption and [NIST P-521 EC](https://en.wikipedia.org/wiki/Elliptic-curve_cryptography#Fast_reduction_(NIST_curves)) signatures.

## Lead Maintainer

[StationedInTheField](https://github.com/StationedInTheField)

## Support Us
Please consider supporting us, so that we can build a non-profit for this project (ツ)

| Ethereum| Bitcoin |
|---|---|
| `0xBC2A050E7B87610Bc29657e7e7901DdBA6f2D34E` | `bc1qujrqa3s34r5h0exgmmcuf8ejhyydm8wwja4fmq`   |
|  <img src="https://github.com/QuestNetwork/qDesk/raw/master/doc/images/eth-qr.png" >   | <img src="https://github.com/QuestNetwork/qDesk/raw/master/doc/images/btc-qr.png" > |

## Development

qDesk News is a module of [qDesk](https://github.com/QuestNetwork/qDesk), so please see https://github.com/QuestNetwork/qDesk#development for instructions.

### Commands

**Prepare Package**

``npm run inst`` Removes `package-lock.json` and runs ``npm install``

We added an example ```swarm.json``` to the ```src/app``` folder with an example node to make reproduction easier, but we strongly recommend to use our [Quest CLI](https://github.com/QuestNetwork/quest-cli) to test and build the app.

Pro Tip: Put a file in your `/bin` that runs the quest-cli like so `node /path/to/quest-cli/index.js` from any folder on your system. It's much nicer!

## Roadmap

**0.9.7**
- Basic functionality

## License
GNU Affero GPLv3
