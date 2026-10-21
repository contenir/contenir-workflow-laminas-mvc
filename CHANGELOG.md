# Changelog

All notable changes to the 1.x line are documented here. The format follows
[Keep a Changelog](https://keepachangelog.com/en/1.1.0/), and the project
adheres to [Semantic Versioning](https://semver.org/).

## [Unreleased] - 2026-10-21

### Added

- Every navigation page the strategy builds, sub-pages included, carries a `workflow`
  property: the resource's workflow plugin name, `page` when it has none. The sitemap
  in `contenir/seo-laminas-mvc` uses it to leave out the workflows a site excludes.
