---
title: Directories
---

Articles are stored in the content directory.  Associated resources, such as images, are stored in the media directory. The `package.json` and `_config.yml` files are used to configure the project.

| Directory            | Description                                                      |
|----------------------|------------------------------------------------------------------|
| `./_config.yml`      | General options to configure the project                         |
| `./content`          | Articles                                                         |
| `./dist`             | Rendered site data and staging area for source files              |
| `./dist/src`         | Unrendered source files                                        |
| `./dist/site`        | Rendered content                                               |
| `./media`            | Various resources for the project (images, imported content, etc.) |
| `./package.json`     | Configuration settings                                          |

All content changes are monitored; any change triggers a regeneration of the content. After a structural change (for example, adding a sub-directory or new article) a restart is required.
