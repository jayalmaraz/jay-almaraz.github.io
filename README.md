# Volaby Guide

Github Pages repo for Volaby's guides and documentation

## Style Guide

The only place where the formatting is critical is in the top section, before the `---` divider. This is because the Table of Contents formatting through Just the Docs struggles with this header section.

### New Doc Template

```
---
layout: default
title: Uploading your own content with Resources
parent: Managers
nav_order: 2
---

# Heading 1 (Page Title)
{: .no_toc }

## Skip To
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Heading 2
{: .fs-10 }

### Heading 3

etc.
```

## Un-fucking the issues that markdown format causes with Just a Doc styling

### General style tags

Replace all

```

{:
```

> with

```
{:
```

Hotkeys:

1. `command + option + f`
1. `control + return`
1. `{:`
1. `tab`
1. `{:`
1. `command + return`

---

### Table of content tags

Replace all

```
   {:toc}
```

> with

```
{:toc}
```

---
