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
- [Functions](#functions)
- [Galleries](#galleries)
- [Glossary](#glossary)
- [Go](#go)
- [Landing Pages](#landing-pages)
- [Questions](#questions)
- [Shortcodes](#shortcodes)
- [Taxonomies](#taxonomies)
- [Templates](#templates)
- [Themes](#themes)
- [Variables](#variables)
- [Videos](#videos)
- [tba](#tba)

---

---
## <a name="sticky-notes"></a>Sticky Notes
- Static Site Generator !!!
- The world’s fastest framework for building websites https://gohugo.io/
- Quick Start https://gohugo.io/getting-started/quick-start/
- Forum at https://stackoverflow.com/questions/tagged/hugo
- Other Hugo Community Projects https://gohugo.io/tools/other/
- Written in Go programming language https://golang.org/ which uses multithreading

---
##### To Do
- [ ] build a business landing page with Atlas https://github.com/indigotree/atlas

---
## <a name="anatomy"></a>Anatomy <a style="font-size:small;" href="#top">Back to top</a>

#### Top level anatomy
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
https://gohugo.io/getting-started/directory-structure/

The `default.md` file inside the `archetypes` folder contains pieces of content that are common to all the content of the website!? I allows you to define metadata about your content.

The `config.toml` file is the main settings file of your website.

The `content` folder is where you are going to store all the content about your website: posts, pages, etc.

The `data` folder acts like your database. It stores any data (ie json files) that you want to use on your site.

The `layout` folder gathers all the files defining the layout of the website, ie: header, footer, etc.

The `static` folder stores all the static elements of your website, ie: an image, css or js file, etc. Something that is not going to change from page to page.

The `themes` folder holds any theme you'd like to use for your website.

#### Theme anatomy
```
theme-name
    ├── LICENSE.md
    ├── README.md
    ├── archetypes
    │   └── default.md
    ├── layouts
    │   ├── 404.html
    │   ├── _default
    │   │   ├── list.html
    │   │   └── single.html
    │   └── partials
    │       ├── footer.html
    │       └── header.html
    └── theme.toml
```
Notice how the theme structure mirrors is some ways the site one.

The `layout` folder contains all the `html` layouts we are going to use.

The `theme.toml` is basically the config file about of theme.

---
## <a name="commands"></a>Commands <a style="font-size:small;" href="#top">Back to top</a>
- create new website `$ hugo new site [name of the site]`
- "compile" the site and starts the server `$ hugo server`. If you stop the server in your command line (<kbd>CTRL</kbd>+<kbd>C</kbd>), you won't be able to see the website in your browser anymore :wink:
- `$ hugo server -D`, same as the `hugo server` but it also makes sure it renders the draft pages
- ...

---
## <a name="functions"></a>Functions <a style="font-size:small;" href="#top">Back to top</a>
https://gohugo.io/functions/
- range https://gohugo.io/functions/range/

---
## <a name="glossary"></a>Glossary <a style="font-size:small;" href="#top">Back to top</a>
- Front Matter is metadata, data about data, it allows you to keep metadata attached to an instance of a content type. https://gohugo.io/content-management/front-matter/
- ...

---
## <a name="questions"></a>Questions <a style="font-size:small;" href="#top">Back to top</a>
- What's YAML?
- What's TOML?
- ...

---
## <a name="shortcodes"></a>Shortcodes <a style="font-size:small;" href="#top">Back to top</a>
Shortcodes are simple snippets inside your content files calling built-in or custom templates.
https://gohugo.io/content-management/shortcodes/
- figure
- gist
- syntax highlight
- instagram
- ref and relref
- speakerdeck
- tweet
- vimeo
- youtube
- Custom Shortcodes https://gohugo.io/templates/shortcode-templates/

---
## <a name="templates"></a>Templates <a style="font-size:small;" href="#top">Back to top</a>
https://gohugo.io/templates/

...

---
## <a name="themes"></a>Themes <a style="font-size:small;" href="#top">Back to top</a>
Collection of templates and layouts that build the website for you.
https://themes.gohugo.io/

Once you decided on what theme to use, you need to edit the `config.toml` file by adding the following under the `title` entry.
```
...
theme = "name_of_the_theme"
```

---
## <a name="variables"></a>Variables <a style="font-size:small;" href="#top">Back to top</a>
https://gohugo.io/variables/
- .Content
- .Pages
- .URL

---
## <a name="videos"></a>Videos <a style="font-size:small;" href="#top">Back to top</a>
<a href="https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3" ><img src="http://img.youtube.com/vi/qtIqKaDlqXo/0.jpg"
alt="Introduction to Hugo" width="240" height="180" /></a>
- #1 Introduction to Hugo | Hugo - Static Site Generator
https://www.youtube.com/watch?v=qtIqKaDlqXo&list=PLLAZ4kZ9dFpOnyRlyS-liKL5ReHDcj4G3
- #3 Installing Hugo on Mac | Hugo - Static Site Generator https://youtu.be/WvhCGlLcrF8
- #4 Creating a New Site / Directory Structure | Hugo - Static Site Generator https://youtu.be/sB0HLHjgQ7E
- #5 Installing & Using Themes | Hugo - Static Site Generator
https://youtu.be/L34JL_3Jkyc
- #6 Creating & Organizing Content | Hugo - Static Site Generator https://youtu.be/0GZxidrlaRM
- #7 Front Matter | Hugo - Static Site Generator https://youtu.be/Yh2xKRJGff4
- #8 Archetypes | Hugo - Static Site Generator https://youtu.be/bcme8AzVh6o
- #9 Shortcodes | Hugo - Static Site Generator https://youtu.be/2xkNJL4gJ9E
- #10 Taxonomies | Hugo - Static Site Generator https://youtu.be/pCPCQgqC8RA
- #11 Template Basics | Hugo - Static Site Generator https://youtu.be/gnJbPO-GFIw
- #12 List Page Templates | Hugo - Static Site Generator https://youtu.be/8b2YTSMdMps
- #13 Single Page Templates | Hugo - Static Site Generator https://youtu.be/ZYQ5k0RQzmo
- #14 Home Page Templates | Hugo - Static Site Generator https://youtu.be/ut1xtRZ1QOA
- ...

---
## <a name="tba"></a>tba <a style="font-size:small;" href="#top">Back to top</a>
...

---

---
