Peatio : The open-source crypto currency exchange [Under Development For Version 2.0]
=====================================
![Bitcoin](https://appspicket.com/wp-content/uploads/2017/07/coins-2.png)

Peatio is a free and open-source crypto currency exchange implementation with the Rails framework and other cutting-edge technology.


### Mission

Our mission is to build the world best open-source crypto currency exchange with a high performance trading engine and safety which can be trusted and enjoyed by users.Help is greatly appreciated, feel free to submit pull-requests or open issues.


### Things You Should Know ###

RUNNING AN EXCHANGE IS HARD.

Peatio makes it easier, but running an exchange is still harder than a blog, which you can download the source code and following the guide or even a cool installer and boom!!! a fancy site is there to profit. We always prioritize security and speed higher than 1-click setup. We split Peatio to many components (processes) so it's flexible to deploy and scalable.

SECURITY KNOWLEDGE IS A REQUIREMENT.

* Rails knowledge
* Security knowledge
* System administration


### Features

* Designed as high performance crypto currency exchange.
* Built-in high performance matching-engine.
* Built-in [Proof of Solvency](https://iwilcox.me.uk/2014/proving-bitcoin-reserves) Audit.
* Built-in ticket system for customer support.
* Usability and scalibility.
* Websocket API and high frequency trading support.
* Support multiple digital currencies (eg. Bitcoin, Litecoin, Dogecoin etc.).
* Easy customization of payment processing for both fiat and digital currencies.
* SMS and Google Two-Factor authenticaton.
* [KYC Verification](http://en.wikipedia.org/wiki/Know_your_customer).
* Powerful admin dashboard and management tools.
* Highly configurable and extendable.
* Industry standard security out of box.
* Active community behind.
* Free and open-source.
* Created and maintained by [Peatio open-source group](http://peat.io).


### Known Exchanges using Peatio

* [Yunbi Exchange](https://yunbi.com) - A crypto-currency exchange funded by BitFundPE
* [One World Coin](https://oneworldcoin.com)
* [Bitspark](https://bitspark.io) - Bitcoin Exchange in Hong Kong
* [MarsX.io](https://acx.io) - Australian Cryptocurrency Exchange

### Mobile Apps ###

* [Boilr](https://github.com/andrefbsantos/boilr) - Cryptocurrency and bullion price alarms for Android

### Requirements

* Linux / Mac OSX
* Ruby 2.2.2
* Rails 4.0+
* Git 1.7.10+
* Redis 2.0+
* MySQL
* RabbitMQ

** More details are in the [doc](doc).


### Getting Quick start using Installer

  * Use peatio-fresh-installer.sh file to install on fresh server

  * Use peatio-repair-installer.sh file to repair/delete/old and then install

  * Use peatio-installer-vagrant.sh file to install via vagrant (Linux + Windows + MacOX)

  * To install manually please follow the docs

### Getting Manual start

* [Setup on Mac OS X](https://github.com/algobasket/PeatioCryptoExchange/blob/rebuild-peatio/doc/setup-local-osx.md)
* [Setup on Ubuntu](https://github.com/algobasket/PeatioCryptoExchange/blob/rebuild-peatio/doc/setup-local-ubuntu.md)
* [Deploy production server](https://github.com/algobasket/PeatioCryptoExchange/blob/rebuild-peatio/doc/deploy-production-server.md)
* [Setup Ethereum Server](https://github.com/algobasket/PeatioCryptoExchange/blob/rebuild-peatio/doc/eth.md)

### API

You can interact with Peatio through API:

* [API v2](http://demo.peat.io/documents/api_v2?lang=en)
* [Websocket API](http://demo.peat.io/documents/websocket_api)

Here're some API clients and/or wrappers:

* [peatio-client-ruby](https://github.com/peatio/peatio-client-ruby) is the official ruby client of both HTTP/Websocket API.
* [peatio-client-python by JohnnyZhao](https://github.com/JohnnyZhao/peatio-client-python) is a python client written by JohnnyZhao.
* [peatio-client-python by czheo](https://github.com/JohnnyZhao/peatio-client-python) is a python wrapper similar to peatio-client-ruby written by czheo.
* [peatioJavaClient](https://github.com/classic1999/peatioJavaClient.git) is a java client written by classic1999.
* [yunbi-client-php](https://github.com/panlilu/yunbi-client-php) is a php client written by panlilu.

### Custom Style

Peatio front-end based Bootstrap 3.0 version and Sass, and you can custom exchange style for your mind.

* change bootstrap default variables in `vars/_bootstrap.css.scss`
* change peatio custom default variables in `vars/_basic.css.scss`
* add your custom variables in `vars/_custom.css.scss`
* add your custom css style in `layouts/_custom.css.scss`
* add or change features style in `features/_xyz.css.scss'

`vars/_custom.css.scss` can overwrite `vars/_basic.css.scss` defined variables
`layout/_custom.css.scss` can overwrite `layout/_basic.css.scss` and `layoputs/_header.css.scss` style

### License

Peatio is released under the terms of the MIT license. See [http://peatio.mit-license.org](http://peatio.mit-license.org) for more information.


### DONATE

**Bitcoin** address [36uSLDtaiBaRrQxgRdC3qdtevLhANBHfd6](https://blockchain.info/address/36uSLDtaiBaRrQxgRdC3qdtevLhANBHfd6)
**Paypal** [https://paypal.me/algobasket](https://paypal.me/algobasket)

# SKYPE : algobasket
# EMAIL : algobasket@gmail.com
