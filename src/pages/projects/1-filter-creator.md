---
repoName: FilterCreator


setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Filter Creator
publishDate: 12 Sep 2020
name: Maurer Krisztian
value: 128
description: Basic image editor with OpneCV.
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

# {frontmatter.title}

Basic image editor with OpneCV.


details: <a href={'/git/' + frontmatter.repoName}>{frontmatter.repoName}</a>