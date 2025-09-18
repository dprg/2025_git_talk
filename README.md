# Git and Github - zero to hero in 60 minutes

- Scope: how too do common operations for common scenarios

## What is git + github

- github keeps a copy of your code repository on your PC in the cloud
- git manipulates the code repository version history, and provides for
syncing it with the cloud version

Include image of github repo and git on PC

## Why use git + github?

Robotics centrally includes software/firmware. You need to use proper
techniques in its development. Git enables good techniques. Here's how:

- Cloud backup of your code saves you if you accidentally delete your
code folder on your PC. It's a lot harder to delete a github repo than
a directory.

- Save intermediate "working states" of your code, and easily get back
to them for testing

- Switch between multiple configs - e.g. between two robot configs, or
two sensor configs

- Avoid "multiple copies of code directories" syndrome. Easily make
changes to test something without changing the known-good version (difficult
without multiple copies if not using git)

- Document changes (vs. documenting lines of code) with comments in the
commit message. Supports long-term project archeology - months or years
later you can see not just what you changed but why.

- Sync your code directory between multiple machines. Get warnings about
conflicting changes between them. Scenarios: same codebase on PC and on Raspberry Pi
used for different purposes

- Fearless refactoring or trying out new libraries/features. Git encourages
bold changes. Start a major refactoring on a branch and abandon it if
it doesn't work out. Safety net gives you confidence to try big changes.

- Maintain a "Release" version that's always ready to run, while you develop
on a branch. Helps you quickly isolate whether a problem that arises in development
is due to the SW change or if HW broke.
