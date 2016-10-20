## Site Structure:

```
_includes/          -> page fragments that compose your layout
_layouts/           -> layouts of the page
_posts/             -> posts
_sass/              -> scss files to be compiled
_site/              -> final output: after compile, the result will be here
css/
 └── main.scss      -> main css file
gulp/
 └── tasks/
      └─── task.js  -> gulp tasks for compile
js/
 ├── dev/           -> js files during dev phase
 └── prod/          -> js files after compiling (with browserify)
_config.yml         -> configuration file of jekyll
index.html          -> index of the page

```

## Setup:

- install ruby
- install node
- install gulp
- install all dependency for tasks ( npm install --save-dev <package_name_1> .. <package_name_N> )
