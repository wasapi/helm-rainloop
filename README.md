[cookbookurl]: https://geek-cookbook.funkypenguin.co.nz
[kitchenurl]: https://discourse.geek-kitchen.funkypenguin.co.nz
[discordurl]: http://chat.funkypenguin.co.nz
[patreonurl]: https://patreon.com/funkypenguin
[blogurl]: https://www.funkypenguin.co.nz

[![geek-cookbook](https://raw.githubusercontent.com/funkypenguin/www.funkypenguin.co.nz/master/images/geek-kitchen-banner.png)][cookbookurl]


Got more details at:
* ![Discourse with us!](https://img.shields.io/discourse/https/discourse.geek-kitchen.funkypenguin.co.nz/topics.svg) [Forums][kitchenurl]
* ![Chat with us!](https://img.shields.io/discord/396055506072109067.svg) [Friendly Discord Chat][discordurl]
* ![Geek out with us!](https://img.shields.io/badge/recipies-35+-brightgreen.svg) [Funky Penguin's Geek Cookbook][cookbookurl]
* ![Thank YOU](https://img.shields.io/badge/thank-you-brightgreen.svg) [Patreon][patreonurl]
* ![Read blog!](https://img.shields.io/badge/read-blog-brightgreen.svg) [Blog][blogurl]

# Rainloop

[RainLoop](https://github.com/RainLoop/rainloop-webmail) is a simple, modern & fast web-based email client. Further details at <https://www.rainloop.net>.

Features include:
* Modern user interface.
* Complete support of IMAP and SMTP protocols including SSL and STARTTLS.
* Sieve scripts (Filters and vacation message).
* Minimalistic resources requirements.
* Direct access to mail server is used (mails are not stored locally on web server).
* Allows for adding multiple accouns to primary one, simultaneous access to different accounts in different browser tabs is supported. Additional identities.
* Administrative panel for configuring main options.
* Really simple installation and update.
* Integration with Facebook, Google, Twitter and Dropbox.
* Managing folders list.
* Simple look'n'feel customization.
* Configurable multi-level caching system.
* Extending functionality with plugins installed through admin panel.
* Perfect rendering of complex HTML mails.
* Drag'n'drop for mails and attachments.
* Keyboard shortcuts support.
* Autocompletion of e-mail addresses.


# Installation

Install as follows:

```bash
helm repo add funkypenguin https://funkypenguin.github.io/helm-charts
helm repo update
helm install --name rainloop rainloop
```

