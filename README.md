Perpera
=================

**Plugin for [Nextcloud](https://nextcloud.com) and [ownCloud](https://owncloud.org) to create hashes of files and upload them to a public blockchain.**

Installation
------------

**Nextcloud**

In your Instance, simply navigate to »Apps«, choose the category »Files«, find the Perpera app and enable it.

**ownCloud**
- Copy the perpera folder in the app directory of owncloud.
- If not already done, rename the app-folder to "perpera" - causes overwise an sql error.
- Enable this app in the admin interface.

Usage
-----

Just open the details view of the file (Sidebar). There should be a new tab called "Perpera". 

Compatibility
-------------

- I only tested the app for the current version of owncloud (9.x) and Nextcloud 10 and 11.
- I tried to use the current api as much as possible. It should be safe for future versions.
