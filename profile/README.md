## Welcome to the „Cronica IT&C” project!

**Cronica IT&C** is a non-governmental, non-profit project initiated by
the Group of Romanian Unix Users (GURU).

### Aims

The project aims at a **reconstitution and long-term preservation
of the IT&C history in Romania**, 
presented in an international context.

### Content

The content is structured around a timeline and an archive.

The timeline consists of dated **Events** (_Evenimente_),
described through more or less detailed articles and followed 
by references.

The archive includes a **Memories** (_Amintiri_) section, with
personal posts of those involved in various events, and the 
**Archive** (_Arhiva_) section, with various PDF documents and other 
binary files.

### Internals

To minimise build times and to avoid space constraints, the content 
is stored in multiple Git repositories, with the images and the
archive in separate projects.

- `[cronica-it.github.io](https://github.com/cronica-it/cronica-it.github.io)` -
  the main location where the web site content is stored
- `[preview](https://github.com/cronica-it/preview)` -
  the Git repository used as a placeholder to publish the preview web
- `[imagini](https://github.com/cronica-it/imagini)` -
  the Git repository where the web site images are stored
- `[arhiva](https://github.com/cronica-it/arhiva)` -
  the Git repository where the PDF and binary files are stored
- `[docusaurus-chronology](https://github.com/cronica-it/docusaurus-chronology) -
  a fork of the Docusaurus project, with enhancements for blogs with historical content
- `[.github`](https://github.com/cronica-it/.github] -
  A special GitHub repository, ith the top README page.

The main web site content is in Romanian. The repositories `imagini` and `arhiva` 
also have Romanian names, since they are logically part of the main web.

The recommended workflow is to add new content first into the
preview site, check it, possibly further improve it, and, when
the author is happy with the result, publish it on the main site.
