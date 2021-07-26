# TrunkBasedDev

This is a demo and test bed for trunk based developement.


The idea is that there will be client side git-hooks which will check for a couple things;
Lint
Unit tests passing
unit test coverage
Commit message

These git hooks will run when the dev commits locally. If anything fails to pass, the local commit will be rejected. If it passes, then you'll be able to push up the commit.


This, however, is just some safe guards that will make pushing to Main a little safer. Ultimately, though, it is a mentally that is key. Google has some techniques or qualities that are needed to pull off [Trunk based developement](https://cloud.google.com/architecture/devops/devops-tech-trunk-based-development)
