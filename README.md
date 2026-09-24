# jialingYK.github.io

Personal academic homepage of Jialing Cai, built with the [academic-homepage](https://github.com/luost26/academic-homepage) Jekyll template.

## Where to edit

| What | File |
| --- | --- |
| Name, bio, links, education, experience | `_data/profile.yml` |
| Navigation bar | `_data/navigation.yml` |
| Co-author links / bold name | `_data/authors.yml` |
| News | `_news/*.md` (one file per item) |
| Publications | `_publications/*.md` (one file per paper; `selected: true` shows it on the homepage) |
| Hobbies page cards | `_hobbies/**/*.md` (`group`, `width` 1-12, `order`) |

## Preview locally

```bash
bundle install
bundle exec jekyll serve
```
