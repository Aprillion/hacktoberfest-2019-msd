---
title: Hacktoberfest 2019 MSD
theme: black
highlight-theme: atelier-dune-dark
verticalSeparator: --v
revealOptions:
  transition: none
  controls: true
  width: 1500
  height: 843
---

<!-- .slide: data-background="./first.png" -->

---

<!-- .slide: data-background="./default.png" -->

## Open Source

---

<!-- .slide: data-background="./default.png" -->

## Open and Free

- view
- use
- modify
- distribute

---

<!-- .slide: data-background="./default.png" -->

## Community

---

<!-- .slide: data-background="./default.png" -->

- Linux
- React
- OctoPrint
- Vue.js
- ...

---

<!-- .slide: data-background="./default.png" -->

## Documentation

---

<!-- .slide: data-background="./default.png" -->

## Licenses

---

<!-- .slide: data-background="./default.png" -->

# How to contribute

---

<!-- .slide: data-background="./default.png" -->

- find the project
- check CONTRIBUTING.md
- just do :)

---

<!-- .slide: data-background="./default.png" -->

## Github contribution Demo

---

<!-- .slide: data-background="./default.png" -->

# Good Commit Messages

---

<!-- .slide: data-background="./default.png" -->

## Why?

```md
- Fixed nasty bug by changing configuration issue with missing keys.
- refactoring of ArsService
- Typo
- new version
```

vs

```md
- 🐛 Fix nasty bug in configuration
- ♻️ Refactor the ArsService
- ✏️ Fix typo
- 🔖 Release version 2.0.1
```

---

<!-- .slide: data-background="./default.png" -->

## Keep subject short (50 characters)

```md
- I fixed nasty bug in configuration.
- refactoring of ArsService
- Typo
- new version.
```

Note: keeps subject short, simple

---

<!-- .slide: data-background="./default.png" -->

## Capitalize the subject line

```md
- I fixed nasty bug in configuration.
- Refactoring of ArsService
- Typo
- New version.
```

Note: good for consistency

---

<!-- .slide: data-background="./default.png" -->

## Don't end subject line with a period

```md
- I fixed nasty bug in configuration
- Refactoring of ArsService
- Typo
- New version
```

Note: not necessary in subject line, brings no value

---

<!-- .slide: data-background="./default.png" -->

## Use the imperative mood

```md
- Fix nasty bug in configuration
- Refactor the ArsService
- Fix typo
- Release version 2.0.1
```

Note: This one I like most, clean instructions

--v

<!-- .slide: data-background="./default.png" -->

- Clean your room
- Close the door
- Take out the trash

--v

<!-- .slide: data-background="./default.png" -->

Git uses imperative mode itself

```md
- Merge branch 'myfeature'
- Revert "Add the thing with the stuff"
- Merge pull request #123 from someuser/somebranch
```

--v

<!-- .slide: data-background="./default.png" -->

Finish the sentence:

**If applied, this commit will**

- _fix the broken issue_
- _remove deprecated code_

## Separate subject from body with a blank line

<!-- .slide: data-background="./default.png" -->

```md
Fix nasty bug in configuration

There was an issue with config, so it's fixed lorem impsum, dolor sit amet, con
this is my love letter to this issue. And I pity anyone who will be refactoring
this code.
```

Note: improved git log

---

<!-- .slide: data-background="./default.png" -->

## Wrap the body at 72 characters

```md
Fix nasty bug in configuration

There was an issue with config, so it's fixed lorem impsum, dolor sit amet, con
this is my love letter to this issue. And I pity anyone who will be refactoring
this code.
```

Note: gives git space to indent and be under 80 characters

---

<!-- .slide: data-background="./default.png" -->

## Use the body to explain what and why vs. how

---

<!-- .slide: data-background="./default.png" -->

# gitmoji

```md
- 🐛 Fix nasty bug in configuration
- ♻️ Refactor the ArsService
- ✏️ Fix typo
- 🔖 Release version 2.0.1
```

---

<!-- .slide: data-background="./default.png" -->

- Short subject (50 characters)
- Capitalize the subject line
- No period
- Imperative mood
- Separate subject from body
- Wrap the body at 72 characters
- Explain what and why vs. how

---

<!-- .slide: data-background="./default.png" -->

- [How to Write a Git Commit Message](https://chris.beams.io/posts/git-commit/)
- [gitmoji](https://gitmoji.carloscuesta.me/)
- [An Introduction to Open Source](https://www.digitalocean.com/community/tutorial_series/an-introduction-to-open-source)
- [HacktoberFest](https://hacktoberfest.digitalocean.com)
