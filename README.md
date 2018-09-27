# Boostrap

A fully responsive, open source, theme for [Ghost](https://ghost.org/) using Bootstrap. 

![The theme](http://i.imgur.com/TtadKo5.png)


## Quick Set Up

So quick. Just kidding, pretty slow still - one day there will be releases to download (but not today). For the time being please follow the development installation.

## Development Set Up

To get going you will need an instance of Ghost do develop in, the quick start is [here](https://github.com/TryGhost/Ghost#quick-start-install). You will also need [SASS](http://sass-lang.com/install) to compile the stylesheets.

Clone the repo into `content/themes/`,

```bash
git clone https://github.com/bitHero/boostrap.git boostrap
```

Install dependencies,

```bash
npm install
```

You now probably want to [build the SASS](#building-sass). Restart your Ghost server and you can select the theme from `Settings > General > Theme`.

### Building SASS

In order to run the following commands, you're going to need the following dependencies:

- ruby
- sass
- grunt

To install the first two, run:

```bash
sudo apt install ruby sass # or whichever package manager your OS uses.
```

To install grunt, use npm:

```bash
npm install -g grunt
```

To make sure the sass is built, run:

```bash
grunt build
```

To activate the Sass watcher,

```bash
grunt watch
```

## Origin

Originally forked from a barebones theme (also called Boostrap) by Matt Lambert.


