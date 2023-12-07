This is the Lensfun website repository and its content will be automatically published as a [GitHub Page](https://pages.github.com/) at the project URL https://lensfun.github.io/.

See the [GitHub Pages Help](https://help.github.com/en/categories/github-pages-basics) for further details how to use and configure this repo.

### Technical background ###

The website is based on __Jekyll__ which is a static website generator. See http://jekyllrb.com/ for more information.

Changes in the repo will automatically trigger a build of the website on the GitHub server. During this process, files with an extension `.md` will be processed by Jekyll and transformed into HTML code. Folders and files beginning with an underscore are reserved for Jekyll and contain either site content and templates or config files.

All other files and folders are simply copied over to the website destination. For example, creating a file `testfolder/website.html` in the repo will make this file accessible at `https://lensfun.github.io/testfolder/website.html`. This also works for small binary files like images.

For testing and to see and fix errors reported by Jekyll, one can also build the website locally:

* Install Ruby

      sudo apt-get install ruby-full

* Install Jekyll with bundler in the root folder of this repo

      bundle install

* Run Jekyll to build the html files and serve the whole website with a local web server at http://localhost:4000/

      bundle exec jekyll serve

* All web content can be found in the created `_site/` subfolder and may be  packaged into the documentation or uploaded to any web server. Use `bundle exce jekyll build` to only build without starting a local web server.
