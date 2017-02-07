---
title: 'Add Blog Post'
template: form
parent: /blog
pagefrontmatter:
    template: item
    title: 'My new Blog post'
    taxonomy:
        category: blog
        tag:
            - journal
            - guest
form:
    name: add-blog-post-form
    fields:
        -
            name: author
            label: Author
            placeholder: 'Enter your name here'
            autocomplete: true
            type: text
            validate:
                required: true
        -
            name: title
            label: 'Blog Post Title'
            placeholder: 'Enter your page title here'
            autocomplete: true
            type: text
            validate:
                required: true
        -
            name: content
            id: simplemde
            label: 'Page Content'
            size: long
            placeholder: 'Write the content here'
            type: textarea
            validate:
                required: true
    buttons:
        -
            type: submit
            value: Submit
            classes: null
    process:
        -
            addpage: null
        -
            display: thank-you
---

You can add a new blog post by filling in the form below.

Please enter your name, a title and write something nice.