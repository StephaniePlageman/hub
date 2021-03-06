---
title: "How we use GitHub"
layout: "q-and-a"
permalink: "/github-work/"
---
# {{ page.title }}

GitHub is a great tool for collaboration at 18F. Even if you don't consider yourself a developer, we want you to have access to (and eventually be comfortable with) GitHub. The setup is a handful of steps, but we promise it isn't scary.

## Steps to get set up

1. [Create an account](https://github.com/join).
    * If you're signing up for a new account, use your work email to assist with [records retention](http://ben.balter.com/open-source-for-government/#records).
    * If you already have a GitHub account, simply [add your work email](https://github.com/settings/emails).
1. [Add your name and a profile picture](https://github.com/settings/profile) to your account.
    * This makes it a lot easier for your teammates to know whose account it is and to administer the teams, but most of all it helps a lot with autocomplete in a bunch of situations.
    * We are not dogmatic that the avatar be a headshot, but please make it unique.
1. [Enable two-factor authentication](https://github.com/settings/security).
    * GitHub access _will not_ be provided if two-factor authentication is turned off.
    * While you're at it, it's a *very, very* good idea to do this for your [Gmail account](http://lifehacker.com/5932700/please-turn-on-two-factor-authentication/all) and [elsewhere](http://lifehacker.com/5938565/heres-everywhere-you-should-enable-two-factor-authentication-right-now/all).
1. Drop into [#admins-github on Slack](https://18f.slack.com/messages/admins-github/) and ask to be added to [the @18F/18F team on GitHub](https://github.com/orgs/18F/teams/18f), saying that you followed the steps above. After of of the admins says you've been added, accept the "invite" [here](https://github.com/orgs/18F/invitation?via_email=1).
1. Go to the organization's [people page](https://github.com/orgs/18F/people), click where it says "private" next to your name, and change it to "public."

    ![image](../assets/images/github-work/visibility.png)

## Get Github configured properly for work

*This is only relevant if using the command-line.*

Use your work email rather than your personal email for work-related commits – instructions at [https://help.github.com/articles/setting-your-email-in-git](https://help.github.com/articles/setting-your-email-in-git). Note that this is different than [setting notifications to go to one or another email address](https://help.github.com/articles/configuring-notification-emails-for-organizations/).

If you’re using your work computer for personal projects on GitHub and want your personal email tied to those commits, you can set your GSA email as part of the global `.gitconfig`, then [override on a repository level](http://git-scm.com/book/en/v2/Customizing-Git-Git-Configuration) with your personal email, or use a tool like [karn](https://github.com/prydonius/karn). If you have both emails [in your GitHub settings](https://github.com/settings/emails), though, they will both be tied to your GitHub account anyway.

Also, make sure you have notifications turned on. Go to [this page](https://github.com/settings/notifications) and make sure your notifications are set up they way you'd like them. (Some people watch every repo; some only watch when they're mentioned.)

## Teams

After the steps above, you should be a member of the [18F GitHub organization](https://github.com/18F). This will ensure you access into private repos that are team wide — [DevOps](https://github.com/18F/DevOps), edit access to [these pages](https://github.com/18F/hub-pages-private), etc. — and repos where general write access is encouraged. Even if you don't have write access into a repo, we strongly encourage the submission of pull requests for improvements or fixes.

_If you can't access any 18F GitHub repositories:_ Ensure you have two-factor authentication enabled (as explained above) and then ask someone in the [#admins-github Slack channel](https://18f.slack.com/messages/admins-github/) to add you to the 18F GitHub organization.

Contractors or external collaborators should only be added to teams with scoped write permissions to the repos they're working on. They should never have admin level rights. In order to seperate these permissions, create a team in the format of `projectname-admins` for staff. Please coordinate with DevOps in the Slack channel when onboarding contractors or external collaborators.

## Learn more

* After you feel comfortable with Git and GitHub, be sure to read and complete all of our [GitHub Standards](../standards/github/).
* [@wslack](https://github.com/wslack) created a [GitHub Basics](https://docs.google.com/document/d/18b-4VPTcuqat-enGQSVzivGH2CsqdQVG0K0eToRM39I/edit) guide and training, which teaches you the pointy-clicky GitHub for Mac interface.
* [@melody](https://github.com/melodykramer) and [@gboone](https://github.com/gboone) wrote a [great tutorial](https://18f.gsa.gov/2015/03/03/how-to-use-github-and-the-terminal-a-guide/) on how to use GitHub on the command-line.
* For a quick and gentle introduction to Git, the underlying protocol of GitHub, take a few minutes to work through [Try Git](https://try.github.io/levels/1/challenges/1).
* If you're ready for something more comprehensive, [Pro Git](http://git-scm.com/book/en/v2) is available in its entirety online or as a download.

## Tips and tricks

* You can set up custom email routing through the [Notifications Center](https://github.com/settings/notifications).
* Many projects at 18F use [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/) to manage branches.
* [GitHub + IFTTT = all kinds of possibilities](https://ifttt.com/github).
* See also [this repo](https://github.com/18F/github-in-government/blob/master/tips_and_tricks.md).
