---
title: "Home"
show_status: true
---
# Home Page
#### -{{ "Neil" | capitalize }}

## {{ "Hello World!" | upcase }}

This is {{ page.title | upcase}} page.

{% if page.show_status %}
### The developer neil is tired    
{% endif %}

## Step for Creating new jekyll site:

- ```sh jekyll new site/ --blank ```
- ```sh cd site/ ```
- ``` bundle exec jekyll serve ```
