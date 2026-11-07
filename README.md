# Respawn

A theme for [Kosatka](https://github.com/kosatka-cms/kosatka): a light
portal of news and reviews - a white header with the main menu and a
search, cards on light grey, a front page that leads with its first item,
a dark footer, one accent colour. A list field's options show as coloured
badges in their order (a review's verdict, a difficulty), so it suits a
site of ratings and reviews.

![Respawn](https://raw.githubusercontent.com/kosatka-cms/kosatka-theme-respawn/main/static/screenshot.jpg)

## Install

```bash
app theme add https://github.com/kosatka-cms/kosatka-theme-respawn
```

Then commit `themes/` and choose *Respawn* on *Appearance*. See
[Distributing a theme](https://kosatka-cms.github.io/kosatka/themes/distribute/).

## Settings

On *Appearance → Respawn → Settings*:

| Setting | Default |
|---|---|
| Accent colour | `#d72638` |
| The header's mark - the theme's ring or the site's logo | the ring |
| A search in the header | on |

## Regions

The engine's regions - *Header*, *Sidebar*, *Content top*, *Content
bottom*, *Inside content*, *Footer*, *Footer bottom line* - so blocks
placed for another theme stay where they are. A new site gets the
copyright block in *Footer bottom line*.

## Fonts

Golos Text, with Latin and Cyrillic. It comes with the theme
(`static/fonts`, SIL Open Font License 1.1) and the site serves it: no
requests to other servers.

## Translations

The theme's own strings: English, Russian, German and Spanish
(`translations/`).

## License

MIT
