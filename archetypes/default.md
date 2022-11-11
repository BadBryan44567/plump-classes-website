---
title: "{{ replace .Name "-" " " | title }}"
description:
date: {{ .Date }}
url: /posts/{{.Name}}/
image: images/{{ .Name }}.jpg
draft: false
---

