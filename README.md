# brume

- Download the ZIP file and extract it’s contents.
- Open *_config.yml* file and enter your site’s URL and add additional configuration or update the existing one if needed.
- Open *_data/brume.yml* file and fill in values for site name (site title), author (your name) and description (blog description). This file contains all the custom information about your page. You can access it using `site.data.brume` object.
- Open *about/index.md* file and add information about you or your site. You can delete this file and directory if not needed.
- Open *_data/links.yml* and add additional links or update the existing ones that you want to be displayed in the navigation menu.
- If you don’t want to use CC BY-NC 4.0 licence for the content then you should change the footer text, which is located in *_layouts/default.html*.
- Change the logo, which can be found in *public/images* folder.
- Build your site and be happy!



I am not a designer so I cannot impress you with breathtaking Jekyll themes, but brume is something that just came to my mind and I had to build it. It is a clean and simple theme, which has an index page that lists all your blog posts divided by the year, a single post page and a layout for any additional pages you might need.

This is how the "Home" page looks like.

![Home](https://raw.githubusercontent.com/aigarsdz/brume/master/screenshots/home.png)

And this is a single post.

![Post](https://raw.githubusercontent.com/aigarsdz/brume/master/screenshots/post_1.png)

![Post. More content examples.](https://raw.githubusercontent.com/aigarsdz/brume/master/screenshots/post_2.png)

## Usage

Brume can be installed just like any other Jekyll theme as described [here](https://jekyllrb.com/docs/themes/#installing-a-theme),
but there are a couple of additional steps you have to take.

1. All the links are defined in a file *_data/links.yml*, therefore you'll have to create a *_data*
directory and put this file there in order for navigation to be displayed.
2. Brume uses `home` layout for the home page (like the default Jekyll theme). All you need to do
is create an *index.html* or *index.md* file with `layout: home`. If you want the home page to be
listed in the navigation you have to add `title` to it's front matter that matches
the title you used for the home page link in the *links.yml* file. Titles are used to indicate
the current page.

## Theme customization

This theme has 4 predefined colors that can be used for links:

- azul
- ruby
- amber
- avocado

By default it uses *avocado*, but if you want to select another one just change the `color_scheme` setting in
*_config.yml* file.

Express your thoughts about brume on Twitter [@aigarsdz](http://twitter.com/aigarsdz), and help me make it better!
