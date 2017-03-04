# Awesome news hacks

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

Awesome bits of code built and tested in newsrooms for the purpose of enabling smarter, faster and better journalism.

#### NICAR 2017

This list supplements the [Hack Swap](http://ire.org/events-and-training/event/2702/2988/) session at [NICAR 2017](http://ire.org/conferences/nicar2017/).

**2:15 p.m. - 3:15 p.m., Saturday | City Terrace 12**


##### Session description

> In the last year you’ve built a bit of code that someone else needs. Buried deep in your github is a half week of work, doomed to repeat itself by newsroom developers just like you, over and over. But it doesn’t have to be this way. Dedup the world and come to the inaugural hack swap. Think of it as a flea market of code, this session is designed to encourage sharing of code bits nearly great and small.

> We’ll take early submissions and organize a handful of lightning demos of open-source code ready to share today and lead a chat with other devs and journo coders about your most nearly-there project. We’ll also write up everyone’s OS code with short synopses and links for a future Source post.

> Come be part of the news nerd sharing economy.

#### An awesome list with a sense of purpose!

Many of us work in small teams or alone in our newsrooms. All of us rely on shared code to make us faster and better at what we do.

We want to help diversify the scale and community of open source sharing in journalism. Everyone can contribute their bit. Whether it's a few lines of bash to ease a public data import to a new framework, we think sharing code, especially nearly-great and small code, adds to the overall health of journalism and, by extension, of democracy.

Seriously, we said that once.


#### How you can participate

Send a pull request to this repo with your awesome news hack as per our [contributor guide](CONTRIBUTING.md) and come to the Hack Swap session at NICAR 2017 to tell others about your awesome hack and what it do.


#### What kinds of projects should be here

Simply put: We're looking for code that clearly enables journalism.

What that means is open to welcome debate, but here are some ins and outs we have in mind:

##### In
- Couple lines of bash that help process election data
- JavaScript library that helps present responsive charts

##### Likely out
- A React plugin that renders an awesome date picker
- Code closely tied to a specific story that can really only be used to replicate the same story


#### Current Curators/NICAR 2017 session emcees

- [Jon McClure](https://twitter.com/JonRMcClure)
- [Andrew Chavez](https://twitter.com/adchavez)
- [Jeremy Bowers](https://twitter.com/jeremybowers)


Want to help curate this list? Drop a line in the issues.


# Hacks <a name="hacks"></a>

#### Contents

- [Data utils](#hacks-data-utils)
- [Dataviz tools](#hacks-dataviz)
- [Elections](#hacks-elections)
- [Geo tools](#hacks-geo)
- [Scrapers](#hacks-scrapers)
- [Miscellany](#hacks-misc)


### Data utils <a name="hacks-data-utils"></a>

|   Project  | [datakit-core](https://github.com/associatedpress/datakit-core)  |
|----------|--------|
|What it do|Datakit is a pluggable command-line tool for managing the life cycle of data projects. The Associated Press Data Team uses Datakit to auto-generate project skeletons, archive and share data on Amazon S3, and other routine tasks. |
|Languages/Frameworks| Python |
|Authors| Serdar Tumgoren, Associated Press|

|   Project  | [indian-ocean](https://github.com/mhkeller/indian-ocean)  |
|----------|--------|
|What it do|A NodeJS library for reading and writing data plus some handy file system utilities. Supports csv, tsv, json, yaml, dbf as well as custom formats and delimeters.|
|Languages/Frameworks| Node |
|Authors| Michael Keller|

|   Project  | [joiner](https://github.com/mhkeller/joiner)  |
|----------|--------|
|What it do|A simple utility for SQL-like joins with Json, GeoJson or dbf data in Node, the browser and on the command line. Also creates join reports so you can know how successful a given join was.|
|Languages/Frameworks| Node |
|Authors| Michael Keller|

|   Project  | [schedule-data-loader](https://github.com/OpenNews/schedule-data-loader)  |
|----------|--------|
|What it do| A lightweight Python script that fetches data from a Google spreadsheet, transforms to JSON, then optionally commits a data file to a GitHub repo. Suitable for dropping into projects as a task for cron or Slackbot trigger.|
|Languages/Frameworks| Python |
|Authors| Ryan Pitts |


|   Project  | [tables](https://github.com/datanews/tables)  |
|----------|--------|
|What it do| Tables is a simple command-line tool and powerful library for importing data like a CSV or JSON file into relational tables.|
|Languages/Frameworks| JavaScript |
|Authors| Alan Palazzolo, WNYC |


### Dataviz tools <a name="hacks-dataviz"></a>

|   Project  | [chartwerk-editor](https://github.com/DallasMorningNews/chartwerk-editor)  |
|----------|--------|
|What it do| Our newsroom graphics appliance. Lets us develop and tweak chart templates easily alongside reporters, publish embeddable interactive or static charts to AWS and quickly build chart types using any third party libs we like. |
|Languages/Frameworks| Javascript, React, Redux|
|Authors| Jon McClure, The Dallas Morning News|


### Elections <a name="hacks-elections"></a>

|   Project  | [mccelections](https://github.com/mcclatchy/mccelections)  |
|----------|--------|
|What it do| Open-source Django application to ingest, store and output election results.|
|Languages/Frameworks| Python, Django |
|Authors| Greg Linch, McClatchy |


### Geo tools <a name="hacks-geo"></a>

|   Project  | [lunchbox boundaries](https://github.com/stlpublicradio/lunchbox)  |
|----------|--------|
|What it do|An add-on to NPR lunchbox that adds a boundary lookup by street address.|
|Languages/Frameworks| Python |
|Authors| Brent A Jones, St. Louis Public Radio|


### Scrapers <a name="hacks-scrapers"></a>

|   Project  | [ipeds-scraper](https://github.com/UrbanInstitute/ipeds-scraper)  |
|----------|--------|
|What it do|Downloads Integrated Postsecondary Education Data System (IPEDS) complete data files|
|Languages/Frameworks| Python |
|Authors| Ben Chartoff|


### Miscellany <a name="hacks-miscellany"></a>

|   Project  | [cron-starter-kit](https://github.com/nprapps/cron-starter-kit)  |
|----------|--------|
|What it do|This is a simple starter kit for deploying and maintaining cron jobs on EC2 servers. Examples in use: [bernard](https://github.com/nprapps/bernard) and [clark](https://github.com/nprapps/clark).|
|Languages/Frameworks| Python |
|Authors| Tyler Fisher, NPR |

|   Project  | [django-rolodex](https://github.com/DallasMorningNews/django-rolodex)  |
|----------|--------|
|What it do| Newsroom contacts manager. Built with cool extras like graph analysis of social networks. We also use it to track the diversity of our sources. |
|Languages/Frameworks| Python, Django|
|Authors| Jon McClure, The Dallas Morning News|


|   Project  | [mta-styles](https://github.com/datanews/mta-styles)  |
|----------|--------|
|What it do| The colors of the MTA in an easy to include library.|
|Languages/Frameworks| JavaScript |
|Authors| Alan Palazzolo, WNYC |



|   Project  | [pym-shortcode](https://github.com/INN/pym-shortcode)  |
|----------|--------|
|What it do| A WordPress plugin adding a [pym src=""] shortcode to simplify the process of using pym.js. |
|Languages/Frameworks| JavaScript, PHP |
|Authors| RC Lations |

|   Project  | [python-frontmatter](https://github.com/eyeseast/python-frontmatter)  |
|----------|--------|
|What it do|Jekyll-style YAML front matter offers a useful way to add arbitrary, structured metadata to text documents, regardless of type. This is a small package to load and parse files (or just text) with YAML front matter. |
|Languages/Frameworks| Python |
|Authors| Chris Amico, Frontline|

|   Project  | [srccon-schedule](https://github.com/OpenNews/srccon-schedule)  |
|----------|--------|
|What it do| The code underneath the schedule app for SRCCON.|
|Languages/Frameworks| JavaScript |
|Authors| Ryan Pitts |



## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)
