# Awesome Atomist  [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

A curated list of Atomist articles, references, guides, courses, books, videos and presentations

Contributions most welcome. See (https://github.com/sindresorhus/awesome) for contributions guidelines.

![Atomist](https://pbs.twimg.com/profile_images/708279517899563008/FcOUbYXB.jpg)

# Contents

1. [Articles](#articles)
2. [Community](#community)
3. [Meetups](#meetups)
4. [References](#references)
5. [Guides](#guides)
6. [Code](#code)
7. [Videos](#videos)
8. [Presentations](#presentations)
9. [Courses and Tutorials](#courses-and-tutorials)
10. [Books](#books)
11. [Templates and Editors](#templates-and-editors)
12. [Repository Support](#repository-support)
13. [Tooling](#tooling)
14. [Resources](#resources)
15. [Misc](#misc)

# Articles

* [The Composition](https://medium.com/the-composition) - Articles from the Atomist Team covering Rugs, etc.
  * [Introduction to Atomist Editors](https://medium.com/the-composition/software-that-writes-and-evolves-software-953578a6fc36#.abvq9g980) - The fundamental differentiation provided by Atomist over previous project generation approaches.
  * [Evolving Projects Using Atomist Editors](https://medium.com/the-composition/evolving-projects-using-atomist-editors-fd3b1f057c86#.7i0nx3env) - Continuing the series started in *Introduction to Atomist Editors* this post steps through the mechanics of creating a Spring Boot project with one editor action and then running a second editor to bring in Neo. The article also dives down into the structure of Rug types which are used to create new Atomist editors.
  * [Updating Multiple Projects using Atomist Executors] (https://medium.com/the-composition/understand-automate-collaborate-1b5695ecb724#.8ffgnmr1n)
  * [BDD with Rug](https://medium.com/the-composition/bdd-with-rug-371e85d7a1a9#.p2feulni0) - This soup to nuts account of the process to create a new editor with test scenarios introduces the use the Rug Test DSL.
  * [Rugs At the Bazaar: Open Source @Atomist](https://medium.com/the-composition/rugs-at-the-bazaar-open-source-atomist-6c23de4abe74#.gbpargwux) - Listing and discussion of Rug-related open source projects.
  * [Automating Infrastructure with Atomist](https://medium.com/the-composition/automating-infrastructure-with-atomist-c15262f985ab#.my2iax5ra) - Configure [Travis CI](https://travis-ci.org) for your repo with one click.
  * [Atomist: Meet TypeScript](https://medium.com/the-composition/atomist-meet-typescript-2f2e16251d4f#.6sy4v0zd6) - Introduction of writing Rugs using [TypeScript](https://www.typescriptlang.org/).
  * [Automating Our Development Flow With Atomist](https://medium.com/the-composition/automating-our-development-flow-with-atomist-6b0ec73348b6#.t02n4y28d) - Introduction to automating development flows, e.g., build, test, & deploy, with Rug.
  * [Rugs on the Command Line](https://medium.com/the-composition/rugs-on-the-command-line-eca46492db09#.ogvgfrxvf) - Tutorial for using the [Rug CLI](https://github.com/atomist/rug-cli) to run Rugs.
  * [Upgrading to Spring Boot 1.4.4 with Rug](https://medium.com/the-composition/upgrading-to-spring-boot-1-4-4-with-rug-ba00c62c487e#.eujyp2x16) - Walkthough showing how to create a Rug to upgrade SpringBoot and then use an Executor to apply this across a collection of projects
  * [Write your Rugs in Python](https://medium.com/the-composition/write-your-rugs-in-python-f10d258e0e2b#.ri2eisoft) - Rug authoring in Python using JavaScripthon to transpile to ECMAScript 5 (the Atomist lingua franca)

* [Using Rug with Elm](http://blog.jessitron.com/2016/12/using-rug-with-elm.html) - Using Rugs to automate the language tutorial process, in this case [Elm](http://elm-lang.org/).
* [Today’s Rug: maven executable jar](http://blog.jessitron.com/2017/01/todays-rug-maven-executable-jar.html) - Quick walk through of creating your own Rug editor to solve an infrequent problem once and for all.
* [Evolucionando Código con Rug](http://blog.eddumelendez.me/2017/01/evolucionando-codigo-rug/) - Code that writes code
  * [English Translation](https://translate.google.co.uk/translate?sl=auto&tl=en&js=y&prev=_t&hl=en&ie=UTF-8&u=http%3A%2F%2Fblog.eddumelendez.me%2F2017%2F01%2Fevolucionando-codigo-rug%2F&edit-text=&act=url)

# Community

* [Slack: Atomist Community](https://atomist-community.slack.com/) - Slack for Atomist Community - [![Slack Status](https://join.atomist.com/badge.svg)](https://join.atomist.com/)
  * [Clojure](https://atomist-community.slack.com/messages/rug-clojure/) - Atomist support for Clojure
  * [Elm](https://atomist-community.slack.com/messages/rug-elm/) - Atomist support for Elm
  * [Go](https://atomist-community.slack.com/messages/rug-go/) - Atomist support for Go
  * [Groovy](https://atomist-community.slack.com/messages/rug-groovy/) - Atomist support for Groovy
  * [Python](https://atomist-community.slack.com/messages/rug-python/) - Atomist support for Python
  * [Rust](https://atomist-community.slack.com/messages/rug-rust/) - Atomist support for Rust
  * [Swift](https://atomist-community.slack.com/messages/rug-swift/) - Atomist support for Swift
  * [TypeScript](https://atomist-community.slack.com/messages/typescript/) - Atomist support for TypeScript

* [Join The Atomist Slack Community](https://join.atomist.com/) - Start here if you need to join the Atomist Slack Community
* [This Month in Atomist](this-month-in-atomist) - News and chat snippets curated from various sources including the Atomist Slack channels.
* [Atomist Enthusiasts](https://www.linkedin.com/groups/12014097) - LinkedIn Atomist User Group
* [Atomist StackOverflow](http://stackoverflow.com/search?q=atomist) - Atomist questions on StackOverflow

# Meetups

## United Kingdom
* [Rug RUG, The London Atomist Rug User Group](https://www.meetup.com/Rug-Rug-The-London-Atomist-Rug-User-Group/) - The Original Atomist Meetup

# References

* [Atomist Reference](http://docs.atomist.com/reference-docs/) - Atomist Reference: The Atomist Bot, Atomist Project Template Overview, Authoring Atomist Project Editors and Reviewers with the Atomist DSL, Systems that Atomist Currently Supports.

# Guides

* [Quick Starts](http://docs.atomist.com/quick-starts/) - Atomist Quick Starts

# Code

* [HelloWorld Microservices with Atomist](https://github.com/atomist-bot) - atomist-bot commits linking to HelloWorld Microservice examples using SpringBoot (for now). 
* [Neo4j with Atomist](https://github.com/neo4j-examples/atomist-spring-neo4j) - Example Project demonstrating Atomist Editors for Spring Boot with Neo4j
* [Upgrading to JUnit 5](https://github.com/eddumelendez/rug-demo) - Demo project uses two Rugs to update Maven POMs and Java source code to JUnit 5.

# Videos

* ["The Clockwork Gardener: Growing an Elm App With Templates" by Jessica Kerr](https://youtu.be/jJ4e6cIBgYM?list=PLglJM3BYAMPH2zuz1nbKHQyeawE4SN0Cd) - Jessica Kerr steps through life alongside her PR flinging, code generating buddy Atomist starting with ChatOps and progressing to CLI. 
* [JAX London 2016: Interview with Russ Miles - Rapid overview of Rug](https://youtu.be/S_E77jz0yCg) - 10 minute Rug Language overview with Russ Miles at JAX London 2016. Awesome because convincing case that a _Rug_ can actually tie things together. Maybe.
* [Atomist Bot Demo](https://www.youtube.com/watch?v=B_x43nPoDH4) - 10 minute Atomist Bot demo showing interaction via Slack channel.
 * The Atomist Bot gets authorized via OAuth, shows status, executes a generator prompting for parameters, creates a compojure-service PR on GitHub project.
 * The demo shows how to list generators.
  * Atomist then is instructed to create a SpringBoot project.
  * Atomist lists it's 54 editors, then adds a Docker file to the SpringBoot project.
  
Super cool to see the workflow all within Slack with history.
* [Atomist YouTube Channel](https://www.youtube.com/channel/UCvKTtZtPh_MHkQJuAgvzKOA/videos)
* [Jessica Kerr - Web Programming without Errors, and Coding without Typing](https://youtu.be/yFN8Y0Aoflw) - From CodeMesh 2016

# Presentations

* [Fries and a ChatOps with JackieBigShots](varia/tea-and-a-chatops-with-jackiebigshots/full-atomist-chatops-session.md) - Step by step request and response microservice creation and Dockerization modification from Atomist Slack team.
* [Musical Theatre Style take on Microservice Challenge/Atomist Solution scenarios](https://skillsmatter.com/skillscasts/7870-keynote-making-sense-of-microservices-maximizing-development-productivity-and-minimizing-mistakes) - Great if you missed the Edinburgh Fringe this year. Requires login to SkillsMatter.

# Courses and Tutorials

* [Rug Koans](https://github.com/atomist-rugs/rug-koans-editors/blob/master/koans.md) - Self-directed learning samples using Rug tests to explore and learn Rug and its environment
  * Feedback channel: https://atomist-community.slack.com/messages/rug-koans/details/

# Books

* [Atomist in Action - Manning](https://www.manning.com/books/atomist-in-action) - In anticipation
* [Professional Atomist - Wrox](http://www.wrox.com/WileyCDA/Section/id-WROX_SEARCH_RESULT.html?query=Professional%20Atomist) - In anticipation
* [Learning Atomist - O'Reilly](https://ssearch.oreilly.com/?q=learning+atomist) - In anticipation

# Templates and Editors

* [Atomist Project Templates](https://github.com/atomist-project-templates) - Python, Java and Clojure templates.

## Clojure

* [Simple Lein Project](https://github.com/atomist-project-templates/simple-lein-project) - Clojure project generator & example editor
* [Compojure API Sample](https://github.com/atomist-project-templates/compojure-api-sample) - Clojure Compojure API project generator

## Java

## Python

## Scala

* [AddScalaPom. BringInScalatest](https://github.com/jessitron/scattered-rugs#addscalapom) - Example Rugs related to Scala
  * [Scala Maven Rugs](https://medium.com/@jessitron/scala-maven-rugs-97c8659d6832#.4vpgtw1j6) - Context for the above project

## TypeScript

* [NPM packages by atomist](https://www.npmjs.com/~atomist) - TypeScript model for Atomist editors, generators etc

## Travis CI

* [Atomist Travis Editors](https://github.com/atomist-rugs/travis-editors) -  Rug archive with editors that enable and configure a Travis CI build for a GitHub repository
  * [Automating Travis CI configuration with Atomist](https://medium.com/the-composition/automating-infrastructure-with-atomist-c15262f985ab#.nln6abkee) - Paints a vision of pushing forward the current frontier of infrastructure-as-code automation and illustrates this vision with Travis CI configuration.

## Licencing

* [Atomist Licensing Editors](https://github.com/atomist-rugs/licensing-editors) - Manage licensing and copyright notices with Atomist.  Add licence from selection of 25+ licence templates including AFL-3.0, GPL-3.0, and all the usual suspects

## Resources

* [Atomist in Lauchpad](https://launchpad.net/~atomisthq)

## Tooling

### Editor and IDE plugins, IDE plugins

TODO: If you are reading this and have information please provide an edit to this table

|Name | Status | Description |Further Information and Link
|-----|-------------|--------|----------------------------
|IntelliJ IDEA|-|
|Atom|Pre-release|Mentioned on Slack: https://atomist-community.slack.com/archives/general/p1485340978000655
|Atom|-|An Atom plugin for running Elm Atomist Rugs|https://github.com/mbylstra/elm-atomist-rugs-atom-plugin
|Eclipse|-|
|Emacs|Early Stages|Emacs major mode for the Rug language|https://github.com/atomist/rug-emacs-mode
|VI|-|
|CodeMirror|-|
|Visual Code Studio|-|

## Repository Support

TODO: If you are reading this and have information please provide an edit to this table

|Name | Status | Description |Further Information and Link
|-----|-------------|--------|----------------------------
|GitHub|Generally Available
|GitHub Enterprise|???|
|Bitbucket|Investigating|
|TeamCity|Mentioned on Slack|https://atomist-community.slack.com/archives/announce/p1485342173000135
|GitLab|???
|Team Services|???

### Other Tools

# Misc

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Janek Bogucki](https://twitter.com/janekdb) has waived all copyright and related or neighboring rights to this work.
