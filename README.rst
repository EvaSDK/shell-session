=============
shell-session
=============

shell-session is a simple python script that lets you start dbus
based daemons that require a session bus without requiring a full
blown desktop.

Why
===

This tool was written in order to simplify starting rygel and tracker
on a file server that runs a minimal installation (no desktop, no X).

The experience should be as follows:
 * start shell-session on boot
 * start your DLNA device
 * profit

License
=======

shell-session is licensed under the `GNU GPL-3 <http://www.gnu.org/licenses/gpl-3.0.txt>`_.

Development
===========

We use `semantic versioning <http://semver.org/>`_ for versioning.
When working on a development release, we append ``~dev`` to the 
current version to distinguish released versions from development
ones.
