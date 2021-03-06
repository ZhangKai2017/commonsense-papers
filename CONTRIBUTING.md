# Contributing Guidelines

Welcome to the `commonsense-papers` project. We aim to select the most representative and innovative papers in the research field of **commonsense knowledge**, and provide taxonomy/classification as well as statistics of these papers to give a quick overview of the field and help focused reading.

Since our paper-list cannot be complete, we welcome your contributions. 

## Paper

All the papers include here should follow the following format: 

```
**Paper Title** (abbreviation, if exists, and not in title) VENUE YEAR [code](url)

*Author1, Author2*
```

Different kinds of papers may have different requirements: 

- For resource, includes author names, venue(published version first, then arxiv), resource abbreviation, links to homepage, paper and code(if possible).

- For other papers, includes author names, venue, links to paper and code(if possible), and list the resources used if possible.

## Classification

See the current table of contents.

If a paper does not fit into a current (sub)class, can add a new one.

If a paper provides a resource as well as a method, we usually put it into the resource class.

## Statistics

After editing the paper list with the format stated above, simply run `gen_stats.py` and the statistics in `README.md` will automatically update.