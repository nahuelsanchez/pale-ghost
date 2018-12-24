# Pale Ghost

A blank, dev ready, [Ghost](https://ghost.org/) theme. :)

## Introduction letter

Hi there,

Thanks for considering this theme as on option for your [Ghost](https://ghost.org/) blog development plan.

The idea behind this theme is to provide a well structurated, deconstructed in different "modules", style-less theme... a blank theme.

You might find this [Ghost](https://ghost.org/) theme useful if you want to develop your own theme for your blog or for distribution. Use it as a kick off for your future perfect and stunning theme.

Feel free to suggest any code improvement you might think this project needs. Also, ping me if you need some help.

Thanks again,

Nahuel

----

## What to expect

### All Ghost features

It includes all the [Ghost](https://ghost.org/) functionalities a theme can provide, in a modular implementation so it is easy to customize those functionalities or get rid of them.

Probably you will not want everything [Ghost](https://ghost.org/) shows on a theme, but trust me when I say it is easy to remove those stuff you do not want to see instead of add them if they are missing in the first place.

### Code separated into different .hbs files

While trying to avoid complicating the whole code, still some parts of it are divided into different `.hbs` files for easy understanding of what those specific snippets do, and to easily customize them or remove them.

For example, you might find that `page.hbs` is exactly the same as `post.hbs`. The "logical" thing to do is to omit the `page.hbs` so [Ghost](https://ghost.org/) loads the `post.hbs` for default, but both files are there for the reason that this is a developer ready theme.

### No styles

The point with the Pale Ghost theme is to get a good markup with all the [Ghost](https://ghost.org/) features already there.

For that reason, it does not include any CSS because the idea is that you use this theme as a base for your own creation that will include CSS (or SASS, or LESS) for the styling.

What the Pale Ghost theme does have is a `beautify.css` file that highlights the main elements in the markup for a more easy coding. Keep this in the `head.hbs` file if you don not want to see a mess when loading the theme in your browser.

Also, you can find a `ghost.css` file which includes some mandatory CSS class for the GScan validation to pass.

### AMP ready

With some specific AMP modifications separated into specific `.hbs` files for easy maintenance.


### GScan valid

> GScan is designed to check your theme for various issues that we know cause compatibility problems. Our aim is to allow themes to suggest which versions of Ghost they are compatible with via engines in package.json, but to always know for sure by running various checks.

Read more about it in the [GScan documentation](https://themes.ghost.org/docs/gscan).

----

## Screenshots

Remember this project is a blank theme for you to use in order to create your own one. Nevertheless, it includes a `beautify.css` file to make it pretty if you want to see it on the browser without it looking like a real mess.

Go to [assets/screenshots](/assets/screenshots) for some images of how the Pale Ghost theme looks like out of the box.

----

## Installation

Simple as uploading the `pale-ghost.zip` file into the `Settings -> Design` section from the Ghost Admin, or moving the `pale-ghost` folder into `content/themes`.

You can fork and/or clone this repo so it is easy for you to work on the code, or you can download the latest stable release from the [Releases](https://github.com/nahuelsanchez/pale-ghost/releases) section.

----

## Need help?

Visit the [Issues](https://github.com/nahuelsanchez/pale-ghost/issues) section to post your problems so I (or anybody) can give you a hand.

You can also contact me at [nahuel [at] nahuelsanchez.com](mailto:nahuel@nahuelsanchez.com).

----

## Copyright

Copyright (c) 2018 [Nahuel Sanchez](https://www.nahuelsanchez.com/)

Released under the [MIT license](LICENCE).

Portions of code were borrowed from [Casper](https://github.com/TryGhost/casper), copyright (c) 2013-2018 Ghost Foundation. Used under the MIT license.