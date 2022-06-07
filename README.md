### Personal Website

This is my little academic website.

### Setup

~~~~
conda create -n <env-name> python=3.6+
pip install -r requirements.txt
pelican contnet (builds content/)
pelican --listen starts up local server for testing
~~~~

### To Remember:
1. [Pelican](https://github.com/getpelican/pelican) for static site setup
2. Github pages for hosting output from pelican
3. Themes from [pelican-themes](https://github.com/getpelican/pelican-themes)
    - AFAIK, this repo has to be cloned locally. Then you can use ``pelican-themes`` command line tool for management.
