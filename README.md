# Phase 2 Template
This will be the template to use for the delivery of Phase 2 of the DensityDesign Final Design Synthesis Studios 2019/2020.

It uses Jekyll, a static website generator, so you can focus on the content and the visualizations of your research.

1. Video tutorial for [macOS](https://www.youtube.com/watch?v=WhrU9m82Wm8&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=2)

1. Video tutorial for [Windows](https://www.youtube.com/watch?v=LfP7Y9Ja6Qc&list=PLLAZ4kZ9dFpOPV5C5Ay0pHaa0RJFhcmcB&index=3)

*These commands will work for macOS.*

## Check your Ruby version and update it if necessary

The first time that you download or clone this repository on your computer, open the folder in your terminal and type:

```
$ bundle install
```

to install all the packages needed to make the website work. This command must be run **only the first time**!

To install Jekyll, simply clone this repository on your computer, open the Terminal through Github and type

```
$ gem install bundle jekyll
```

If you get permissions error, type

```
$ sudo gem install bundle jekyll
```

and then insert your computer's password.

Once you successfully install Jekyll, you can see **a live version of your website** on a local server like `http://127.0.0.1:4000/` by typing in your Terminal

```
$ bundle exec jekyll serve
```
