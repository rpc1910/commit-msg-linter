# git-commit-msg-linter

> Watching your every git commit message. 👀

![git-commit-msg-linter-demo](https://raw.githubusercontent.com/legend80s/commit-msg-linter/master/assets/demo-3.png)

A git "commit-msg" hook for linting your git commit message against the [Angular Commit Message Guidelines](https://github.com/angular/angular/blob/master/CONTRIBUTING.md#-commit-message-guidelines). As a hook it will run at every commiting to make sure that your every commit message is valid against the conventions. If not your commit will be aborted.

*The repo is heavily influenced by [pre-commit](https://github.com/observing/pre-commit). Thanks.*

## Install

```shell
npm install git-commit-msg-linter --save-dev
```

*To uninstall run the `uninstall` script instead of removing it manually* because only in this way, the `commit-msg` hook can be restored, then your next commit messages will be ignored by git-commit-msg-linter.

```shell
npm uninstall git-commit-msg-linter --save-dev
```

## Why yet a new linter

Firstly no simple git commit message hook ever exists right now. To Add, to overwrite or to remove `type`s is not so friendly supported. *Why not [conventional-changelog/commitlint](https://github.com/conventional-changelog/commitlint), read the [FAQs](https://github.com/legend80s/commit-msg-linter/blob/master/assets/docs.md#faqs)*.

Secondly it's very important to follow certain git commit message conventions and we recommend Angular's.

## Recommended commit message pattern

> \<type\>(\<scope\>): \<subject\>
>
> // scope optional

## Documentations

[Configuration and FAQs.](https://github.com/legend80s/commit-msg-linter/blob/master/assets/docs.md)