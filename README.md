# Integreatly community website

This is a site generator project for Apache Camel. It generates static HTML and
resources that are to be published. 

Tools used to generate the website:
 - [Git](https://git-scm.com/) a source code management tool used to fetch document sources from different 
   github repositories.
 - [Node.js](https://nodejs.org/) a JavaScript runtime used to build the website. You will need to use Node.js version 10.
 - [yarn](https://yarnpkg.com/) a blazing fast dependency and package manager tool used to download 
   and manage required libraries.
 - [Gulp](http://gulpjs.com/) a task automation tool. Used to build the Antora UI theme.
 - [Hugo](https://gohugo.io) a static site generator. Simplified, it takes the
   documentation from the `content` folder and applies templates from `layouts`
   folder and together with any resources in `static` folder generates output in
   the `public` folder.
 - [Antora](https://antora.org/) a documentation site generator. It uses
   Asciidoc documents from different sources in the docs repositories and renders them for inclusion in this website.