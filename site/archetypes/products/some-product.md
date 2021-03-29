---
title: "{{ replace .Name "-" " " | title }}"
date: {{ .Date }}
draft: false
description: "meta_description"
data_file: some-file-or-folder
index: true
weight: 1
---

{{< img src="someimage.jpg" alt="this is the alt text" >}}