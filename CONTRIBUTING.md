# Contributing to Flilia
We would love you to contribute to Flilia and help make it even better than it is today! As a contributor, here are guidelines we would like you to follow:

- [Question or Problem?](#question)
- [Found a Bug?](#bug)
- [Have an idea?](#idea)
- [Submission Guidelines](#submit)
- [Commit Message Guidelines](#commit)

## Got a Question or Problem?
- If your question not related to development, please contact a project manager by email or Teams.
- If your question related to development and project source code, feel free to start discussion and ask any questions in [Developers team][developers-team].
- If your question related to development but not with project source code, we recommend using [Stack Overflow][stackoverflow] to ask support-related questions.
	```
	Stack Overflow is a much better place to ask questions since:
	- there are thousands of people willing to help on Stack Overflow
	- questions and answers stay available for public viewing so your question/answer might help someone else
	- Stack Overflow's voting system assures that the best answers are prominently visible.
	```
- If you would like to chat about the question in real-time, you can reach out via our Flilia team in Microsoft Teams.

## <a name="bug"></a> Found a Bug?
If you find a bug in the source code, you can help us by [submitting an bug][azurebug] to our [project management tool][azureflilia]. Even better, you can submit a Pull Request with a fix.

## <a name="idea"></a> Have an idea?
If you have an idea or new feature, feel free to discuss it with us. Contact a project manager or team lead for further details.

Be sure that your idea coincides with the activity of the product and will be useful in the future for users of our service.

## <a name="submit"></a> Submission Guidelines

#### Submitting a Pull Request (PR)
1. Make your changes in a new git branch:
     ```shell
     git checkout -b my-fix-branch master
     ```
2. Commit your changes using a descriptive commit message that follows our [commit message conventions](#commit): 
     ```shell
     git commit -m "Fix: Remove dublicates in css (AB#526)"
     ```
3. Push your branch to GitHub:
     ```shell
     git push origin my-fix-branch
     ```

#### Once your pull request is merged
Once your pull request is merged, you can safely delete your branch and pull the changes from the main (upstream) repository:

1. Delete the remote branch on GitHub either through the GitHub web UI or your local shell as follows:
     ```shell
     git push origin --delete my-fix-branch
     ```
2. Check out the master branch:
     ```shell
     git checkout master
     ```
3. Delete the local branch:
     ```shell
     git branch -D my-fix-branch
     ```

## <a name="commit"></a> Commit message format
We have very precise rules over how our Git commit messages must be formatted. This format leads to easier to read commit history.

Each commit message consists of header and body.
```shell
<header>
<BLANK LINE>
<body>
```

The `header` is mandatory and must conform to the [Commit Message Header format](#commitMessageHeaderFormat).

The `body` is mandatory for all commits except for those of type "docs". When the body is present it must be at least 20 characters long and must conform to the [Commit Message Body format](#commitMessageBodyFormat).

Any line of the commit message cannot be longer than 100 characters.

#### <a name="commitMessageHeaderFormat"></a> Commit Message Header
```html
Example: <Fix: Remove dublicates in css (AB#526)>

<Type>: <Summary> (<Scope>)
   │        │         |
   │        |         └─⫸ Scope is requiered if changes is related to Azure DevOps tasks: (AB#526)
   |        |
   │        └─⫸ Summary in present tense. Capitalized. No dot at the end.
   │
   └─⫸ Commit Type: Build|CI|Docs|Feat|Fix|Perf|Refactor|Test
```

The `<Type>` and `<Summary>` fields are mandatory, `(<Scope>)` field is optional.

`<Type>` - must be one of the following:
- Build: Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)
- CI: Changes to our CI configuration files and scripts (example scopes: Circle, BrowserStack, SauceLabs)
- Docs: Documentation only changes
- Feat: A new feature
- Fix: A bug fix
- Perf: A code change that improves performance
- Refactor: A code change that neither fixes a bug nor adds a feature
- Test: Adding missing tests or correcting existing tests

`<Summary>` - use the summary field to provide a succinct description of the change:
- use the imperative, present tense: "change" not "changed" nor "changes"
- Capitalize the first letter
- no dot (.) at the end

`(<Scope>)` - if the changes related to tasks from Azure DevOps, `<Scope>` field is required:
- add the ID of related task from Azure DevOps: (AB#526)
- optionally add related pull requests ID if exist: (#242)
- separate many relations with commas: (AB#526, #242)

#### <a name="commitMessageBodyFormat"></a> Commit message body
Just as in the summary, use the imperative, present tense: "fix" not "fixed" nor "fixes".

Explain the motivation for the change in the commit message body. This commit message should explain why you are making the change. You can include a comparison of the previous behavior with the new behavior in order to illustrate the impact of the change.

#### Revert commits
If the commit reverts a previous commit, it should begin with `Revert:` , followed by the header of the reverted commit.

The content of the commit message body should contain:

- information about the SHA of the commit being reverted in the following format: This reverts commit `<SHA>`,
- a clear description of the reason for reverting the commit message.

## <a name="guidance"></a> Related documentation and guidance
This guides will help you get started with installing and setting up the languages and tools you need to develop on Windows or Windows Subsystem for Linux:

- [Azure DevOps Server][azure] is a Microsoft product that provides version control, reporting, requirements management, project management, automated builds, testing and release management capabilities.

[developers-team]: https://github.com/orgs/flilia/teams/developers-team
[azure]: https://azure.microsoft.com/en-us/services/devops/
[stackoverflow]: http://stackoverflow.com/
[azurebug]: https://docs.microsoft.com/en-us/azure/devops/boards/backlogs/manage-bugs?view=azure-devops&tabs=new-web-form
[azureflilia]: https://dev.azure.com/flilia/Flilia
