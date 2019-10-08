# Phase 2 Template
This will be the template to use for the delivery of Phase 2 of the DensityDesign Final Design Synthesis Studios 2019/2020.

It uses Jekyll, a static website generator, so you can focus on the content and the visualizations of your research. However, you're free to customize the look and feel of the report by changing colors and fonts. You will find the editable stylesheet inside the folder `_sass/variables.scss`. Remember to link the fonts from Google Fonts in the `<head>` tag on your HTML file under `_layouts/default.html`.

## Step-by-step installation (macOS)
1. Video tutorial for [macOS](https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=2)
1. Video tutorial for [Windows](https://www.youtube.com/watch?v=LfP7Y9Ja6Qc&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3)

### Check your Ruby version
1. To check the Ruby version installed on your Mac, type `ruby -v` in your terminal. You should have installed a version 2.1 or higher.
2. Check your gem version by typing `gem -v`. gem is a package manager needed to install Jekyll.

### Install Jekyll before cloning the repository
To install Jekyll, open the Terminal in a new window and type

```
$ gem install jekyll bundler
```

If you get permissions error, type

```
$ sudo gem install jekyll bundler
```

and then insert your computer's password (it will not show dots or asterisks, so it will seem like you're not typing).

### Run your template locally
Now that you installed Jekyll on your computer, you are ready to start working.

The first time that you download or clone this repository on your computer, open the folder in your terminal (by dragging it onto the terminal icon in the dock, or by opening it through Github) and type

```
$ bundle install
```

to install all the packages needed to make the website work. This command must be run **only the first time**!

Finally, you can type

```
$ bundle exec jekyll serve
```

to see **a live version of your website** on a local server like `http://127.0.0.1:4000/` in your browser.
