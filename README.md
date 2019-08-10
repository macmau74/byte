# Byte
Rediscover your music

Interact with your music and fall in love with your library all over again.
Byte offers a beautiful presentation of your Music Library with loads of powerful features in a minimalistic yet highly customizable UI.

## Handy features:
* Light and Dark themes.</li>
* Add up to 100 items under "Recently Added" for songs.
* Sort individual playlists by album, title, play count or recently added.
* Advanced Media Details and Artist Info.
* Group Playlists, Albums, Artists, Songs, etc.
* Search, add and play your favorite online radio stations.

<a href="https://appcenter.elementary.io/com.github.alainm23.byte"><img src="https://appcenter.elementary.io/badge.svg?new" alt="Get it on AppCenter" /></a>

![Byte Screenshot](https://github.com/alainm23/byte/raw/master/data/screenshot/screenshot-01.png)
![Byte Screenshot](https://github.com/alainm23/byte/raw/master/data/screenshot/screenshot-02.png)
![Byte Screenshot](https://github.com/alainm23/byte/raw/master/data/screenshot/screenshot-03.png)
![Byte Screenshot](https://github.com/alainm23/byte/raw/master/data/screenshot/screenshot-04.png)
![Byte Screenshot](https://github.com/alainm23/byte/raw/master/data/screenshot/screenshot-05.png)

## Building and Installation

You'll need the following dependencies:
* libgtk-3-dev
* libgee-0.8-dev
* libgstreamer-plugins-base1.0-dev
* libtagc0-dev
* libsqlite3-dev
* libgranite-dev (>=0.5)
* meson
* valac >= 0.40.3

## Building  

```
meson build && cd build
meson configure -Dprefix=/usr
sudo ninja install
com.github.alainm23.byte
```

## Donations
Stripe is not yet available in my country, If you like Planner and you want to support its development, consider donating via [Patreon](https://www.patreon.com/alainm23)

Made with 💗 in Perú
