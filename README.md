<img src="https://nes.io/press-kit/nes-symbol.svg" width="140"/>

# Node EcoSystem [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) [![nes.io](https://nes.io/img/nes-badge.svg)](https://nes.io)

> A curated list of projects, tools, and resources for the nes platform.

# Client Libraries

Clients prepare files for uploading using encryption and erasure encoding and upload and download files to the nes network directly to farmers *(running nesshare)* and store meta data on the nes Bridge.

- [libnes](https://github.com/nes/libnes) - Asynchronous multi-platform C library and CLI for encrypted file transfer on the nes network.
- [docker-libnes](https://github.com/jchancehud/docker-libnes) - A docker image containing a built and tested libnes executable.
- [node-libnes](https://github.com/nes/node-libnes) - Bindings to libnes for Node.js (work-in-progress)
- [ruby-libnes](https://github.com/nes/ruby-libnes) - Bindings to libnes for Ruby (work-in-progress)
- [python-libnes](https://github.com/nes/python-libnes) - Bindings to libnes for Python (work-in-progress)
- [java-libnes](https://github.com/nes/java-libnes) - Bindings to libnes for Java (work-in-progress)
- [android-libnes](https://github.com/nes/android-libnes) - Bindings to libnes for Android (work-in-progress)
- [hello-nes](https://github.com/kaloyan-raev/hello-nes) - Example app based on android-libnes (example, work-in-progress)
- [Swiftynes](https://github.com/angu/Swiftynes) - Bindings to libnes for iOS (example, work-in-progress)
- [nesDotNet](https://github.com/ssa3512/nesDotNet) - .NET library for interacting with nes (work-in-progress)
- [libnes.NET](https://github.com/TopperDEL/libnes.NET) - Working .NET library based on java-libnes, nuget-package available (work-in-progress)
- [nes.js](https://github.com/nes/nes.js) - Browser library for interacting with nes (work-in-progress)
- [nes Python Library](https://github.com/nes/nes-python-sdk) - Python library for interacting with nes (work-in-progress)
- [nes-PHP](https://github.com/WebWeave/nes-php) - Implementation of the nes protocol for PHP (work-in-progress)

# Farming

Farmers store data on the nes network in exchange for nes tokens based on contracts with any nes Bridge.

- [nes Share GUI](https://nes.io/share.html) - Earn money by sharing your extra hard drive space on the nes network.
- [nes Share Daemon](https://github.com/nes/nesshare-daemon) - :imp: Daemon + CLI for farming data on the nes network.
- [Payout Formula](https://gist.github.com/pgerbes1/8c0bdfc70055786cec43b885af5b249f) | [previous](https://gist.github.com/super3/a36a3d4967951ec678200f499364b81a) - Transparent formula that is used to calculate farmer payments.
- [nes Wallet](https://github.com/hunterlong/nes-wallet) - nes Wallet (unofficial) for Windows, Mac and Linux. Send and Receive nes ERC20 Token and Ethereum.
- [KFS](https://github.com/nes/kfs) - Kademlia inspired local file store based on LevelDB.
- [nes Collectd Plugin](https://github.com/bobey/nes-collectd-plugin) - Monitor your nes.io nodes along with some Grafana/influxdb like solution.
- [ssdynamite](https://ssdynamite.com/) - Community made tool for analyzing nes Share logs for connectivity issues 
- [nesStat](https://nesstat.com/) - Community made tool for monitoring your nes farming node(s), the tool gives you both real-time and historical analysis.
- [nesBoard](https://nesboard.pro/) - nesBoard is a fully free secured multilingual platform for monitoring your nes farming node(s).
- [nesshare Status Checker](https://github.com/DMcP89/nesShareStatusChecker) - Community made tool for sending nesshare stats to IFTTT.
- [nesshare-config-gen](https://jukeboxrhino.github.io/nesshare-config-gen/) - Easily generate configuration files for nesshare.
- [nes-location-parser](https://github.com/geckogecko/nes-location-parser) - Find the location of nodes that talk to your node.
- [nesPebble](https://github.com/eliassjogreen/nesPebble) - A nes node monitoring app for the pebble smartwatches.
- [nes-HostStats](https://github.com/geckogecko/nes_hoststats_app) - Community made Android app. Features: Node Statistics, Alerts, Response Time Graphs, etc. 
- [nesDash](https://github.com/sibblegp/nes-Dashboard-Client) - Farming Dashboard that tracks useful data about all your servers, nodes, storage space, response times, reputation, and much more.
- [nes Telegraf Plugin](https://github.com/salgieri/nes-Telegraf-Plugin) - A Telegraf Exec Plugin for harvesting nes Metrics.
- [nes_Node_Query](https://github.com/funtimes-ninja/nes_node_query) - Python3 script to get the status of your nodes

# Bridge

Bridges store meta data of files and hold contracts with nes farmers. A Bridge monitors the state of the metadata and will mirror, replicate and repair files when it's necessary.

- [nes Bridge](https://github.com/nes/bridge) - Access the nes network via simple REST API.
- [nes Complex](https://github.com/nes/complex) - Manage many renter nodes with the same identity with remote control capabilities.
- [nes Billing](https://github.com/nes/billing) - Creates debits and credits for nes Bridge users.
- [nes Models](https://github.com/nes/service-storage-models) - Database models for nes Bridge
- [nes Bridge GUI](https://github.com/nes/bridge-gui) - Web application for managing your nes Bridge account.

# Network

Description and implementation for the nes protocol that all nodes and participants in the nes network use to communicate.

- [nes Status](https://status.nes.io/) - Status of the nes network
- [SIPS](https://github.com/nes/sips) - nes Improvement Proposals.
- [nes Core](https://github.com/nes/core) - Implementation of the nes protocol for Node.
- [nes Node Map](http://nesmap.overnetcity.com/) - Uses Bridge API to display online nodes on a map. [[Github]](https://github.com/bobey/nesMap)

# Client Applications & Tools
- [FileZilla](https://docs.nes.io/docs/filezilla-getting-started) - New protocol for nes is being added to FileZilla.
- [nes CLI (C)](https://github.com/nes/libnes) - Newest and recommended CLI tool for nes.
- [nes CLI (Javascript)](https://github.com/nes/core-cli) - Deprecated CLI tool for nes *(supports multifile uploads)*.
- [Heroku Add-on](https://elements.heroku.com/addons/nes) - nes in your favorite cloud platform.
- [nes@stdlib](https://github.com/nes/stdlib.com) - Deploy a serverless datastore on the stdlib network backed by nes.
- [nes.pics](http://nes.pics) - Upload and share pictures using nes 100% in browser. [[Example]](http://nes.pics/#/public/3c894b5bc1b2b8c8a69915c7/files/867cd8678ce8363eb6a38a28) [[Github]](https://github.com/nginnever/nes.pics)
- [nesrb-backupcore](https://bitbucket.org/DaveahamLincoln/nesrb-backupcore) - A generic Ruby script that facilitates the automation of multiple nes backups.
- [nes-gui-client](https://github.com/lakewik/nes-gui-client) - GUI Client for nes Network written in Python and PyQt4.
- [Goobox community](https://github.com/GooBox/goobox-community-gui) - A desktop file synchronization client for nes.

# Tutorials & Examples
- [Quickstart](https://docs.nes.io/) - Steps thought creating an acccount, and using CLI tools.
- [Tutorials](https://nes.github.io/core/) - Full documentation for nes Core, with many example scripts.
- [nes Node Heroku Example in Node.js](https://github.com/nes/nes-node-heroku-example) - Authenticate, create key pairs, create buckets, and upload and download a file.
- [Working with the nes API](https://docs.google.com/document/d/1ehsSHtwnwC-LSgygxYGFuWoCx1DuhA2-XbDw64nggNY/edit?usp=sharing) - Order of method calls for uploading and downloading with the nes API.
- [FAQ](https://nes.io/faq.html) - Frequently Asked Questions.

# Whitepapers
- [nes Whitepaper v2](https://nes.io/nes.pdf) - Published December 15, 2016.
- [nes Whitepaper v1](https://nes.io/nes2014.pdf) - Published December 15, 2014.

# Community
- [Community Chat](https://community.nes.io/) - Open community chat. Our most active discussion area.
- [Community Page](https://nes.io/community.html) - Links to newsletter, chat, social media, and events.  
- [Discord](https://discord.gg/S6KTchS) - Community discord server with chat and voice chat. 

# Contribute to nes
- [nes on Github](https://github.com/nes) - All nes repositories in one place.
- [Give Feedback](https://wantoo.io/nes-product-feedback/) - Suggest new product ideas or upvoting existing ones.
- [Write Guides](https://nes.io/get-paid-to-write.html) - Get paid to write guides and tutorials about our platform.
- [Submit Code](https://nes.io/developers.html) - Submit pull requests on our public repositories on GitHub.

# Support
- [Chat Support](https://community.nes.io/) - Recommend using our community chat for realtime support in many languages.
- [Issue Support](https://docs.nes.io/discuss) - If you any troubles or questions, please contact nes support.
