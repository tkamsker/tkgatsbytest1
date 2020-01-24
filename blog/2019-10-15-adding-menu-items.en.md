---
title: Adding menu items
description: Add menu items in GraphQL to create a dynamic menu
date: '2019-10-15 15:41:34'
image: /assets/img/07.jpg
category: Gatsby
background: '#7d4cdb'
---
The menu items translations are located in `config/menu` and the `useMenu` custom hook pulls these translations (via GraphQL query) and inserts them into the pages.

<a href="http://www.google.com">Link to Google</a> <br/> <a href="/about">Internal link</a>

```JS
{
  "menuItems": [
    { "name": "Home", "link": "/" },
    { "name": "Documentation", "link": "/docu" },
    { "name": "About", "link": "/about-me" },
    { "name": "Blog", "link": "/blog" },
    { "name": "Contact", "link": "/contact" }
  ]
}
```
