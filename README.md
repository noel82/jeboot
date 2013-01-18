# JeBoot
## A jekyll bootstrap template thing

`JeBoot` is a template system for the [jekyll](http://github.com/mojombo/jekyll) static site generator program.
Fill the \_config.yml with the appropriate values and just run `rake` to go.
It provides the basic structure for your `Jekyll` powered projects.

## Usage
Just clone this repository, fill in the correct values on the `_config.yml` file and start coding.

## Pages' structure

The base layout strucure is embodied in `_layouts/base.html`
Here we have the following items:
- An `header` 
- A `nav` section included from `_includes/navigation.html`
- An `h1` with id `site_title`
- The page content
- A `footer` element

Every item described here, has an associated style in the `css/styles.less` file: you must customize it to your needs.
Likewise, in the `css` directrory there's a phone.less file for styling your mobile experience. :) (And a bunch of other stuff too...)
