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


## Follow a Friend(22-03-2018)

One of the great features on GitHub is the ability to see what other people are working on and who they are connecting with. When you follow someone, you’ll get notifications about their GitHub activity. Following friends helps you find new projects and new people that you may share interests with.


## Git Reflog(23-03-2018)

Git reflog allows you to see every step you have made with git allowing you to retract and reinstate your steps. Use `git reflog`


## Quick!! I need my pic(24-03-2018)

If you ever need quick access to your profile picture, you can access it at github.com/[profilename].png


## Watch Projects(25-03-2018)

When you fork a project, you'll most likely want to know what's happening in the upstream project. If so, watch the repo. If the update chatter annoys you, unwatch it. If you notice changes that affect you, fetch and merge the upstream commits.


## Comment your commits as you would have others comment theirs(26-03-2018)

If you're the kind of developer who thinks (1) the code should speak for itself and (2) the in-line comments are way more important than the change logs, try cloning a repository you've never seen before and identifying the recent commit that may have caused the latest issue posted without reading all the code. As you can see, accurate commit logs are double-plus good. 


## Get changes on GitHub back to your computer(27-03-2018)

In order to get the most recent changes that you or others have merged on GitHub, use the `git pull origin master` command (when working on the master branch).

This shows you all the files that have changed and how they've changed.
Now we can use the `git log` command to see all new commits.


## Explore Github(28-03-2018)

Many interesting open source projects have repositories on GitHub. Explore GitHub provides a browsing interface to find some of them, but mostly it's easier to type a few letters of the project's name in the search box to find its repos. For example, type `jq` or `ang` to find two of the major open source JavaScript frameworks.


## Add someone as a collaborator(29-03-2018)

You can invite users to become collaborators to your personal repository.

1. Ask for the username of the person you're inviting as a collaborator. If they don't have a username yet, they can sign up for GitHub.
2. On GitHub, navigate to the main page of the repository.
3. Under your repository name, click  Settings. 
 <img src ="https://help.github.com/assets/images/help/repository/repo-actions-settings.png">
4. In the left sidebar, click Collaborators.
 <img src ="https://help.github.com/assets/images/help/repository/user-account-repo-settings-collaborators.png">
5. Under "Collaborators", start typing the collaborator's username.
6. Select the collaborator's username from the drop-down menu.
 <img src = "https://help.github.com/assets/images/help/repository/repo-settings-collab-autofill.png">
7. Click "Add Collaborator"
 <img src = "https://help.github.com/assets/images/help/repository/repo-settings-collab-add.png">
8. The user will receive an email inviting them to the repository. Once they accept your invitation, they will have collaborator access to your repository.


## Creating a Team(30-03-2018)

You can create independent or nested teams to manage repository permissions and mentions for groups of people.

**STEPS :-**

1) In the top right corner of GitHub, click your profile photo, then click **Your profile**.

<img src = "https://help.github.com/assets/images/help/profile/top_right_avatar.png">

2) On the left side of your profile page, under "Organizations", click the icon for your organization.

<img src = "https://help.github.com/assets/images/help/profile/profile_orgs_box.png" height = 400 width = 300>

3) Under your organization name, click **Teams**

<img src = "https://help.github.com/assets/images/help/organizations/organization-teams-tab.png">

4) On the right side of the Teams tab, click **New team**

<img src = "https://help.github.com/assets/images/help/teams/new-team-button.png">

5) Under "Create new team", type the name for your new team.

<img src = "https://help.github.com/assets/images/help/teams/org-new-team-name.png">

6) Optionally, in the "Description" field, type a description of the team.

<img src = "https://help.github.com/assets/images/help/teams/org-team-description.png">

7) Optionally, if you're creating a child team, use the drop-down menu to choose a parent team for your new team.

<img src = "https://help.github.com/assets/images/help/teams/choose-parent-team.png">

8) Decide whether the team will be visible or secret.

<img src = https://help.github.com/assets/images/help/teams/new-team-visibility.png>

9) Click **Create team**.

10) Optionally, give the team access to organization repositories.


## GitHub CheatSheet(31-03-2018)

When nothing seems to work out, go head to the git Cheatsheet :sunglasses: It contains all commands, in brief, from the very basics, to all complex stuff. When cheat sheet's at hand, then nothing to rant :sunglasses::sunglasses: ~i rhymed it intentionally~ . The link here https://services.github.com/on-demand/downloads/github-git-cheat-sheet/
