# Eugene on HUGO <a name="top"></a>
20171013

last updated on 20171014

---
##### CONTENT:
- [Sticky Notes](#sticky-notes)
  - To Do
- [Anatomy](#anatomy)
- [Boilerplates](#boilerplates)
- [Commands](#commands)
- [Documentation](#documentation)
- [Galleries](#galleries)
- [Go](#go)
- [Landing Pages](#landing-pages)
- [Templates](#templates)
- [Themes](#themes)
- [Videos](#videos)
- [tba](#tba)

---

---
## <a name="sticky-notes"></a>Sticky Notes
- Static Site Generator !!!
- Written in Go programming language https://golang.org/ which uses multithreading
- The world’s fastest framework for building websites https://gohugo.io/
- Forum at https://stackoverflow.com/questions/tagged/hugo
- Other Hugo Community Projects https://gohugo.io/tools/other/

---
##### To Do
- [ ] build a business landing page with Atlas https://github.com/indigotree/atlas

---
## <a name="anatomy"></a>Anatomy <a style="font-size:small;" href="#top">Back to top</a>
```
site-name
    ├── archetypes
    │   └── default.md
    ├── config.toml
    ├── content
    ├── data
    ├── layouts
    ├── static
    └── themes
```
The `default.md` file inside the `archetypes` folder contains pieces of content that are common to all the content of the website!? I allows you to define metadata about your content.

The `config.toml` file is the main settings file of your website.

The `content` folder is where you are going to store all the content about your website: posts, pages, etc.

The `data` folder acts like your database. It stores any data (ie json files) that you want to use on your site.

The `layout` folder gathers all the files defining the layout of the website, ie: header, footer, etc.

The `static` folder stores all the static elements of your website, ie: an image, css or js file, etc. Something that is not going to change from page to page.

The `themes` folder holds any theme you'd like to use for your website.

---
## <a name="commands"></a>Commands <a style="font-size:small;" href="#top">Back to top</a>
- create new website
`$ hugo new [name of the site]`
- ...

---
## <a name="themes"></a>Themes <a style="font-size:small;" href="#top">Back to top</a>
Collection of templates and layouts that build the website for you.
https://themes.gohugo.io/



---
## <a name="videos"></a>Videos <a style="font-size:small;" href="#top">Back to top</a>
<a href="https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3" ><img src="http://img.youtube.com/vi/qtIqKaDlqXo/0.jpg"
alt="Introduction to Hugo" width="240" height="180" /></a>
- Introduction to Hugo | Hugo - Static Site Generator | Tutorial 1
https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3
- Installing Hugo on Mac | Hugo - Static Site Generator | Tutorial 3 https://youtu.be/WvhCGlLcrF8
- Creating a New Site / Directory Structure | Hugo - Static Site Generator | Tutorial 4 https://youtu.be/sB0HLHjgQ7E
- Installing & Using Themes | Hugo - Static Site Generator | Tutorial 5
https://youtu.be/L34JL_3Jkyc
- ...

---
## <a name="tba"></a>tba <a style="font-size:small;" href="#top">Back to top</a>
...

---

---
