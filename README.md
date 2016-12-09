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
9. [Courses](#courses)
10. [Books](#books)
11. [Templates and Editors](#templates-and-editors)
12. [Tooling](#tooling)
13. [Resources](#resources)
14. [Misc](#misc)

# Articles

* [Introduction to Atomist Editors](https://medium.com/the-composition/software-that-writes-and-evolves-software-953578a6fc36#.abvq9g980) - The fundamental differentiation provided by Atomist over previous project generation approaches.
* [Evolving Projects Using Atomist Editors](https://medium.com/the-composition/evolving-projects-using-atomist-editors-fd3b1f057c86#.7i0nx3env) - Continuing the series started in *Introduction to Atomist Editors* this post steps through the mechanics of creating a Spring Boot project with one editor action and then running a second editor to bring in Neo. The article also dives down into the structure of Rug types which are used to create new Atomist editors.
* [Updating Multiple Projects using Atomist Executors] (https://medium.com/the-composition/understand-automate-collaborate-1b5695ecb724#.8ffgnmr1n)
* [BDD with Rug](https://medium.com/the-composition/bdd-with-rug-371e85d7a1a9#.p2feulni0) - This soup to nuts account of the process to create a new editor with test scenarios introduces the use the Rug Test DSL.
* [Using Rug with Elm](http://blog.jessitron.com/2016/12/using-rug-with-elm.html) - Using Rugs to automate the language tutorial process, in this case [Elm](http://elm-lang.org/).

# Community

* [Slack: Atomist Community](https://atomist-community.slack.com/) - Slack for Atomist Community
* [Join The Atomist Slack Community](https://join.atomist.com/) - Start here if you need to join the Atomist Slack Community
* [This Month in Atomist](this-month-in-atomist) - News and chat snippets curated from various sources including the Atomist Slack channels.

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

# Courses

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

## TypeScript

* [NPM packages by atomist](https://www.npmjs.com/~atomist) - TypeScript model for Atomist editors, generators etc

## Travis CI

* [Atomist Travis Editors](https://github.com/atomist-rugs/travis-editors) -  Rug archive with editors that enable and configure a Travis CI build for a GitHub repository

## Licencing

* [Atomist Licensing Editors](https://github.com/atomist-rugs/licensing-editors) - Manage licensing and copyright notices with Atomist.  Add licence from selection of 25+ licence templates including AFL-3.0, GPL-3.0, and all the usual suspects

## Resources

* [Atomist in Lauchpad](https://launchpad.net/~atomisthq)

## Tooling

Editor plugins, IDE plugins and the like.

# Misc

---

## License

[![CC0](http://i.creativecommons.org/p/zero/1.0/88x31.png)](http://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Janek Bogucki](https://twitter.com/janekdb) has waived all copyright and related or neighboring rights to this work.
