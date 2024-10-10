---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
type: page
date: {{ .Date }}
draft: true
slug: {{ .Name | replace " " "-" | lower }}
---

