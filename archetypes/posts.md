---
title: '{{ replace .File.ContentBaseName "-" " " | title }}'
type: post
date: {{ .Date }}
draft: true
categories:
  - Basics
cover:
    alt: Basics
    caption: 'Illustrated by [Igan Pol](https://www.behance.net/iganpol)'
    image: basics.png
    relative: false
tags:
- first
slug: {{ .Name | replace " " "-" | lower }}
---

Привет, `%username%`!

---
Если у тебя есть вопросы, комментарии и/или замечания – заходи в [чат](https://ttttt.me/jtprogru_chat), а так же подписывайся на [канал](https://ttttt.me/jtprogru_channel).
