awesome
=======

This repository contains personal list of awesome software.

Data management and synchronisation:
----------------

- [Syncthing](https://syncthing.net/) - seamless synchronisation of files.

  > Syncthing is a continuous file synchronization program. It synchronizes files between two or more computers in real time, safely protected from prying eyes. Your data is your data alone and you deserve to choose where it is stored, whether it is shared with some third party, and how it's transmitted over the internet.
  

Libraries
---------

Authorization and policy evaluation:

- [Open Policy Agent](https://github.com/open-policy-agent/opa) - supports partial evaluation, can be embedded as a go library,
- [Oso](https://github.com/osohq/oso) - supports data filtering via execute for query, can be embedded as a library in multiple languages.


Server setup, via docker:
-------------------------

HTTP reverse proxy and SSL:

- [jwilder/nginx-proxy](https://github.com/jwilder/nginx-proxy) for easy auto-configured reverse proxy setup,
- [JrCs/docker-letsencrypt-nginx-proxy-companion](https://github.com/JrCs/docker-letsencrypt-nginx-proxy-companion) for integration of ***Let's Encrypt*** to *nginx-proxy*,

Mail server:

- [tomav/docker-mailserver](https://github.com/tomav/docker-mailserver) for quick setup of `postfix/dovecot/fail2ban/...` email server,

Desktop environment - GNOME 3:
------------------------------

GNOME 3 offers elegant and consistent looks, and almost productive experience, straight from clean installation, using default settings. 

Configuration of GNOME 3 is based on dconf configuration system, which offers nice text-based gittable exports. Partial imports of configuration is easy: `cat settings-file.ini | dconf load /`.

Extensions:

- [Dash to Dock](https://extensions.gnome.org/extension/307/dash-to-dock/)
- [system-monitor](https://extensions.gnome.org/extension/120/system-monitor/)

Utilities:
----------

- [Solaar](https://pwr-solaar.github.io/Solaar/) ([git](https://github.com/pwr-Solaar/Solaar)) -  a Linux manager for many Logitech keyboards, mice, and trackpads that connect wirelessly to a USB Unifying, Bolt, Lightspeed, or Nano receiver, connect directly via a USB cable, or connect via Bluetooth.

Linux technologies
------------------

[dconf](https://en.wikipedia.org/wiki/Dconf) is a low-level configuration system and settings management tool, which is optimized for reads, and supports notifications about changed configuration.
