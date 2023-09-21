---
title: Pages
tags: [getting_started, formatting, content_types]
keywords: pages, authoring, exclusion, frontmatter
last_updated: July 16, 2016
#summary: "This theme primarily uses pages. You need to make sure your pages have the appropriate frontmatter. One frontmatter tag your users might find helpful is the summary tag. This functions similar in purpose to the shortdesc element in DITA."
sidebar: mydoc_sidebar
permalink: mydoc_pages.html
folder: mydoc
---

## Headings

Use pound signs before the heading title to designate the level. Note that kramdown requires headings to have one space before and after the heading. Without this space above and below, the heading won't render into HTML.

```
## Second-level heading
```

**Result:**

## Second-level heading

-----

```
### Third-level heading
```
**Result:**

### Third-level heading

------

```
#### Fourth-level heading
```

**Result:**

#### Fourth-level heading

## Headings with ID Tags {#someIdTag}

If you want to use a specific ID tag with your heading, add it like this:

```
## Headings with ID Tags {#someIdTag}
```

Then you can reference it with a link like this on the same page:

```
[Some link](#someIdTag)
```

{% include links.html %}
