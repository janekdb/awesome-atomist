# This Month In Atomist - 2016 December

## News from the [Atomist Slack channels](https://atomist-community.slack.com)

### Kubernetes editor in development

Work continues on the K8 editor: https://github.com/atomist/rug/pull/15

### Using rug-cli with Proxies

https://atomist-community.slack.com/messages/rug-cli/ saw discussions around using Artifactory as a proxy to Central by configuring `cli.yml`

### Atomism of the day: Are you crazy?

![Atomism of the day](images/atomism-of-the-day-2.png)

https://atomist-community.slack.com/archives/rug-elm/p1480925068000002

### .NET

Afif enquired about support for .NET. A parallel was drawn with support for Elm with the caveat that parsing of .NET assemblies lies in the future via microgrammer support.

https://atomist-community.slack.com/archives/general/p1481528235000042

### Scala 2.12.1 - Not just yet

Atomist briefly adopted Scala 2.12.1 and then reverted following unantipicated consequences.

Upgraded to Scala 2.12.1: https://github.com/atomist/rug-compiler/commit/9b648ed435543fdf4cd7bc5554a097c7d2375ea0
Downgraded to Scala 2.11.8: https://github.com/atomist/rug-compiler/commit/eb2704d9724a333a57719e2574c97801ab9a55cd

### Testing Multiple Edits

Discussion picked up around testing the outcome of applying an editor twice with one proposed use being idempotence: https://atomist-community.slack.com/archives/general/p1481898858000067

Jessica is working on Atomist Rug idempotence for Elm: https://twitter.com/jessitron/status/809812239582642176

### Not My Assertion

Rug assertions can now have a negative sense. For example,

```
editor Baby

precondition No

with elm.module e
  do updateImport from "Carrot" to "Kiwifruit"

predicate No

with project p
  when not fileExists "Banana.elm"
 ```
 ### Python Buildout
 
 Godefroid sparked some interest in a Rug for Python Buildout: https://atomist-community.slack.com/archives/general/p1482492008000129
