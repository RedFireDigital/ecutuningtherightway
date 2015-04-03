# Contributing to ECU Tuning The Right Way

## Using the issue tracker

The [issue tracker](https://github.com/PartFire/ecutuningtherightway/issues) is
the preferred channel for changes: spelling mistakes, wording changes, new 
content and generally [submitting pull requests](#pull-requests), but please 
respect the following restrictions:


<a name="pull-requests"></a>
## Pull Requests

Pull requests are a great way to add new content to ECU Tuning The Right Way, as well 
as updating any browser issues or other style changes. Pretty much any sort of 
change is accepted if seen as constructive.

Adhering to the following this process is the best way to get your work
included in the project:

1. [Fork](http://help.github.com/fork-a-repo/) the project, clone your fork,
   and configure the remotes:

   ```bash
   # Clone your fork of the repo into the current directory
   git clone https://github.com/<your-username>/php-the-right-way.git
   # Navigate to the newly cloned directory
   cd php-the-right-way
   # Assign the original repo to a remote called "upstream"
   git remote add upstream https://github.com/codeguy/php-the-right-way.git
   ```

2. If you cloned a while ago, get the latest changes from upstream:

   ```bash
   git checkout gh-pages
   git pull upstream gh-pages
   ```

3. Create a new topic branch (off the main project development branch) to
   contain your change or fix:

   ```bash
   git checkout -b <topic-branch-name>
   ```

4. Install the [Jekyll](https://github.com/jekyll/jekyll/) gem to preview locally.

5. Commit your changes in logical chunks.

6. Locally merge (or rebase) the upstream development branch into your topic branch:

   ```bash
   git pull [--rebase] upstream gh-pages
   ```

7. Push your topic branch up to your fork:

   ```bash
   git push origin <topic-branch-name>
   ```

8. [Open a Pull Request](https://help.github.com/articles/using-pull-requests/)
    with a clear title and description.


## Contribution Agreement and Usage

By submitting a pull request to this repository, you agree to allow the project 
owners to license your work under the the terms of the [GNU General Public License v2.0](http://choosealicense.com/licenses/gpl-2.0/).

The same content and license will be used for all ECU Tuning The Right Way publications,
including - but not limited to:

* [ecutuningtherightway.com](http://ecutuningtherightway.com)
* Translations of ecutuningtherightway.com
* [LeanPub: PHP The Right Way](https://leanpub.com/ecutuningtherightway/)
* Translations of "LeanPub: |ECU Tuning The Right Way"

All content is completely free now, and always will be.

## Contributor Style Guide

1. Use UK English spelling (*primary English repo only*)
2. Use [GitHub Flavored Markdown](http://github.github.com/github-flavored-markdown/) for all content

