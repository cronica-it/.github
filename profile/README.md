## Welcome to the „Cronica IT&C” project!

**Cronica IT&C** is a non-governmental, non-profit project initiated by
the Group of Romanian Unix Users (GURU).

### Aims

The project's goal is to **reconstruct and preserve the Romanian IT&C history**
in a long-term manner, in relation to the international context.

### Web site

The project website is published at
[https://cronica-it.github.io/](https://cronica-it.github.io/).

The main benefit of using a `github.io` sub-domain instead of creating its 
own domain is that it eliminates the risk of being taken off line
in case someone forgets to cover the annual cost of the domain.

In addition, GitHub has a better chance to outlive us and most other
custom domains.

### Content

The content is structured around a **timeline** and an **archive**.

The timeline consists of dated **Events** (_Evenimente_),
described through more or less detailed articles and followed 
by references.

The archive includes a **Memories** (_Amintiri_) section, where people
who participated in various events share their personal stories and
the **Archive** (_Arhiva_) section, where various PDF files and other 
binary files are stored.

### Internals

To minimise build times and to avoid space constraints, the content 
is stored in multiple Git repositories, with the images and the
archive in separate repositories.

- [`cronica-it.github.io`](https://github.com/cronica-it/cronica-it.github.io) -
  the main location where the web site content is stored
- [`preview`](https://github.com/cronica-it/preview) -
  the Git repository used as a placeholder to publish the preview web
- [`imagini`](https://github.com/cronica-it/imagini) -
  the Git repository where the web site images are stored
- [`arhiva`](https://github.com/cronica-it/arhiva) -
  the Git repository where the PDF and binary files are stored
- [`docusaurus-chronology`](https://github.com/cronica-it/docusaurus-chronology) -
  a fork of the Docusaurus project, with enhancements for blogs with historical content
- [`.github`](https://github.com/cronica-it/.github) -
  A special GitHub repository, with the top README page.

### Romanian language

The main web site content is in Romanian. The repositories `imagini` and `arhiva` 
also have Romanian names, since they are logically part of the main web.

### Contact

For discussion in English about GitHub related issues, please use the GitHub 
[Discussions](https://github.com/orgs/cronica-it/discussions) pages.

For announcements and general discussions about the web site content, 
in Romanian, please use the Google Group 
[cronica-it-ro](https://groups.google.com/u/1/g/cronica-it-ro).

To contact the project maintainers, please use the <cronica.it.ro@gmail.com> 
email address.
