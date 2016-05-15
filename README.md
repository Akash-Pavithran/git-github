[![General Assembly Logo](https://camo.githubusercontent.com/1a91b05b8f4d44b5bbfb83abac2b0996d8e26c92/687474703a2f2f692e696d6775722e636f6d2f6b6538555354712e706e67)](https://generalassemb.ly/education/web-development-immersive)

# Git and Github

## Objectives

-   Manage change in a project.
-   Collaborate over time and space.
-   Fork a repository.
-   Clone a repository
-   Synchronize repositories locally.
-   Synchronize repositories remotely.

## Prerequisites

-   [Git Basics](https://github.com/ga-wdi-boston/git-basics)

## Overview

Continuing with what we started in [Git
Basics](https://github.com/ga-wdi-boston/git-basics). Now we are going to use
Github to manage our project.

## Demo: Linking with GitHub

So we have a local repository, watch as I create a GitHub repository. Why
GitHub? So we can backup our code online. It also provides us with a useful
graphical interface and useful collaboration features.

Now create your own GitHub repository and `push` your master branch.

## Lab: More Pushing

The last time we saw Ned Stark we had just written his fate.  Below his story,
write the beginning of another character's story. For instance:

```bash
Joffrey Baratheon was the one to do Ned in, but his story was only about to
begin. Let me assure you, he will _DEFINITELY NOT DIE!_
```

Push the changes you've made.

Also push your `dream-story` branch.  We pushed our `master` branch with the
command `git push origin master`.  Can you figure out how to push our
`dream-story` branch?

## Demo: Adding to Your Story

Watch as I `fork` and `clone` one of your repos and make an addition by
creating a `pull request`.

## Lab: Adding to Other's Stories

Working with a partner follow my example and take turns adding to one another's
stories. Accept each other's pull requests.  After you've each gone once stop.

## Pulling: Updating Your Local

Each of you should now have updated code on GitHub, but your local Git repo
will be behind.  We need to get the latest code off of GitHub.  We can do this
by pulling the changes that we merged.  The command to do this is:

`git pull origin master`

This get the latest copy of our code off of the master branch of our original
repository.

## Remotes

A remote repository is just another repository that you are connected to and
depending on your permission you can push code up to it and pull code down from
it.

Watch as I add a remote from one of your repositories then update my local with
the changes. You will be asked to do this next.

`git remote add upstream <"git@gsomessh.com/">` is the command to add a remote
called upstream.  It's just as easy to pull from it.

## Adding Your Own Remote

Working with the same partner from before one of you will be the primary
repository, the other will be a contributor.

1.The contributor will add the primary repository as a remote.

2.The primary will push their latest story to the master branch.

3.The contributor will pull the master branch from the primary.

4.The contributor will add to the story and push their changes to their own
repository and create a pull request to the primary.

5.The primary will accept the pull request and pull the changes to their local.

6.The primary will add to the story and push the changes to their master branch.

7.The primary and the contributor will go back and forth adding to the story.

## References

- [Git Commands](command-reference.md)
- [Github's fork page](https://help.github.com/articles/fork-a-repo/)

## [License](LICENSE)

Source code distributed under the MIT license. Text and other assets copyright
General Assembly, Inc., all rights reserved.
