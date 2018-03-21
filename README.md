# Tip-of-the-day
This contains a list of various "Tips of the day" shared by me in the #git_github channel during my Udacity Android Basics Scholarship course. The tips have been organised day wise, new tips would be added everyday.

## Clone Almost Anything(14-03-2018)

There are many interesting projects available from GitHub and other public Git repositories that you can clone freely to your own computer. Why would you want to do that? One reason is to learn something about coding style, practice, and tools in a language of interest, including commit log commenting style. A second reason is to learn how a given project accomplishes its goals. A third reason, should the licensing both permit you to do so and make sense for your purposes, would be to incorporate the project into your own endeavor or product. Double-check the license, by the way, so that you don't run into compliance issues later on.


## Commit Early and Often(15-03-2018)

A commit is a granular update to a project, which includes one or more changes to one or more files. Think of it as a record of a unit of work completed, which can be applied to or removed from the project as a logical whole. Do commit every logical change you complete, even before testing it. Commits only apply to your local repository.


## Use gists to share snippets(16-03-2018)

GitHub "gists" (shared code snippets) are not a Git feature, but they use Git. All gists are Git repositories, andGitHub Gist makes it easy to share them. You can search Gist for public gists by topic, programming language, forked status, and starred status. You can also create secret gists and share them by URL.


## Forking a repository(17-03-2018)

Forking a repository means creating your own writable server copy of a repo. Recall that we clone a repo to make our own client copy of it. If it's a public repo for which we do not have commit privileges, then the easiest way to contribute our changes is to first commit them to our own fork of the repo on the server via the fork button on the original GitHub project. Then we can issue a pull request to the owners of the forked repo so that they can test and possibly use our contribution. I know, it's confusing at first,:sweat_smile: but it gets easier. :blush:


## Reverting a commit(18-03-2018)

You can revert a commit to undo the last saved work on your branch.
When you revert to a previous commit, the revert is also a commit. The original commit also remains in the repository's history.
Also, when you revert multiple commits, it's best to revert in order from newest to oldest. If you revert commits in a different order, you may see merge conflicts.

## The Blame Game(19-03-2018)

A terrible name, but a terribly useful feature. Use it to find the list of changes in a file and who made them. Click the Blame button in the upper-right tab list to quickly find out who last worked on the file. Or, type
```Git blame [filename]```
at the command line.


## Adding a new file to the repo(20-03-2018)

- On your computer, move the file you'd like to upload to GitHub into the local directory that was created when you cloned the repository.
- Open Terminal
- Change the current working directory to your local repository.
- Stage the file for commit to your local repository.(_git add_)
- Commit the file that you've staged in your local repository.(_git commit -m "add existing file"_)
- Push the changes in your local repository to GitHub. (_git push origin **_your-branch_**_)


## GitHub Pages(21-03-2018)

GitHub Pages are public webpages hosted and easily published through GitHub. The quickest way to get up and running is by using the Jekyll Theme Chooser to load a pre-made theme. You can then modify your GitHub Pages’ content and style remotely via the web or locally on your computer.
