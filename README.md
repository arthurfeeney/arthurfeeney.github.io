### Personal Website

This contains the source for my little academic website.

### Setup

~~~~
conda create -n <env-name> python=3.6+
pip install -r requirements.txt
pelican contnet (builds content/)
pelican --listen starts up local server for testing
~~~~

### Deploying

This is sort of annoying: this source repo has to be separate from the github pages repo.
[How to deploy user page](https://docs.getpelican.com/en/latest/tips.html#user-pages)

This pushes the ``output/`` to my user github page. I think it is safe to force-push because the github page won't contain any of the source.

~~~~
<do development, updates, or w/e>
pelican content
ghp-import output -b gh-pages
git push -f https://github.com/arthurfeeney/arthurfeeney.github.io gh-pages:master
~~~~

### To Remember:
1. [Pelican](https://github.com/getpelican/pelican) for static site setup
2. Github pages for hosting output from pelican
3. Themes from [pelican-themes](https://github.com/getpelican/pelican-themes)
    - AFAIK, this repo has to be cloned locally. Then you can use ``pelican-themes`` command line tool for management.
