---
layout: page
title: Structured Data
nav: 3
summary: Structured data allows for more control.
images:
  - file: 1.jpg
    title: Fig
    link: https://www.moma.org/collection/works/194633
  - file: 2.jpg
    title: Pomegranate
    link: https://www.moma.org/collection/works/194634
  - file: 3.jpg
    title: Glasser
    link: https://www.moma.org/collection/works/194635
  - file: 4.jpg
    title: Square Cloud
    link: https://www.moma.org/collection/works/194636
  - file: 5.jpg
    title: Kiwi
    link: https://www.moma.org/collection/works/194637
  - file: 6.jpg
    title: Up Died
    link: https://www.moma.org/collection/works/194638
---

## Templating with Jekyll

Often you are going to want to have more control than Markdown alone allows. Jekyll facilitates this with *structured data* it calls *[front-matter](https://jekyllrb.com/docs/front-matter/)*.

This is saved at the top of your `.md` files, in a data format called [YAML](https://en.wikipedia.org/wiki/YAML)—for *Yet Another Markup Language*. (So many languages, I know.)

### Note that YAML/YML uses spaces for indentation, and will break with tabs character! I do this all the time.

This data can then be accessed in your `layouts` and `includes` for consistent structure and formatting! A bit like our *Are.na* projects.
