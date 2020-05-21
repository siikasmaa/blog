---
title: Project notes
date: "2020-05-21T17:00:00.000Z"
---

Collection of points taken while building this site and using Svelte+Sapper for the first time.

<!-- more -->

- Selected webpack template since I’m most familiar with Webpack (compared to rollup.js)
- Encountered first issue after 5 minutes https://github.com/sveltejs/sapper/issues/764
- Found in webpack configuration https://github.com/sveltejs/svelte/issues/2377
- Started checking if Svelte supports Typescript: https://github.com/sveltejs/svelte/issues/4518
  - Hot reloading brought up there as well...
  - TLDR; Have to use community provided processor (svelte-preprocess)
- Support for VSCode when you have added the community support preprocessor: https://github.com/sveltejs/svelte-preprocess#with-svelte-vs-code?
- Found out that Sapper verions <=0.27.11 are vulnerable to Path Traversal
- Use external connection to fetch the posts -> transpile Markdown to html/json elsewhere
