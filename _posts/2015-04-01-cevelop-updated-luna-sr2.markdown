---
layout: post
title:  "Update to Eclipse Luna SR2 and Eclipse CDT 8.6"
---

Not a joke &ndash; we have just released [Cevelop 1.2.0](/download) to give you the latest Eclipse Luna Service Release SR2 and Eclipse CDT 8.6. Feature-wise, the new CDT release includes [many debugging improvements](https://wiki.eclipse.org/CDT/User/NewIn86) and the rename class refactoring now renames files as well. We also fixed a bug where custom formatter profiles were lost on restart and we reduced the maximum amount of memory Cevelop requests on 32bit systems from 2GB to 1GB.

Our C++ unit testing framework CUTE has been updated to version 4.11. This new release allows you to upgrade any existing project to a CUTE project. For a full list of changes, see [the release announcement](http://cute-test.com/news/18).

Just download [Cevelop 1.2.0](/download) or if you are already using Cevelop, you can also try to update your installation through Help -> Check for Updates. Note that there are some issues with [updating Eclipse products on Windows](http://stackoverflow.com/questions/22427728/eclipse-kepler-cant-install-updates), so we recommend downloading a fresh copy. If you are running OS X, we also recommend downloading a fresh installation. All your settings are stored in the workspace so they won't get lost.

For the next release, we have planned to include a brand new plug-in that helps you refactor char-pointers to proper C++-string objects.

<p class="pull-right">
  <em>&mdash; Mirko Stocker</em>
</p>
