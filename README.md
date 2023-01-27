# arXiv-daily
Generate new published papers on arXiv everyday and select the papers you are interested in.

## Install requirements
* arxiv

```
pip install arxiv
```

* arxivpy

```
pip install git+https://github.com/titipata/arxivpy
```

**NOTE:** When you install the arxivpy package using ``pip install arxiv``, it may install the ``arxivpy-0.0.2`` and lead to error when run ``search.py`` in the ``arxivpy.query()`` function. So I suggest that you use the above commad to install the arxivpy package.

## Get started
1. Run the bash.
```
bash upload.sh
```
2. Select whether the paper you are interested in, and your interested paper will be saved in the markdown file ``date.md`` in the folder ``/markdowns``.
```
[1] Title

Authors: Author 1; Author 2; ...

Abstract: ...

Save? (Space for save, Enter for skip)
```

3. You can select the arXiv paper category you are interested in in ``search.py``, e.g. [cs.CV], to get the papers updated today under that category.

## References
[[arxivpy]](https://github.com/titipata/arxivpy) [[arxiv_sanity]](https://github.com/aniki-ly/arxiv_sanity)

Last updated: Jan 27, 2023
