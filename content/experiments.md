---
title: "Experiments"
date: 2022-03-30T14:13:49+05:30
draft: false
---

## Images


{{ $image := resources.Get "images/sunset.png" }}
<img src="{{ $image.Permalink }}">


