<!--
Customize this by replacing PLACEHOLDER with your information.
Examples will be given for easy copy-pasting.
Use Ctrl + F (Windows) to highlight all the PLACEHOLDER that need to be replaced.
Delete the hidden comments like this as you go.
Good luck!
-->
<!-- Liu Yongliang - IWM@NUS-OSS Progress Report -->
# Liu Yongliang - IWM@NUS-OSS Progress Report

<!-- 
## Project Information
- Period of work: Aug-Nov 2021
- Module: CP3108A
- Project: MarkBind
-->
## Project Information
- Period of work: Aug-Nov 2021
- Module: CP3108A
- Project: MarkBind

# Weekly Progress
<!--
## Week 1 (9 Aug 2021)
- Investigated issues #123 (Page not loading properly)
- Tried a possible solution given in this S/O post, but it did not work because ...
- Created PR #456 (Fix integer overflow bug)
- Updated PR #973 (...) based on reviews
- Merged PR #879 (...)
## Week 2 (16 Aug 2021)
- Investigated issues #123 (Page not loading properly)
- Tried a possible solution given in this S/O post, but it did not work because ...
- Created PR #456 (Fix integer overflow bug)
- Updated PR #973 (...) based on reviews
- Merged PR #879 (...)
-->
## Week 0
- Created issues with regards to User Guide hyperlink not working:
  - [MarkBind/markbind#1339](https://github.com/MarkBind/markbind/issues/1339)
  - [MarkBind/markbind#1528](https://github.com/MarkBind/markbind/issues/1528)
- Discussed line ending issues of different OS for development:
  - [MarkBind/markbind#1640](https://github.com/MarkBind/markbind/issues/1640)
- Setup and get acquainted with MarkBind by
  - [forking the repository](https://github.com/tlylt/markbind), and
  - creating two experimental PRs:
    - [Update devGuide setting up section](https://github.com/tlylt/markbind/pull/1) 
    - [Include unit tests for default plugins](https://github.com/tlylt/markbind/pull/2)
- Created an issue based on inconsistent test results:
  - [Functional tests failed to run properly when executing npm run test in packages/cli](https://github.com/MarkBind/markbind/issues/1641)
- Investigated issue [Unnecessary files in test site folder](https://github.com/MarkBind/markbind/issues/792):
  - Rasied a follow-up issue [Add/fix documentation for usage of open bugs page under test/functional/test_site/bugs](https://github.com/MarkBind/markbind/issues/1644) for discussion.
## Week 1 (9 Aug 2021)
- Raised an issue on the upgrade of commander.js version to improve code quality:
  - [MarkBind/markbind#1648](https://github.com/MarkBind/markbind/issues/1648) 
- Merged PR to fix package level test running issues
  - [MarkBind/markbind#1645](https://github.com/MarkBind/markbind/pull/1645)
- Investigated the pros and cons of separating commands in `packages/cli/index.js` into separate files for better organization and decided to delay that at this moment.
  - Checked with the community using Commander.js via [tj/commanderjs](https://github.com/tj/commander.js/issues/1581). I think this is a low priority refactor that may be useful in future updates. Currently an added layer of abstraction may not be that desirable.

## Week 2 (16 Aug 2021)
- Raised PR [Update linebreak-style settings](https://github.com/MarkBind/markbind/pull/1653) to address line ending issues.
- Investigated issue [MarkBind/markbind#1571](https://github.com/MarkBind/markbind/issues/1571):
  - It is reported that "A search bar without enabling search results in a blank page.", However, after some investigation, I was unable to reproduce the error. I have also noticed that the `enableSearch` variable is set to true, by default. This is the same for both templates that MarkBind offers at the moment(default and minimal).
  - I have followed up with OP to see if there are further actions required.
- Investigated issue [MarkBind/markbind#416](https://github.com/MarkBind/markbind/issues/416):
  - It is reported that "Build console progress bar doesn't show when using 'gitbash on Windows' terminals". I have tested on various console (cmd, bash, within/out of vscode) and could not reproduce the error. The progress bar is working as expected. A side note is that the suspected bug that was previously causing this reported issue has a quick patch that can be applied if this reported issue is still valid. If the issue stems from the `node-progress` package that MarkBind is using, the reported bug in the `node-progress` package is unlikely to be fixed (though a fix PR has been submitted) as it seemed to be unmaintained.
  - Created a patch [PR](https://github.com/MarkBind/markbind/pull/1654)
## Week 3 (23 Aug 2021)
- Raised PR [Fix bug-report issue template file path](https://github.com/MarkBind/markbind/pull/1658) to fix an issue with outdated information in the issue template.
- Raised PR [Update workflow docs](https://github.com/MarkBind/markbind/pull/1659) to update the developer guide on how to manage dependencies.
- Investigated an [issue](https://github.com/MarkBind/markbind/issues/1646) on keeping track of contributors to the MarkBind project so far.
  - Listed out pros and cons of all-contributors and a less powerful alternative.
## Week 4 (30 Aug 2021)
- Updated PR [patch node-progress](https://github.com/MarkBind/markbind/pull/1654) to resolve issues with the display of progress bar on MinTTY terminals.
- Looked further into the [issue of adding contributors](https://github.com/MarkBind/markbind/issues/1646):
  - More research done on how other developers use all-contributors bot and the pros and cons of automating it.
  - Listed out action items to move this suggestion forward.
- Raised PR [Add contributors](https://github.com/MarkBind/markbind/pull/1662) to setup required files for all-contributors integration.

## Week 5 (6 Sep 2021)
- Looked into the bug report [Use of optional chaining operator](https://github.com/MarkBind/markbind/issues/1664) and explained to the questioner that it might be due to issues with outdated Eslint package.

## Week 6 (13 Sep 2021)
- Investigated feature request: [Give easy ways to add different types of horizontal lines](https://github.com/MarkBind/markbind/issues/897)
  - Researching relevant markdown-it plugins and figuring out how to add a customized markdown rule

## Week 7 (20 Sep 2021)

## Week 8 (27 Sep 2021)

# Summary Of Achievements
<!--
## Overview:
- [PRs authored by me](https://github.com/MarkBind/markbind/pulls/tlylt)
- [Issues created by me](https://github.com/MarkBind/markbind/issues/created_by/tlylt)
-->
## Overview:
- [PRs authored by me](https://github.com/MarkBind/markbind/pulls/tlylt)
- [Issues created by me](https://github.com/MarkBind/markbind/issues/created_by/tlylt)

## Breakdown:
### PRs merged
- PLACEHOLDER
### PRs reviewed
- PLACEHOLDER
### Issues raised
- PLACEHOLDER
