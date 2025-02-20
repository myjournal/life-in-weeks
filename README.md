# Life in Weeks

I originally saw this on [GitHub](https://github.com/ginatrapani/life-in-weeks) and thought it would be an interesting thing to try to do.

It is an interactive map of my life in weeks, where each week I've been alive is a box. The border color of each box represents where I was living, and the inner color of the box is what I was doing that week.

Read more about [Life in Weeks at Wait But Why](https://waitbutwhy.com/2014/05/life-weeks.html).

This code was copied from [GitHub](https://github.com/ginatrapani/life-in-weeks). It is a single webpage statically-rendered with [Hugo](https://gohugo.io/). It consists of two [data](data/events.yml) [files](data/colors.yml), [an introduction](content/index.md), and a [template](layouts/_default/index.html).

## 🚀 Setup

1. Install Hugo:
   ```sh
   brew install hugo  # Mac
   ```
2. Clone and run locally:
```sh
    git clone https://github.com/myjournal/life-in-weeks.git
    cd life-in-weeks
    hugo server -D
```
3. Visit [http://localhost:1313/](http://localhost:1313/).

## ✨ Customize

- `content/` → Page content
- `data/events.yml` → All the events of my life
- `data/colors.yml` → Define the colors for the boxes
- `layouts/` → Templates
- `assets/scss/` → Styles
- `assets/imgs/` → Site-wide images
- `static/` → Unprocessed assets
- `hugo.toml` → Site settings

## Colophon

This page uses [Bootstrap](https://getbootstrap.com/) for layout and interaction, and a smidge of [jQuery](https://jquery.com/) to reflect the current week on the map.

The font is [Red Hat Display](https://fonts.google.com/specimen/Red+Hat+Display). Colors chosen via [Color Hunt](https://colorhunt.co/).
