# Badrap web pages

This is the source repository for Badrap web pages and additional material available on the web
unlinked.

## Hierarchy

* company/ - old company presentation
* educate/ - WIP educational presentation
* employees/ - employee cyber hygiene page
* gov/ - a presentation for the gov
* health/ - old hygiene deliveri  es
* pitch/ - investor pitch
* pmassets/ - Assets from PM
* press/
* researchers/
* tech/ - fun tech and feature presentation
* testdrive

## Contributing

```console
gem install bundler
gem install github-pages
```

### Commits

* Commits through pull requests
  * Trival typo fixes etc can be pushed straight to master.

* Local edits example:
  * ```bundle install --path vendor/bundle```
  * ```git checkout -b contributing```
  * Edit
  * Check the site: ```bundle exec jekyll liveserve``` - the site is at <http://localhost:4000>
  * ```git push --set-upstream origin contributing```
  * Go to GitHub and create a pull request
  * Ask feedback for your pull request
