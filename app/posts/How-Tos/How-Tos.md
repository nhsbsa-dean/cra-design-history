---
tags: false
layout: collection
title: How to
<<<<<<< HEAD
description: Generic description
=======
description: Visual instuctions for different tasks
>>>>>>> main
pagination:
    data: collections.How-Tos
    reverse: true
    size: 10
permalink: "How To's/{% if pagination.pageNumber > 0 %}page/{{ pagination.pageNumber + 1 }}{% endif %}/"
eleventyComputed:
    eleventyNavigation:
        key: "{{ title }}"
        excerpt: "{{ description }}"
        parent: home
---
