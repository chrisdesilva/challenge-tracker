Challenge Tracker is a React app that gamifies goals. Users can set points to use as motivation for working toward their goals. Each day, users will tally their points to track their progress and will be able to challenge other users to build accountability.

**Example goal:** User wants to lose 10 pounds in 90 days

**Example points:** 3 points for 30 minutes of exercise, 2 points for 7-9 hours of sleep, 2 points for going sugar-free

# Contribute [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

I'd LOVE your help on this project! All are welcome to contribute. You can find current issues under the [issues tab](https://github.com/chrisdesilva/challenge-tracker/issues). Just find an issue that you'd like to work on, make a comment to say you're taking it on, and get to it. 

**Working on your first Pull Request?** You can learn how from this *free* series [How to Contribute to an Open Source Project on GitHub](https://egghead.io/series/how-to-contribute-to-an-open-source-project-on-github)

**Would you rather read than watch videos?** Check out this [article](https://akrabat.com/the-beginners-guide-to-contributing-to-a-github-project/).

## Getting Started

1. Fork the project by clicking the Fork button up at the top of the screen.
2. Clone your fork with `git clone [code-you-copied-from-clone-button]`
3. `cd challenge-tracker` to make sure you are in the right directory
4. Add an `upstream` remote for keeping your local repo up-to-date:
  > `git remote add upstream git@github.com:chrisdesilva/challenge-tracker.git`
5. Run `npm install` to install project dependencies
6. Run `npm start` to start your dev environment 
7. Begin making magic

## Creating a New Pull Request
1. Make sure you are on the `master` branch and have pulled the latest changes:
  > `git checkout master && git pull upstream master`
2. Install any new dependencies: `npm install`
3. Create a new branch off of the `master` branch for the issue you are working on:
  > `git checkout -b [new-branch-name]`
  Make sure your branch name relates to the issue. For example, if your issue is "Convert goals component to a functional component using Hooks", your branch name could be `convert-goals-component`.
4. Make your changes. Be sure to check for any errors and address them as they come up.
5. Add and commit your changes: 
> `git add [file-name] && git commit -m [your-message]`
  Use present tense with your commits ("convert goals component" instead of "converts" or "converted").
6. Push your branch to your fork: `git push -u origin [branch-name]`
7. Open a new pull request (PR) against the `master` branch from your fork using the GitHub user interface.

