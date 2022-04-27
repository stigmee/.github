# Welcome to Stigmee project

Stigmee is a decentralized and open source web browser and social network 3D,
made with Godot and the Chromium Embedded Framework, it is designed to run on PC
(Linux, Mac OS, Windows...) and expected for mobile (iOS, Android). It can be
seen as an open source competitor and decentralized direct to the Metaverse, but
it is much more than that. In Stigmee, the users (the Stigmers) assemble
collections of relevant web addresses, such as collections of tabs in a browser.
Assembling a series of URLs can take between 15 minutes and 15 hours depending on
the topic (which restaurant are we going to tonight? 15 mins; which
cryptocurrency to buy? 15 hours) and when a user closes his window with his
relevant tabs, all that work is wasted. To not have loosing them, Stigmee preserves
them anonymously and uses them for offering a collection of relevant tabs to the user
directly, potentially saving him 15 hours since nobody wants to see 30 pop-up
tabs in their browser at the same time, Stigmee requires containing the
experience and the interface: it's there where the 3D web and Godot take actions: the
tab series is represented as a "strand", depicted by the shore of a river in where URLs
are spatialized as lands by a river this strand can be copied, modified, shared
(modified). This working method is comparable to that of WAZE which uses the
paths traveled by motorists to calculate the best paths possible, it is called
STIGMERGY and comes from hives and anthills.  This is why the network is called
STIGMEE.

Notre Slogan: "Mind Beauty" d'après l'explorateur et Gentleman Extraordinaire
(Conan Doyle a inventé le terme pour lui) Richard Francis Burton "Thy Thought to
Thee an Empire Be": "fais de ta Pensée un Empire".

## Resources

- Our GitHub:
  - https://github.com/stigmee
- Our itch:
  - https://stigmee.itch.io
- Our laboratory (private):
  - https://labo.stigmee.fr
- Our mediatheque:
  - https://mediatheque.stigmee.fr
- Our Discord:
  - https://discord.gg/SB7vAgDyNG
- Tutorial concerning our Discord (Google doc):
  - https://docs.google.com/document/d/1PurXBZW6FXdPvxGwbI8tUxvNBjJ6qN9o/edit
- Our first mockup:
  - http://chreage.befuse.com/content/WEBGL/ChreageAlpha0-3/index.html

## GitHub

- https://github.com/stigmee/install Scripts for building Stigmee and continuous integration.
- https://github.com/stigmee/manifest Manifest of git repos needed to make the Stigmee workspace.
- https://github.com/stigmee/gdnative-cef Godot native module for using Chromium Embedded Framework.
- https://github.com/stigmee/gdnative-stigmark Godot native module for using bookmarks collected by [stigmark-server](https://github.com/stigmee/stigmark-server).
- https://github.com/stigmee/gdnative-ipfs Godot wrapper for using IPFS protocol.
- https://github.com/stigmee/stigmark-server A Chrome/Firefox plugin for collecting bookmarks to the database.
- https://github.com/stigmee/beebots collecting and scoring URLs.
- https://github.com/stigmee/assets The graphical 2D/3D assets for the GUI and 3D world.
- https://github.com/stigmee/stigmee The Stigmee application made in Godot script.
- https://github.com/stigmee/doc-internal Our internal documentation.
- https://github.com/stigmee/bootstrap (old) script for building Brave inside a Docker.

## How to start ?

For installing Stigmee, you have to follow instructions in the
[install](https://github.com/stigmee/install).

The Stigmee code source has been split into several git repositories. To
download them into a workspace we are using a special tool and the README of
this [repository](https://github.com/stigmee/manifest) will explain it deeply.

All `gdnative-XXX` (XXX: cef, stigmark, ipfs) are our wrapper on libraries or
our personal libraries to be used by Godot script.

The Stigmee repo contains the Godot code making the Stigmee application.

## How to help ?

Currently, we have ended with our first minimal valid product (MVP): to check if
CEF can live within Godot (and the answer is yes): we can compile Stigmee for
Linux and Windows. The application is offering some features such as displaying
islands, strands, web pages, and database ... But we have plenty of features to
implement before Stigmee becomes a full usable application: such as the
distributed database, create our own tokens (money), improve the GUI (we need
artists) and make a portage for devices such as Android.

Contributions, bug fixes and improvements are welcome. For major contribution,
please first contact our team (Discord or through the GitHub discussion) before
coding and creating pull request: this will help to discuss before and help the
synchronization with our team (no work make in double, ...)
