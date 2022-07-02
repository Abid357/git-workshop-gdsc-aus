# "how to git good" - A Workshop on Git and GitHub

![Event](https://img.shields.io/date/1656147600?label=event&logo=googlecalendar&logoColor=white&color=red)
![Collaborators](https://img.shields.io/badge/collaborators-14-brightgreen?logo=github)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?logo=twitter&logoColor=white)](https://twitter.com/iAbid357)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?&logo=instagram&logoColor=white)](https://www.instagram.com/iabid357)

In this 4-week workshop series, we had tons of fun covering from basics to advanced topics on Git. One session was held
each week in which participants were provided with information as well as necessary tools to do the workshop.

Special thanks to the members of Google Developer Student Clubs at American University of Sharjah. All the workshop
sessions were held virtually. I will link the slides and the event page for each session.

## Session 1

[![Slides](https://img.shields.io/badge/Slides-ffffff?logo=googlesheets&logoColor=f5b911)](https://docs.google.com/presentation/d/1LeIcUPW1pedxkuW8UL7x-bnBT-VF7-vlFXn2PbvaVQo/edit?usp=sharing)
[![Event](https://img.shields.io/badge/Event-ffffff?logo=googlecalendar&logoColor=blue)](https://gdsc.community.dev/events/details/developer-student-clubs-american-university-of-sharjah-presents-git-workshop-session-1/)

There were 35+ participants which was great to be honest. The very first session was all about version control systems (
VCS), specifically Git. Comparing a VCS to an ordinary
cloud storage like Dropbox helped understand how files are tracked by changes in Git. We also explored commits and
branches.

### Commands

```
git init
git status
git add <filename>
git commit -m <message>
git log
git branch <branchname>
git checkout <branchname>
```

## Session 2

[![Slides](https://img.shields.io/badge/Slides-ffffff?logo=googlesheets&logoColor=f5b911)](https://docs.google.com/presentation/d/1Vs3J9P8hiIxBxBkQXIUBTYYKb9EjTfzPrE3Jty-7EkU/edit?usp=sharing)
[![Event](https://img.shields.io/badge/Event-ffffff?logo=googlecalendar&logoColor=blue)](https://gdsc.community.dev/events/details/developer-student-clubs-american-university-of-sharjah-presents-git-workshop-session-2/)

In this session, I introduced the participants cloud VCS such as GitHub. We further explored remote links that exist
between local and remote repositories. One of the challenges was to make sure everyone established an SSH connection to
carry out remote operations. Oh and more importantly, I rickrolled them ¯\_(ツ)_/¯

### Commands

```
git remote <action> <name> <url>
git push -u <remote> <branch>
git branch -vv
git push
git pull
git fetch
git clone <url>
```

## Session 3

[![Slides](https://img.shields.io/badge/Slides-ffffff?logo=googlesheets&logoColor=f5b911)](https://docs.google.com/presentation/d/1Cv0AfNwhXf2k0TAAUYiHZVHnLiIc_WkurSFI05Quatw/edit?usp=sharing)
[![Event](https://img.shields.io/badge/Event-ffffff?logo=googlecalendar&logoColor=blue)](https://gdsc.community.dev/events/details/developer-student-clubs-american-university-of-sharjah-presents-git-workshop-session-3/)

The third session, my personal favorite, was the most anticipated session as it covered merging and merge conflicts.
With the little time I had left, we also looked into pull requests. In this session, I used Python to create a list of
movie quotes because prior to this I watched Morbius, I had to use the best quote of all time. This was the only way.

### Commands

```
git clone <url>
git branch -a
git merge <branch>
git merge --abort
git log --all --decorate --oneline --graph
git mergetool
```

## Session 4

[![Slides](https://img.shields.io/badge/Slides-ffffff?logo=googlesheets&logoColor=f5b911)](https://docs.google.com/presentation/d/17Ry12RWKKfECQ-3qWt3sJEllumw69-lPtiFYjBA82ck/edit?usp=sharing)
[![Event](https://img.shields.io/badge/Event-ffffff?logo=googlecalendar&logoColor=blue)](https://gdsc.community.dev/events/details/developer-student-clubs-american-university-of-sharjah-presents-git-workshop-session-4/)

The final session was to let everyone know that life gets easier by using PyCharm's Git integration. We learnt a bunch
of useful but very specific commands. I asked the participants to contribute by writing song names they like.

### Operations

- Amend
- Squash
- Undo
- Revert
- Reset (--hard)
- Cherry-pick
- Rebase
- Force Push
