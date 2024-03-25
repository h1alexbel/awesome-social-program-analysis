# Awesome Social Program Analysis

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)
[![markdown-lint](https://github.com/h1alexbel/awesome-social-program-analysis/actions/workflows/markdown-lint.yml/badge.svg)](https://github.com/h1alexbel/awesome-social-program-analysis/actions/workflows/markdown-lint.yml)

This is a curated list of **academic** (!) books and papers on
neural/social program analysis, which promote
"Analysis of source code using LLM and ML".
The quotes are mostly of critical nature.

## Papers

### Neural Software Analysis

Michael Pradel and Satish Chandra.
**Neural software analysis**.
_Commun. ACM 65_, 1 (January 2022), 86–96.
[ACM](https://doi.org/10.1145/3460348):
> "Fortunately, software is written by humans and hence follows regular
patterns and coding idioms, similar to natural language.
For example, developers commonly call a loop variable i or j,
and most developers prefer a for-loop over a while-loop when iterating
through a sequential data structure.
This “naturalness” of software has motivated research on machine learning-based
software analysis that exploits the regularities and conventions of code."

### Static Analysis with LLMs

Haonan Li, Yu Hao, Yizhuo Zhai, and Zhiyun Qian.
**Assisting Static Analysis with Large Language Models: A ChatGPT Experiment**.
_In Proceedings of the 31st ACM Joint European Software Engineering Conference
and Symposium on the Foundations of Software Engineering (ESEC/FSE 2023)_.
[ACM](https://doi.org/10.1145/3611643.3613078):
> We progressively provide information, such as function definitions
when necessary. Specifically, we always prompt ChatGPT with the
following message: “If you experience uncertainty due to insufficient
function definitions, please indicate the required functions”.
Upon receiving a request for additional information from ChatGPT,
we automatically retrieve and provide the required data from the
source code of Linux, enabling the model to reevaluate and generate
an improved response.

## How to contribute

I'm not interested in professional or scholar books, web articles, videos,
blog posts, etc.
The list must include only academic papers, like ACM/IEEE/etc. conference
proceedings or publications in scientific journals.

I use [ACM citation style](https://www.acm.org/publications/authors/reference-formatting)
with a bolder font for titles.

To find new papers I recommend to use [arXiv](https://arxiv.org),
[DL ACM](https://dl.acm.org), [Google Scholar](https://scholar.google.com).
