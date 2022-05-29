---
repoName: minimal-dependency-injection

technologies: ['js','ts', 'decorators']

setup: |
  import Layout from '../../layouts/BlogPost.astro'
  import Cool from '../../components/Author.astro'
title: Dependency injection IOC
publishDate: 12 Sep 2020
name: Maurer Krisztian
value: 128
description: An ioc container from scratch.
---

<Cool name={frontmatter.name} href="https://twitter.com/n_moore" client:load />

This is so cool!

Do variables work {frontmatter.value * 2}?

```javascript
// Example JavaScript

const x = 7;
function returnSeven() {
  return x;
}

```
