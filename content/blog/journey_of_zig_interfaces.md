---
date: "2026-01-24T12:49:09-03:00"
draft: true
title: "Journey of Zig Interfaces"
authors:
  - name: Luiz Henrique
    link: https://github.com/LuizSSampaio
    image: https://github.com/LuizSSampaio.png
tags:
  - Zig
---

I've started to learn Zig to build some fun projects that I'll be written about
at future. Bug I got a giant bottleneck at this process, and it was the
interfaces. Unlike other languages that have specific implementation and syntax
sugar Zig doesn't do that, we need the use of compile time types or
[vtables](https://en.wikipedia.org/wiki/Virtual_method_table) at runtime.

I'll make a deep coverage about the matter to help you to understand it.

{{< callout type="warning" >}} Zig isn't stable and can change between updates.
This post is written at **version 0.16**. {{< /callout >}}

## What Is an Interface?

## Acknowledgment

- [Wikipedia: vtable](https://en.wikipedia.org/wiki/Virtual_method_table)
