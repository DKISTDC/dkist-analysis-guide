# Contribute

We love contributions! This analysis guide is open source, built on open source, and we'd love to have you help make it even better!

First off, if directly writing content in this repository is too unfamiliar and you just want to write what you know down, we will be happy to accept contributions in any form.
Our preferences would be for something which is as close to [markdown](https://www.markdownguide.org/) as you are comfortable writing, so if not markdown then plain text, LaTeX, or lightly formatted word documents are all ok (in that order of preference).

If you are happy to contribute directly to the source on GitHub then thank you!
We have tried to make it as approachable as possible, but if you encounter any issues then please let us know.

## Getting Started

The first step is to sign up / sign into GitHub.

The next step is to fork the repository to your own GitHub account, to do this go to https://github.com/DKISTDC/dkist-analysis-guide/fork.

Then, you clone the repository to your local machine. First make sure you have [generated an SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent) and [added it to your GitHub account](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

To clone the repository run:

```console
$ git clone git@github.com:<your github username here>/dkist-analysis-guide.git
```

setting your github username as required.

Next we want to add the upstream DKISTDC repository to your local clone:

```console
$ git remote add upstream git@github.com:DKISTDC/dkist-analysis-guide.git
```

Then we can update the remotes with:

```console
$ git remote update
```

This should set you up with a local copy of the files to edit.


## Authoring Content
