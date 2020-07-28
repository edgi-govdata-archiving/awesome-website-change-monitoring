# **IMPORTANT! We've moved development of this repo to the `main` branch. You will not be able to merge changes into `master`.**

## **UPDATING LOCAL CLONES**

(via [this link](https://www.hanselman.com/blog/EasilyRenameYourGitDefaultBranchFromMasterToMain.aspx), thanks!)

If you have a local clone, you can update and change your default branch with the steps below.

```sh
git checkout master
git branch -m master main
git fetch
git branch --unset-upstream
git branch -u origin/main
git symbolic-ref refs/remotes/origin/HEAD refs/remotes/origin/main
```

The above steps accomplish:

1. Go to the master branch
2. Rename master to main locally
3. Get the latest commits from the server
4. Remove the link to origin/master
5. Add a link to origin/main
6. Update the default branch to be origin/main

[![Code of Conduct](https://img.shields.io/badge/%E2%9D%A4-code%20of%20conduct-blue.svg?style=flat)](https://github.com/edgi-govdata-archiving/overview/blob/master/CONDUCT.md)

# Awesome Website Change Monitoring [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

> A ~curated~ _comprehensive_ list of awesome tools for website diffing
> and change monitoring.

Unlike many awesome lists, this area is so small that we are currently
aspiring to map the whole tool landscape :)

For a more in-depth comparison of these tools, please see our [Google Spreadsheet][spreadsheet]. All contributions are welcome!

[![Comparison Spreadsheet](https://i.imgur.com/dtT1Cjj.png)][spreadsheet]


## Contents

- [Content Diffing](#content-diffing)
  - [Open Source](#open-source)
  - [Hosted Services](#hosted-services)
- [Content Extraction](#content-extraction)

| Legend |
|--------|
| :beer: Free |


## Content Diffing

### Open Source

- [DiffEngine][].
- [EDGI Web Monitoring][edgi-webmon]
- [Huginn][].
- [Klaxon][]. [code][klaxon-code]
- [NewsDiffs][]. [code][newsdiffs-code]
- [NYTdiff][]. [code][nytdiff-code]
- [Pagelyzer][]. [code][pagelyzer-code]
- [Time Machine][]. [code][timemachine-code]. Also a hosted service.
- [Website Change Monitor][website-change-monitor].


### Hosted Services

Closed source unless indicated otherwise.

- [Distill][]
- Distill Web Monitor browser extension. [Chrome][distill-chrome] - [Firefox][distill-ff]. (Formerly Alertbox.)
- [ChangeDetect][]
- [ChangeTower][]
- [Follow That Page][]
- [OnWebChange][]
- [PageFreezer][]
- [TheWebWatcher][] :beer:
- [Trackly][]
- [Versionista][]
- [VisualPing][] Has [chrome browser extension][visualping-chrome].
- [Wachete][]
- [WatchThatPage][]

## Content Extraction

- [Diffbot][]


## Contribute

Contributions welcome! Read the [contribution guidelines](https://github.com/edgi-govdata-archiving/awesome-website-change-monitoring/blob/master/CONTRIBUTING.md) first.


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](http://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, Patrick Connolly has waived all copyright and
related or neighboring rights to this work.

   [huginn]: https://github.com/huginn/huginn
   [klaxon]: https://www.newsklaxon.org/
   [klaxon-code]: https://github.com/themarshallproject/klaxon
   [pagelyzer]: http://pagelyzer.openpreservation.org/
   [pagelyzer-code]: https://github.com/openpreserve/pagelyzer
   [trackly]: https://trackly.io/
   [versionista]: https://versionista.com/
   [visualping]: https://visualping.io/
   [visualping-chrome]: https://chrome.google.com/webstore/detail/visualping/pemhgklkefakciniebenbfclihhmmfcd
   [follow that page]: https://www.followthatpage.com/
   [diffbot]: https://www.diffbot.com/
   [pagefreezer]: https://www.pagefreezer.com/
   [diffengine]: https://github.com/DocNow/diffengine
   [nytdiff]: https://twitter.com/nyt_diff
   [nytdiff-code]: https://github.com/j-e-d/NYTdiff
   [onwebchange]: https://onwebchange.com/
   [thewebwatcher]: http://www.thewebwatcher.com/
   [ChangeTower]: https://changetower.com/
   [ChangeDetection]: https://www.changedetection.com/
   [WatchThatPage]: http://www.watchthatpage.com/
   [NewsDiffs]: http://newsdiffs.org/
   [newsdiffs-code]: https://github.com/ecprice/newsdiffs
   [wachete]: https://www.wachete.com/
   [spreadsheet]: https://docs.google.com/spreadsheets/d/1TqKX1PA2eOszLgb8Vejw5GPe4STJkHWFe2_IUa3t5gM/edit#gid=0
   [distill]: https://distill.io/
   [distill-ff]: https://addons.mozilla.org/en-us/firefox/addon/alertbox/
   [distill-chrome]: https://chrome.google.com/webstore/detail/distill-web-monitor/inlikjemeeknofckkjolnjbpehgadgge?hl=en
   [edgi-webmon]: https://github.com/edgi-govdata-archiving/web-monitoring
   [ChangeDetect]: http://www.changedetect.com/
   [Time Machine]: http://timemachine.truthmeter.mk
   [timemachine-code]: https://bitbucket.org/metamorfozis/news
   [website-change-monitor]: https://github.com/JuanmaMenendez/website-change-monitor
