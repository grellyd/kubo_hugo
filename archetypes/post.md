// Post Archtype
+++
title: "{{ .Name | replaceRE "^([0-9_]{11})([a-zA-Z_])" "$2" | replaceRE  "_" " " | title }}"
date: {{ .Date }}
draft: true
+++

**Insert Lead paragraph here.****
