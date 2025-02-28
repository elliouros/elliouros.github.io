---
title: >-
  title :o
# >- is used to escape the : in :o
ititle: example!!
summary: this is an example post
layout: blog
style: base
style-internal: |-
  h2 {
    margin: 0;
    + p {
      margin-top: 0;
    }
  }
hidden: true
---
# This is an example blog page.

It has both a `title` and an `ititle`, so on the index it shows differently
than it does here.

**This is written in md!**

## the margins of this should be escaped...
via the `style-internal` front matter

### additionally...
`style: base` imports the rest of the style<br>
**which is why the page doesn't look like ass!**
