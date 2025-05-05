---
title: "{{ replace .File.ContentBaseName "-" " " | title }}"
date: "{{ now.Format "2006-01-02" }}"
author: "{{ .Site.Params.author.name }}"
draft: false
toc: true
readTime: true
showTags: true
tags: ['new']
---
