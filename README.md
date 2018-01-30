Build your own Lisp
===================

Jekyllized: https://dougbeney.github.io/BuildYourOwnLisp-Jekyllized/
Original: http://buildyourownlisp.com

About
-----

This is a fork of BuildYourOwnLisp that uses Jekyll/static HTML instead of Python/Flask.

Running
-------

First, succesfully install [Jekyll/Bundler](https://jekyllrb.com/) (You'll need Ruby too).

Next, simply type `jekyll serve`.

Go to [localhost:4000](http://localhost:4000) and you should see the site! Great job.

Deploying to GH-Pages
-------

After building the project using either `jekyll build` or `jekyll serve`, deploy to the gh-pages branch using the following command:

```
git subtree push --prefix dist origin gh-pages
```
