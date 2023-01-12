# Torrent Player

**Torrent Player** is a site where anyone can stream torrents directly from their browser.

It uses **[WebTorrent](https://webtorrent.io/)** - the first torrent client that works in the browser. **WebTorrent** uses **[WebRTC](https://webrtc.org/)** for true peer-to-peer transport. No browser plugin, extension, or installation is required.

---

### Note

*In the browser, WebTorrent can only download torrents that are seeded by a WebRTC-capable torrent client.*

> What does that mean?

It means that, for now, not every torrent will work on this site.

> Why??

Because most people use native torrent clients like *BitTorrent*, *Transmission*, *μTorrent*, etc. which do not use the [WebRTC](https://en.wikipedia.org/wiki/WebRTC) transport protocol, but the [TCP](https://en.wikipedia.org/wiki/Transmission_Control_Protocol)/[uTP](https://en.wikipedia.org/wiki/Micro_Transport_Protocol).
