# appthreat.github.io

Source for [www.appthreat.com](https://www.appthreat.com/), hosted on GitHub Pages and built with Jekyll using the [Alembic theme](https://github.com/daviddarnes/alembic) as a remote theme.

The homepage content lives in `index.md`. Site settings, navigation, and the theme configuration live in `_config.yml`. Brand overrides (Inter font, orange accents) live in `assets/styles.scss`, which is compiled to `/assets/styles.css` and linked instead of inlined.

To preview locally:

```shell
bundle install
bundle exec jekyll serve
```

For the full picture of AppThreat projects, see the [organization profile](https://github.com/AppThreat).
