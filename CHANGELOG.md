## Version 0.4.2
- Comparison fails at times [#293](https://github.com/DonJayamanne/gitHistoryVSCode/issues/293), [#291](https://github.com/DonJayamanne/gitHistoryVSCode/issues/291), [#290](https://github.com/DonJayamanne/gitHistoryVSCode/issues/290)
- Unable to view history when `Author` name is empty [#294](https://github.com/DonJayamanne/gitHistoryVSCode/issues/294)

## Version 0.4.1
- Use new VS Code API to display the Git Log (with better performance) [#265](https://github.com/DonJayamanne/gitHistoryVSCode/issues/265)
- Remove duplicate command from `package.json` [#263](https://github.com/DonJayamanne/gitHistoryVSCode/issues/263)
- Add exception handler when attempting to determine the `origin` remote [#253](https://github.com/DonJayamanne/gitHistoryVSCode/issues/253)
- Ignore empty items when retrieving list of refs containing a particular commit [#248](https://github.com/DonJayamanne/gitHistoryVSCode/issues/248)
- Add merge and rebase commands to history view [#247](https://github.com/DonJayamanne/gitHistoryVSCode/pull/247)
- Add support for multiple git repositories in a workspace [#233](https://github.com/DonJayamanne/gitHistoryVSCode/issues/233)
- Add support for sub directories and multiple workspaces with git repositories [#2226](https://github.com/DonJayamanne/gitHistoryVSCode/issues/226)

## Version 0.4.0
- Fix display of random avatars [#230](https://github.com/DonJayamanne/gitHistoryVSCode/pull/230), [#229](https://github.com/DonJayamanne/gitHistoryVSCode/pull/229), [#228](https://github.com/DonJayamanne/gitHistoryVSCode/pull/228), [#227](https://github.com/DonJayamanne/gitHistoryVSCode/pull/227)

## Version 0.3.9
- Display github gravatars [#220](https://github.com/DonJayamanne/gitHistoryVSCode/pull/220)
- Add ability to revert a commit [#221](https://github.com/DonJayamanne/gitHistoryVSCode/pull/221)
- Restore ability to view line history [#185](https://github.com/DonJayamanne/gitHistoryVSCode/issues/185)

## Version 0.3.8
- Ability to hide the icon in the editor titlebar [#186](https://github.com/DonJayamanne/gitHistoryVSCode/issues/186)
- File viewer fixes [#216](https://github.com/DonJayamanne/gitHistoryVSCode/issues/216)

## Version 0.3.7
- Support viewing and comparing binary files [#215](https://github.com/DonJayamanne/gitHistoryVSCode/issues/215), [#211](https://github.com/DonJayamanne/gitHistoryVSCode/issues/211)
- Fixes to viewing of files [#211](https://github.com/DonJayamanne/gitHistoryVSCode/issues/211)
- Remove unwanted commands [#206](https://github.com/DonJayamanne/gitHistoryVSCode/issues/212)

## Version 0.3.6
- Fix issue with spaces in path to git executable [#200](https://github.com/DonJayamanne/gitHistoryVSCode/issues/200)
- Support for unicode characters [#206](https://github.com/DonJayamanne/gitHistoryVSCode/issues/206)

## Version 0.3.5
- Added ability to select branch from within history view [#202](https://github.com/DonJayamanne/gitHistoryVSCode/pull/202)
- Swap the display of comparison views [#197](https://github.com/DonJayamanne/gitHistoryVSCode/issues/197)
- Fix parsing of file statys (causing files with numbers to be truncated) [#200](https://github.com/DonJayamanne/gitHistoryVSCode/issues/200)

## Version 0.3.4
- Disabled calculation of total number of commits as this was slowing down viewing of history [#195](https://github.com/DonJayamanne/gitHistoryVSCode/issues/195)
- Fix styles in comment message [#196](https://github.com/DonJayamanne/gitHistoryVSCode/issues/196)

## Version 0.3.3
- Remove unused command and keybinding [#188](https://github.com/DonJayamanne/gitHistoryVSCode/issues/188)
- Display latest commit history and ability to refresh the history view [#193](https://github.com/DonJayamanne/gitHistoryVSCode/issues/193)
- Fix inability to view file contents and differences on Windows [#189](https://github.com/DonJayamanne/gitHistoryVSCode/issues/189), [#182](https://github.com/DonJayamanne/gitHistoryVSCode/issues/182), [#191](https://github.com/DonJayamanne/gitHistoryVSCode/issues/191)
- Style changes and re-display commit graph when search is text is cleared [#183](https://github.com/DonJayamanne/gitHistoryVSCode/issues/183)

## Version 0.3.2
- Display message if a workspace is not open

## Version 0.3.1
- Patch for windows

## Version 0.3.0
- Improvements to the graph
- Ability to search from within the history viewer
- Display history viewer when viewing history of files
- Miscellaneous fixes

## Version 0.2.3
- Ability to view commit information in explorer view
- Ability to compare commits
- Ability to view log of all branches [#144](https://github.com/DonJayamanne/gitHistoryVSCode/pull/144), [#93](https://github.com/DonJayamanne/gitHistoryVSCode/issues/93), [#129](https://github.com/DonJayamanne/gitHistoryVSCode/issues/129)

## Version 0.2.2
- Viewing the history by branch [#140](https://github.com/DonJayamanne/gitHistoryVSCode/pull/140)
- Cherry picking commits [#141](https://github.com/DonJayamanne/gitHistoryVSCode/pull/141)
- Handle branch names containing periods [#133](https://github.com/DonJayamanne/gitHistoryVSCode/pull/136)

## Version 0.2.1
- display ref tags in history when using "git log"
- fixed visual feedback when SHA is copied in "git log"
- Allow scenario where git repo root is not the vscode workspace root [#112](https://github.com/DonJayamanne/gitHistoryVSCode/pull/112)
- fix error when git config log.abbrevcommit=true [#132](https://github.com/DonJayamanne/gitHistoryVSCode/pull/132)
- added a maximize/restore button to the details-view [#118](added a maximize/restore button to the details-view)

## Version 0.2.0
- Move to Async programing pattern (internal)
- Add logging and better error surfacing  - output windows 'Git History Log'
- Add a separate output window for non logging display 'Git History Info'
- Fix #43 #63 - error when file in not present in a commit
- File actions pick list - only show applicable actions
e.g. don't show compare with previous if file not present in previous commit.
- Improve readability of picklist for commits of a file (2 line display)
- Improve gitPath logic and performance.
- Make git log default page size 50 for performance.

## Version 0.1.5
* Fix HTML chars in filenames [#53](https://github.com/DonJayamanne/gitHistoryVSCode/pull/53)
* Fix git log above repo root (Credit to [malytskyy](https://github.com/malytskyy)) [#77](https://github.com/DonJayamanne/gitHistoryVSCode/pull/77)
* Rename outChannel to 'Git History' [#83](https://github.com/DonJayamanne/gitHistoryVSCode/pull/83)
* Don't use incorrectly configured git.path [#78](https://github.com/DonJayamanne/gitHistoryVSCode/pull/78) and [#46](https://github.com/DonJayamanne/gitHistoryVSCode/pull/46)
* Add error handling for spawned processes (Credit to [SE2Dev](https://github.com/SE2Dev)) [#46](https://github.com/DonJayamanne/gitHistoryVSCode/pull/46)
* tmp file cleanup.  There is a lot of effort to manually cleanup when tmp does it all anyway. [#88](https://github.com/DonJayamanne/gitHistoryVSCode/pull/88)
* Update typescript to 2.1 and update to ES6 target (allowing async await in place of .then) [#81](https://github.com/DonJayamanne/gitHistoryVSCode/pull/81)

## Version 0.1.4
* Fix git log paging [#74](https://github.com/DonJayamanne/gitHistoryVSCode/pull/74)

## Version 0.1.3
* Clean up [#70](https://github.com/DonJayamanne/gitHistoryVSCode/pull/70)

## Version 0.1.2
* Underlining file history details link on hover [#48](https://github.com/DonJayamanne/gitHistoryVSCode/issues/48), [#54](https://github.com/DonJayamanne/gitHistoryVSCode/issues/54)

## Version 0.1.1
* Fixed styling of file history details [#48](https://github.com/DonJayamanne/gitHistoryVSCode/issues/48), [#54](https://github.com/DonJayamanne/gitHistoryVSCode/issues/54)
* Updated to TypeScript 2.0 [#68](https://github.com/DonJayamanne/gitHistoryVSCode/pull/68)
* Date format was always displayed in en-US [#69](https://github.com/DonJayamanne/gitHistoryVSCode/issues/69)
* Comparing large files would display incorrect information [#56](https://github.com/DonJayamanne/gitHistoryVSCode/issues/56)
* Compilation issue [#60](https://github.com/DonJayamanne/gitHistoryVSCode/issues/60)

## Version 0.1.0
* Viewing individual file commit details in commit list [#44](https://github.com/DonJayamanne/gitHistoryVSCode/issues/44)

## Version 0.0.12
* Improved look and feel [#35](https://github.com/DonJayamanne/gitHistoryVSCode/pull/35)

## Version 0.0.11
* Bug fix to deleted temporary files [#32](https://github.com/DonJayamanne/gitHistoryVSCode/issues/32)
* Fix to restore following changes to file names [#26](https://github.com/DonJayamanne/gitHistoryVSCode/issues/26)

## Version 0.0.10
* Bug fix to remove debug code [#29](https://github.com/DonJayamanne/gitHistoryVSCode/issues/29)

## Version 0.0.9
* Added new feature to view git history with graphs and details

## Version 0.0.8
* Fix for issue [#27](https://github.com/DonJayamanne/gitHistoryVSCode/issues/27)

## Version 0.0.7
* Updated to make use of VS Code API for file comparison
* Added ability to view file history from explorer context menu
* Fixed issue where history is reversed [#15](https://github.com/DonJayamanne/gitHistoryVSCode/pull/15)

## Version 0.0.5
* Added custom commands for file and line history, allowing the ability to add keyboard shortcuts
* Remove the old command and replaced it with two separate commands
* Ensured the commands are available only when a text editor is active

## Version 0.0.4
* Improvements in detecting path to git
* Bug fix when viewing history of file in workspace (root) directory

## Version 0.0.3
* Read path to GIT from VSCode configuration
* Configure the information displayed in picklist

## Version 0.0.1
* Initial release
