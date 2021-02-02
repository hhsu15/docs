# docs

## Mkdocs

https://www.mkdocs.org/

### Installation

```
pip install mkdocs

mkdocs new my-project  # create a project dir

```

### Run dev

```
mkdoc serve
```

### Create contents

Create the .md files for your contents and create the navifation in the `mkdocs.yml` file

```yml
site_name: mysite
nav:
  - Home: index.md
  - About: about.md
theme: readthedocs # configure the theme
```

### Changing the Favicon Icon

Create an `img` subdirectory in your docs_dir and copy your custom favicon.ico file to that directory. MkDocs will automatically detect and use that file as your favicon icon.

**does not work for custom theme**

### Build

```bash
mkdocs build

```

### Host in github

```bash

mkdocs gh-deploy

```
