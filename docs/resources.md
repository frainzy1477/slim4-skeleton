---
layout: default
title: API Resources
nav_order: 14
---

# API Resources

When building an API, you may need a transformation layer that sits between 
your Service and the JSON responses that are actually returned 
to your application's users. For example, you may wish to display certain 
attributes for a subset of users and not others, or you may wish to always 
include certain relationships in the JSON representation of your data. 

The [selective/transformer](https://github.com/selective-php/transformer) component
allows you to expressively and easily transform your data into any dynamic (JSON) data structure.

There is also the [league/fractal](https://fractal.thephpleague.com/)
that provides a presentation and transformation layer for complex data output, 
the like found in RESTful APIs, and works really well with JSON
