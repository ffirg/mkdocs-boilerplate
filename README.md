# mkdocs-boilerplate

mkdocs is a wonderful tool for creating static webpages from simple markdown.
This document is written in markdown :)

This repo provides a boilerplate setup for a good mkdocs initial setup.

Basically, create some markdown .md files and mkdocs will do the rest :)

## Install/Setup

Install mkdocs (I use pip install)

Git clone this repo into a directory:

```bash
git clone https://github.com/ffirg/mkdocs-boilerplate.git <your dirname>
cd <your dirname>
```

## Config

This repo will give you:

```bash
tree
.
├── README.md			<--- this doc
├── docs			<--- where you'll put your .md files
│   ├── about.md
│   ├── img			<--- put your favicon.ico in here
│   │   └── favicon.ico
│   └── index.md
└── mkdocs.yml			<--- main config file

2 directories, 5 files
```

Hack around mkdocs.yml to suit 

```bash
run mkdocs serve
open http://127.0.0.1:8000
```

Changes will be dynamically updated in the browser as you write changes.

## Publishing

Use mkdocs build/gt-deploy etc to publish
Exercise left to the reader!
