# Hugo Theme: Console

A lightweight and responsive theme for Hugo, inspired by the Linux console designed for fast performance, with an average page load time of just 0.5 seconds.

![Console](https://github.com/mrmierzejewski/hugo-theme-console/blob/master/images/preview.png?raw=true)

## Live demo

* [https://mrmierzejewski.com/hugo-theme-console/](https://mrmierzejewski.com/hugo-theme-console/)

## Installation

From the root of your Hugo site, clone the theme into ```themes/hugo-theme-console``` by running :

```
$ git submodule add https://github.com/mrmierzejewski/hugo-theme-console.git hugo-theme-console
```
    
See the [Hugo documentation](https://gohugo.io/hugo-modules/theme-components/) for more information.

## Configuration

Set theme parameter in your config file:

```
theme = "hugo-theme-console"
```

## Quick start

After installation, take a look in the `exampleSite` folder at. This directory contains an example config file and the content for the demo.

```
  exampleSite
  ├── config.toml
  ├── content
  │   ├── about
  │   │   └── index.md
  │   └── photos
  │   │   └── arizona-us
  │   │       ├── arizona-us.jpg
  │   │       └── index.md
  │   └── posts
  │       └── introduction
  │           └── index.md
  ├── layouts
  │
  └── static
```

Copy at least the `config.toml` in the root directory of your website. Overwrite the existing config file if necessary.

Hugo includes a development server, so you can view your changes as you go -
very handy. Spin it up with the following command:

```
hugo serve
```

Now you can go to [http://localhost:1313](http://localhost:1313) and the theme should be visible.

## Example Site

To run the example site, please type the following command.

```
make hugo-server
```

## License

Copyright © 2024 [Marcin Mierzejewski](https://mrmierzejewski.com/)

The theme is released under the MIT License. Check the [original theme license](https://github.com/panr/hugo-theme-terminal/blob/master/LICENSE.md) for additional licensing information.
