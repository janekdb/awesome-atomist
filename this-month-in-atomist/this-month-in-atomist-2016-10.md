
# This Month In Atomist - 2016 October

## News from the [Atomist Slack channels](https://atomist-community.slack.com)

### Less Privilege

The Atomist team decided to reduce the default scope down to public_repo only. when requesting permissions for the atomist-bot.
Previously permissions were required for private repos. This has made several people quite happy.

### GitHub Integrations

The Atomist team is busy working on support for a recent GitHub feature called integrations:  https://developer.github.com/early-access/integrations/

To quote Jim Clark

> Integrations provide GitHub owners with a lot more control over granting access rights than the OAuth application.  They are also particularly interesting because:

> 1.  they can be "installed" into single GitHub organizations.  Contrast this with an Oauth app that always runs as a particular user.  Integrations run as the integration.  :slightly_smiling_face:

> 2.  since the integration has it's own identity, it appears as it's own bot-style "user".  A PR from an Atomist integration appears to come from ... Atomist.  

> 3.  integrations do NOT take up a license seat in a paid GitHub account.  Contrast this with inviting an external collaborator!  GitHub is providing a great way to charge only for your human collaborators :slightly_smiling_face:
 
### CLI on the way

Additional workflows are being catered for. To quote David Dooling

> The flow for creating and publishing editors/generators is part of the command-line interface which we will be releasing soon. 

### JavaScript Editors Shimmering on the Horizon

[Rug Lang](https://atomist-community.slack.com/messages/rug-lang) saw a flurry of suggestions for approaches to parsing JavaScript as this next language starts to attract the attention of the Atomist team. SNOBOL anyone?

### Clojure Interest

James Carnegie continued to push forward the level of Atomist support for Clojure with a elevated level of ambition,

> Hey all. I've started working on some more Clojure support in rug! Previously I published a generator for a very opinionated project (https://github.com/atomist-project-templates/compojure-api-sample), so now I'm looking at how we can build up useful clojure projects based on a minimal base project, then using editors to add/change stuff. Here's a start: https://github.com/atomist-project-templates/simple-lein-project

The conversation continues on https://atomist-community.slack.com/messages/rug-clojure

### Python Ripples

In an interesting dialog Omer, Sylvain and others start to position Atomist within the existing set of Python toolings. Themes include how Atomist is different, how it overlaps and what workflows make sense. This raises an interesting question: Which language is tooling-poor in the areas addressed by Atomist?
