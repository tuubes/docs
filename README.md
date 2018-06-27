Official documentation of the Tuubes project, written with [MkDocs](https://www.mkdocs.org/).

## License
- The documentation is licensed under CC-BY-SA 4.0 (both the source and the online web pages)
- The code samples and other blocks of code in the documentation are licensed under LGPLv3 like [TuubesCore](https://github.com/tuubes/TuubesCore)

## Development
### Tools installation
- To install MkDocs, [look here](https://www.mkdocs.org/#installation)
- To install the Material theme, [look here](https://squidfunk.github.io/mkdocs-material/)

### Repo structure
- The MkDocs configuration is `mkdocs.yml`, read [the MkDocs user guide](https://www.mkdocs.org/user-guide/configuration/#configuration) and [the Material theme documentation](https://squidfunk.github.io/mkdocs-material/getting-started/) for explanations
- The `docs` folder contains the **online** website which is published by github pages
- The `src` folder contains the MkDocs configuration and the markdown sources
- The `build` folder contains the unpublished website. This folder is **not** in the github repo, it's only local.

### Workflow
1. Edit the markdown source and, if necessary, the `mkdocs.yml`
2. Run `mkdocs serve` or `mkdocs build` to build the website, and test the result
3. (optional) Run `deploy.sh` to copy the build result into the `docs` folder
4. Push to github
