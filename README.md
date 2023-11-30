# SurfaceAI
Project Website

## About
This github page is set up with Jekyll. Jekyll is a static site generator with built-in support for GitHub Pages.
The underlying theme is [Minimal Mistakes](https://github.com/mmistakes/minimal-mistakes).

## Deploy changes on GitHub

The content of the website can be changed directly in GitHub in the repository. The content of the main page is in the file _index.md_ . The elements of the footer are in __config.yml_ , the team members in __data/team.yml_ .

## How to locally update and test this page
You need to have Jekyll installed, and Bundler is recommended. Follow [Jekyll Installation Instruction](https://jekyllrb.com/docs/installation/macos/) to install **Ruby** and **Jekyll** with **Homebrew**. Then **Bundler** should be installed with Ruby by default. See also [GitHub docu for Jekyll](https://docs.github.com/de/pages/setting-up-a-github-pages-site-with-jekyll)

To test the page go to the repository folder of this page in your terminal and run `bundle exec jekyll serve` . Follow the instructions in your terminal to open the site in your browser.

Changes will automatically be updated to the site, except of changes in __config.yml_. If you want to see changes of the config file, you need to stop the execution of jekyll (control + c) and rerun `bundle exec jekyll serve` .

### How to choose/change theme
a. If you choose a [Jekyll template supported by Github](https://pages.github.com/themes/). Then in __config.yml_, you need to comment out the line `remote_theme: SOME_REMOTE_THEME_NAME` and write instead `theme: YOUR_CHOSEN_THEME_NAME` . You also have to include `gem: YOUR_CHOSEN_THEME_NAME` in the _Gemfile_  
OR  
b. Choose a remot theme for example [here](https://github.com/topics/jekyll-theme). Then in __config.yml_, you need to comment out the line `theme: SOME_THEME_NAME` and write instead `remote_theme: YOUR_CHOSEN_REMOTE_THEME_NAME` . You also have to comment out `gem: SOME_THEME_NAME` in the _Gemfile_ .

Also add plugins in __config.yml_ and the _Gemfile_ if required by the theme.

Use Bundler to update your Gemfile by running `bundle install` in the terminal.

### The Config File

The content of the config file __config.yml_ depends on the theme. In General there are site settings like _title_ and _url_, build settings like the _theme_, side structure, and which files and folders should be included in the build process. There can also be additional informations for all pages like footer content.


### Individual Pages
You can choose to write your pages with markdown or html.

Every page starts with the **document’s YAML Front Matter** like:

    ---
    layout: splash
    title: "Surface AI"
    header:
      overlay_image: /assets/images/Stockimage.jpg
      overlay_filter: rgba(100, 100, 100, 0.5)
      caption: "Foto: Shutterstock"
    excerpt: "Automatisierte Bestimmung"
    ---

`layout` defines the theme page layout. [Minimal Mistakes Layouts](https://mmistakes.github.io/minimal-mistakes/docs/layouts/#splash-page-layout). It can be set in the front matter or in __config.yml_. The rest is optional.
A layout defines the structure and appearance of a page. It is therefore sufficient to write the content of a page in a simple Markdown or html file.

The main page is an _index.md_ or _index.html_ file.

Subpages need a _permalink_ for their url path:

    ---
    layout: splash
    title: "Impressum"
    permalink: /imprint/
    ---

Subpages are reached via _baseurl_ + _permalink_.

To load dynamical content you can use a template in _Liquid_,

    {% for member in site.data.team %}
        {% include team.html member=member %}
    {% endfor %}

implement the structure of the template in an html file in the __includes_ folder, and list the elements in a yaml file in the __data_ folder.

### Footer

The Minimal Mistakes theme provides two footers. The structure of the _Follow_ footer is implemented and the content is defined in the __config.yml_ file. A costum footer can be defined in _costum.html_ in the folder __includes/footer_

### Navigation

The Minimal Mistakes theme has a structure for a navigation bar implemented. The content has to be written in the __data/navigation.yml_ file:

    main:
      - title: "Home"
        url: /surfaceai


### Multi-Lingual



