# CoreCrafted Documentation
The official documentation for the CoreCrafted Network, created as a starting point for new players

## Contributing
The documentation site in production is an implementation of the latest commit in the `master` branch (namely production branch). Therefore, the content is exptected to be accurate, complete and flawless. However, there are always a possibility that something went wrong with the keyboard, computer, or ~~even brain of the contributor~~(I mean.. wordings), or there is something important missing in the documentation site. In case you discover any problems, you could consider **contributing** to the the page

> Our docs utilizes [Grav](https://getgrav.org/), an open source flat-file CMS to deliver you with the nice layout of handbook. If you desire to contribute, please be sure to check out the [Grav Official Documentation](https://learn.getgrav.org/) to learn more about Grav itself.

### Dos and Don'ts while contributing
#### Dos
* Make sure every changes you made is important and essential. *We don't want to have load of PRs(pull request) that are just about replacing "a" into "the"*
* Check if the modified content is accurate and factual. If you have unsure statements, do not post them, consult our staff before doing so.
* Keep your changes clean and minimal, and only change those that helps the most. *Wordings and grammatical mistake corrections please create a separate PR to avoid massive amount of conflicts*
* Be patient when waiting for reply from PRs.
* Add a description to your pull request, so that we know what you are working on and avoid excessive and repetitive working
* Contribute by forking the repository and making pull requests as long as you could. If you have difficulties with learning and using Git and GitHub, you could report problems to me directly. *(expect slow response and even being ignored if you use the later one)*
* Use formal tone (passive voice) for formal contents

#### Don'ts
* Making false / unsure modifications in the documentation (e.g. changing the owners to someone else)
* Making Pull Requests on a single minor issue. (If you spot some minor issues, please group them up and fix them all at once in a single PR)

### Branching
We uses [Git Flow](https://github.com/nvie/gitflow) to operate the repository. For more information on Git Flow, please click [here](http://nvie.com/posts/a-successful-git-branching-model/)
* **master** -> The main production branch. Content in this branch is the exact same as the one you see at our docs site
* **develop** -> The main development branch. Everything changes are made and merged into this branch before putting into master branch for production
* **feature/** branches -> Used for creating new features(i.e. new pages/category)
* **hotfixes/** -> Used for making quick fix commit as patches to content in production

## Translating
The translation mechanism of the handbook is just about creating an additional file in different but exact same format. The guideline on how to translate the documentation properly will be posted later