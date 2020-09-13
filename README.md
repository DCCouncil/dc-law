# DC-Law

## Introduction

DC-Law is a project by the Council of the District of Columbia to put DC Code online. This project grew out of the dccode.org/simple project.

We have several goals, some of which have never been accomplished anywhere before:

1. Zero Errors - we are developing tools and processes to catch errors before they are published.
1. Up-to-date - The tools will let us update the code in days, rather than months.
1. Machine Readable - we will publish the code in an xml format with consistent, semantic metadata.
1. Easy to Use - we will publish a website where people can easily read and interact with the code.

To reach these goals we must accomplish the following general tasks:

- [x] Create an xml schema to represent the code
- [x] Convert the existing code from word to xml
- [ ] Eliminate errors in the xml (in progress)
- [ ] extract computer-readable data from the narrative DCCode annotations written by lawyers/paralegals (in progress)
- [ ] Create a Statute Parser (in progress)
- [ ] Create tools to codify a statute based on the parsed statute text and extracted metadata.
- [ ] Improve the html view of the laws
- [ ] Create beautiful pdfs of the laws

Right now we are looking for help extracting computer-readable data from the DCCode annotations. If you are interested in helping, check out the [issues](https://github.com/DCCouncil/dc-law/issues).

## Repositories
This is the main repository for the project,
where you will find documentation and issue tracker.
The other repositories are:

* `https://github.com/DCCouncil/dc-law-tools` - the build scripts used to create, manipulate and edit the laws (archived).
* `https://github.com/DCCouncil/dc-law-xml` - the home of the laws in xml.
* `https://github.com/DCCouncil/dc-law-html` - the home of the laws in html.

## Contributing
* `dc-law-html` is generated from dc-law-xml. Do not make manual commits
* `dc-law-xml` PRs should be broken into enough commits that GitHubs diff can show each commit in full (max 1k files each). Commits should be squashed and merged with a message in the following form:
 * "codify: xx-xxx" to codify a law
 * "recodify: ..." to make codification changes separate from a bill
 * "technical: ..." for technical corrections
 * "system: ..." for changes to the xml necessary for build-system improvements

## License
All repositories are licensed under [CC0](https://creativecommons.org/publicdomain/zero/1.0/).

The CC0 license is not "Viral." If you wish to contribute, it is therefore necessary for you to explicitly license your pull request under the CC0 License. You can do that by either:

1. Licensing all your contributions by following the instructions in [Issue 1](https://github.com/DCCouncil/dc-law/issues/1), or
1. Including the following text in each pull request: `I, <name>, license this pull request under the CC0 license.`

