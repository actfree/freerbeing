---
title: "{{ replace .Name "-" " " | title }}"
linktitle: "{{ replace .Name "-" " " | title }}"
summary:
date: {{ .Date }}
lastmod: {{ .Date }}
draft: false  # Is this a draft? true/false
toc: true  # Show table of contents? true/false
type: docs  # Do not modify.
menu:
  example:
    name: YourParentID
    # parent: YourParentID
    weight: 1
---
