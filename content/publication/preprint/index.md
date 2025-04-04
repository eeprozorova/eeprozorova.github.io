---
title: "Язык разметки Markdown"
authors:
- admin
date: "2025-04-04"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2025-04-04T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Markdown — это простой и удобный язык разметки, предназначенный для форматирования текста. Он позволяет быстро создавать структурированные документы с помощью легко читаемого синтаксиса. Широко используется для написания README-файлов, документации и веб-контента..

# Summary. An optional shortened abstract.
summary: Markdown — это лёгкий язык разметки для форматирования текста с простым синтаксисом. Он часто используется в документации, блогах и README-файлах.

tags:
- Язык разметки Markdown

featured: true

links:
- name: Custom Link
  url: http://example.org
url_pdf: http://arxiv.org/pdf/1512.04133v1
url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

## . Базовые сведения о Markdown
Чтобы создать заголовок, используйте знак #, например:
"# This is heading 1"
"## This is heading 2"
"### This is heading 3"
"#### This is heading 4"
Чтобы задать для текста полужирное начертание, заключите его в двойные звездочки:
This text is "**bold**."
Чтобы задать для текста курсивное начертание, заключите его в одинарные звездочки:
This text is "*italic*"
Чтобы задать для текста полужирное и курсивное начертание, заключите его в тройные
звездочки:
This is text is both "***bold and italic***"
Блоки цитирования создаются с помощью символа >:
"> The drought had lasted now for ten million years, and the reign of the.."

Упорядоченный список можно отформатировать с помощью соответствующих цифр:
1. First instruction
1. Sub-instruction
1. Sub-instruction
1. Second instruction
Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:
1. First instruction
1. Second instruction
1. Third instruction
Неупорядоченный (маркированный) список можно отформатировать с помощью звездочек или тире:
* List item 1
* List item 2
* List item 3
Чтобы вложить один список в другой, добавьте отступ для элементов дочернего списка:
- List item 1
- List item A
- List item B
- List item 2
Синтаксис Markdown для встроенной ссылки состоит из части [link text], представляющей текст гиперссылки, и части (file-name.md) – URL-адреса или имени файла, на который
дается ссылка:
[link text](file-name.md)
или
[link text](http://example.com/ "Необязательная подсказка")
Markdown поддерживает как встраивание фрагментов кода в предложение, так и их размещение между предложениями в виде отдельных огражденных блоков. Огражденные блоки
кода — это простой способ выделить синтаксис для фрагментов кода. Общий формат огражденных блоков кода:
``` language
your code goes in here