# Stack Ranking Experiments

This repository is the start of experimentation and evaluation of a quick reject
method that revolves around ACs doing an initial stack ranking of a subset of 
papers, combining the individual stacks into an overall ranking, and then auto
rejecting the bottom n% of papers.

This idea is further described in:
https://docs.google.com/document/d/17HctvVkZq1S9bc3sbPo7n0wzAmdUyYuB9Hb83nPttLw/edit

Collaboration on this experimentation is welcome. Please just reach out to me, for
example by filing an issue on the repo.

Work is starting entirely in Jupyter notebooks, but I expect that some commonly
used methods will be split out into a separate module.

This repository uses `pipenv` to manage its virtual environment.
