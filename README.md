# gander-settings.github.io

Landing page for the [gander-settings](https://github.com/gander-settings) organization, published at <https://gander-settings.github.io/>.

gander-settings hosts publicly visible configurations used by [gander](https://github.com/gander).

## Available projects

| Project | Page |
| --- | --- |
| [gander-settings/renovate](https://github.com/gander-settings/renovate) | <https://gander-settings.github.io/renovate/> |

This is currently the only available project.

## Development

The site is built by GitHub Pages with [Jekyll](https://jekyllrb.com/). Projects are listed in `_data/projects.yml`; add an entry there to show a new project on the page. The optional `llms_txt` field adds an `llms.txt` badge linking to that file.

```sh
bundle install
bundle exec jekyll serve
```
