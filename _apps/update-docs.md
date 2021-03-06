---
title: Update Docs
description: Replies to newly opened pull requests that do no update a file in the
  `/docs` folder or the `README`
slug: update-docs
screenshots:
- https://user-images.githubusercontent.com/13410355/28179044-97207bee-67b5-11e7-80d0-0c8ede4a325f.png
stars: 5
authors:
- hiimbex
repository: behaviorbot/update-docs
updated: 2017-10-19 16:03:37 UTC
host: https://probot-update-docs.herokuapp.com
installations: 12
organizations:
- adonisjs
- xcodeswift
- behaviorbot
- ilovecode1
- marclop
- philoserf
- cms-gem-daq-project
- robotland
---


Update Docs comments on newly opened Pull Requests that do not update either the README or a file in the `/docs` folder.

Create a `.github/config.yml` file that contains the contents you would like to reply within an `updateDocsComment`. Optionally, you can also add an `updateDocsWhiteList` that includes terms, that if found in the title, the bot will not comment on.

```yml
# Configuration for update-docs - https://github.com/behaviorbot/update-docs

# Comment to be posted to on PRs that don't update documentation
updateDocsComment: >
  Thanks for opening this pull request! The maintainers of this repository would appreciate it if you would update some of our documentation based on your changes.

# Terms that if found in the title of a PR will prevent the bot from commenting on it
updateDocsWhiteList:
  - bug
  - chore
```
