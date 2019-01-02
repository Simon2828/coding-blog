---
templateKey: blog-post
title: localStorage
date: '2019-01-02T18:27:02+00:00'
description: persisting state react
tags:
  - react
---
Used localStorage so when using browser back and forward buttons state will persist. This works fine, however when removing item from localStorage am struggling to rerender on componentDidMount. Uncontrolled component with keys not working... maybe need to use getDerivedStateFromProps.
