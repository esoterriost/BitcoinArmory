**Copyright (C) 2011-2015, Armory Technologies, Inc.**

**Distributed under the GNU Affero General Public License (AGPL v3)**

**See LICENSE or http://www.gnu.org/licenses/agpl.html**

Description
-----------

This directory is meant to contain Armory plug-ins. Plug-ins will generally have a zip file whose structure looks like this:

SomePlugin.zip

- inner.zip
- properties.txt
- signature.txt

In turn, the inner.zip file looks like this:

- SomePlugin.py
- *some other files*...

The signature.txt is a signature from Armory Technologies, Inc. If you are not using a plug-in signed by Armory Technologies, Inc., you can still run the plug-in, but only with --testnet.
