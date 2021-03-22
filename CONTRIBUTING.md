# Contributing
Thank you for contributing to Mue! However, there are some things you need to take note of before starting your contribution to the Mue project.

By contributing to Mue, you agree that:
* None of the work submitted is plagiarised
* Your contribution will be distributed under the [BSD-3-Clause License](https://opensource.org/licenses/BSD-3-Clause) after it has been merged or implemented otherwise
* Your contribution follows the [Code of Conduct](CODE_OF_CONDUCT.md)

Below are some hints and tips to follow when developing for Mue to reduce the chances of your pull request being closed or having to change many things.

## Issues
### Bugs
Please don't open issues relating to questions about the project, as it is preferred you contact us via Discord or email instead. When creating an issue,
make sure to fill out all the important information and it is much appreciated if you include GIFs/screenshots along with your instructions and possibly
even insight of how it would be fixed. **Security issues have a specific reporting policy, please see [SECURITY.md](SECURITY.md)**.

### Feature Requests
You can request a feature through our feature request template.

## Pull Requests
### Commits
We use the [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) system for our commit names so they are easy to read. 
Please keep commit count to a minimum if possible. Do not open an entire pull request just to fix one typo, it is preferred you notify us on Discord or email 
instead. See ``README`` for an invite.

### Code
When coding for Mue projects, keep a few things in mind:

* Dependencies - If there's a lighter alternative, use it. Use as few as possible and keep the bundle sizes small so Mue continues to be fast.
* Code-style - Follow the general codestyle of the repository. Look at .editorconfig and eslint for info.
* Errors - Please fix all errors caused by your changes if possible.

#### Features
It's preferred that you implement features from our project boards [here](https://github.com/mue/mue/projects) and [here](https://trello.com/b/w7zhS7Hi). If you want to add something different, feel free to let us know first
on Discord and we can discuss together how it could be implemented along with UI design (we internally use Figma for our design). This is not so important for small
features, but for anything major this is crucial to keeping things consistent with the project goals and preventing duplication of work.

* External APIs - This is only applicable to the portions of Mue that the users see: the tab, website, blog and documentation. Please refrain from requesting to such services
in order to protect user privacy, and if you must, create a proxy implementation that can be deployed either via [Cloudflare Workers](https://workers.dev) or directly in our 
[API](https://github.com/mue/api).
* Removed Features - Usually, a removed feature will have a reason provided on our project board. Please don't add it back again without consulting us first.
* Pull Requests - Screenshots, especially GIFs are appreciated. We'll try to provide you with some as well when giving feedback.

#### Bug Fixes
Feel free to submit any. It would be great if you could include instructions of how the bug was originally triggered, and how you fixed it.

### Translations
Please don't use Google Translate, and do not open pull requests to any in-development branches as strings may change at any moment without notice.
