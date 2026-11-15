# iptv-url — Malayalam IPTV Playlist

A curated **Malayalam IPTV playlist containing only verified, working links**, built from
[iptv-org](https://github.com/iptv-org/iptv)'s Malayalam language playlist plus additional
working channels found in community lists around the web.

**Last verified: 2026-09-30 · 71 channels**

## 📺 Playlist URL

Paste this into any IPTV player (VLC, TiviMate, OTT Navigator, iMPlayer, Kodi PVR Simple Client, etc.):

```
https://raw.githubusercontent.com/binief/iptv-url/main/malayalam.m3u
```

CDN mirror (sometimes faster, cached):

```
https://cdn.jsdelivr.net/gh/binief/iptv-url@main/malayalam.m3u
```

## What's inside

| Group | Channels |
|---|---|
| Malayalam News | 15 — Asianet News, Manorama News, Mathrubhumi News, News18 Kerala, Media One, 24 News, Kairali News, Janam TV, Reporter TV, Raj News, Big TV 24x7, Real News Kerala, VBC News, Eagle One News, Citi News |
| Malayalam Entertainment | 17 — Asianet HD, Asianet Middle East, Mazhavil Manorama (SD/HD/International), Amrita TV, DD Malayalam, Jaihind TV, Kairali TV, Jeevan TV, Kerala Vision, Darshana TV, Flowers TV USA, Anand TV, Magnavision TV, Pravasi Channel, Pulari TV |
| Malayalam Movies | 1 — Asianet Movies |
| Malayalam Music | 1 — Raj Musix Malayalam |
| Malayalam Lifestyle | 1 — Kappa TV |
| Malayalam Documentary | 1 — Safari TV |
| Malayalam Education | 1 — Kite Victers |
| Malayalam Culture | 1 — C Malayalam TV (Canada) |
| Malayalam Religious | 11 — Shalom, Shalom Global, Shalom America, Harvest TV, Harvest TV Keralam, Goodness TV, Powervision TV, Potta-Divine TV USA, Shekinah TV, Word To World, MTA7 Asia |
| Kerala Local | 15 — KCL TV, CCV, Starnet, VCV, Vision, UTV Palakkad, N Vision, Swantham, Malabar Plus, Metro Live, MCV Channel, South Vision, City Channel, City Vision Kannur, Vibgyor TV |
| Kids (India) | 4 — ETV Bal Bharat, Sony Yay!, Nickelodeon, Sonic |
| Sports (India) | 3 — Sony Sports Ten 1 HD, Ten 5, Ten 5 HD |

The Kids/Sports entries are Indian channels that iptv-org tags with Malayalam (multi-language
audio); they are kept in separate groups so you can filter them out easily.

## Sources

1. **iptv-org** — [languages/mal.m3u](https://iptv-org.github.io/iptv/languages/mal.m3u)
   (every link tested; only the working ones were kept)
2. **Community lists** (additional channels / replacement links, each individually tested):
   - [dreamtech1111's Malayalam gist](https://gist.github.com/dreamtech1111/fff7fa6860844dadfd2134f320628ec4) — VBC News updated link, working Harvest TV link
   - [amazeyourself/tamil-local-iptv](https://github.com/amazeyourself/tamil-local-iptv) (`channels-ml.m3u`) — Kerala local channels (N Vision, Swantham, Malabar Plus, Metro Live, MCV, Citi News, South Vision, City Channel, City Vision, Vibgyor TV, Word To World, Shekinah TV relay, Eagle One News)
   - [amazeyourself/adaptive-streams](https://github.com/amazeyourself/adaptive-streams) — direct Asianet HD link, Mazhavil Manorama International
   - [firozkotta/padulive](https://github.com/firozkotta/padulive) (`kerala_tv.m3u`) — Eagle One News, DD Malayalam alternate

## Links removed from the source (dead at test time)

Garshom TV, Kalika TV, Shekinah TV (original link), Harvest TV (original smartplay link — replaced),
Kairali We (audio-only at test time), CD News, Doctor Live, Venad News, Kannur Vision,
New Media Channel, Flowers TV (India), Zee Keralam, Kaumudy TV, Asianet Plus, Surya TV,
plus all geo-blocked/expired Malaysian channels that iptv-org files under the Malayalam
language code (DidikTV KPM, meWATCH, NTV7, RTM Parlimen, SelangorTV).

## Notes

- Streams were verified at the HLS-manifest level on **2026-09-30**. Free IPTV links rot
  quickly — expect occasional breakage. Re-run/PR fixes welcome.
- Some streams may be **geo-restricted** (particularly the Sony pages.dev links and channels
  served from Indian CDNs) depending on where you watch from.
- `[Not 24/7]` channels only broadcast part of the day.
- This playlist aggregates publicly available free streams for personal use, same as
  iptv-org does. No paid/subscription channels are included.

## Usage

**VLC:** Media → Open Network Stream → paste the playlist URL
(not VLC's best format — a dedicated IPTV app is recommended for EPG/logos/groups)

**TiviMate / OTT Navigator / iMPlayer:** Add playlist → M3U URL → paste

**Kodi:** PVR IPTV Simple Client → M3U URL → paste
