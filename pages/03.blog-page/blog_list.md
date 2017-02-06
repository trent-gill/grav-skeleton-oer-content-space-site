---
title: 'Blog Page'
hide_git_repo_link: false
sitemap:
    changefreq: monthly
external_links:
    process: true
    title: false
    no_follow: true
    target: _blank
    mode: active
content:
    items: '@self.children'
    leading: 0
    columns: 2
    limit: 10
    order:
        by: date
        dir: desc
    show_date: false
    pagination: true
    url_taxonomy_filters: true
blog_url: blog
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

