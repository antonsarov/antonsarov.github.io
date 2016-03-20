---
published: true
title: Groovy AST transformations pitfalls
layout: post
tags: [groovy, ast]
---
- **Always** use `ClassHelper.make(Class c)` and not  `ClassHelper.make(String name)`