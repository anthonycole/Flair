# Flair - Sennza's WordPress Foundation Starter theme

This is WordPress starter theme that uses Foundation, Grunt and libsass!

## Prerequisites

This setup works well with [Chassis](https://github.com/Chassis/Chassis).

## Requirements

You'll need to have the following items installed before continuing.

  * [Node.js](http://nodejs.org): Use the installer provided on the NodeJS website.
  * [Grunt](http://gruntjs.com/): Run `[sudo] npm install -g grunt-cli`
  * [Bower](http://bower.io): Run `[sudo] npm install -g bower`

## Quickstart

```bash
git clone git@github.com:sennza/Flair.git yourtheme
npm install && bower install
```

While you're working on your project, run:

`grunt`

And you're set!

## Directory Strucutre
  * `assets/`: Any media (SCSS, JS, Images) should be contained in this folder.
  * `assets/scss/_settings.scss`: Foundation configuration settings go in here
  * `assets/scss/app.scss`: Application styles go here
  * `parts`: All `get_template_parts` are stored in here
  * `templates`: All Page Templates are stored in here
  * `inc`: Any complex filters and actions should go in here to reduce the bloat of `functions.php`. Note: Any files in the root will be automagically included in your theme.

## Foundation Support

In functions.php there are some commented out `add_theme_support` lines which when uncommented will add theme suppport for Foundations:

  * [Interchange](http://foundation.zurb.com/docs/components/interchange.html)
  * [Top Bar](http://foundation.zurb.com/docs/components/topbar.html)
  * [Sticky Top Bar](http://foundation.zurb.com/docs/components/topbar.html)
  * [Magellan](http://foundation.zurb.com/docs/components/magellan.html)
  * [Orbit](http://foundation.zurb.com/docs/components/orbit.html)
  * [Clearing](http://foundation.zurb.com/docs/components/clearing.html)
  * [Abide](http://foundation.zurb.com/docs/components/abide.html)
  * [Reveal](http://foundation.zurb.com/docs/components/reveal.html)
  * [Alert](http://foundation.zurb.com/docs/components/alert_boxes.html)
  * [Tooltip](http://foundation.zurb.com/docs/components/tooltips.html)
  * [Joyride](http://foundation.zurb.com/docs/components/joyride.html)
  * [Equalizer](http://foundation.zurb.com/docs/components/equalizer.html)
  * [Accordion](http://foundation.zurb.com/docs/components/accordion.html)
  * [Tabs](http://foundation.zurb.com/docs/components/tabs.html)