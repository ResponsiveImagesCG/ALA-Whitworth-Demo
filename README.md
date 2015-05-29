# Whitworth Demos

[These demos](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/) accompany [Element Queries: Once More Unto the Breach](http://alistapart.com/article/element-queries), illustrating the how media queries are flawed in terms of modular design, and the proposed function of an “element query” syntax.

## Demos

*[Demo 1](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo1/index.html)*
A single breakpoint where the layout changes from linear to a primary content area and a sidebar.

*[Demo 2](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo2/index.html)*
Module styles, using a single breakpoint not scoped to any specific contexts. The “featured” module is broken at meduium viewport widths.

*[Demo 3](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo3/index.html)*
Modules now have a second breakpoint and set of styles scoped to the “featured” container context.

*[Demo 4](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo4/index.html)*
“Add to cart” button and “Only 3 left” text are aligned right regardless of available space.

*[Demo 5](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo5/index.html)*
“Add to cart” button and “Only 3 left” text are aligned right based on modules’ available space, using several media queries and duplicated styles.

*[Demo 6](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo6/index.html)*
Module layouts using a single set of “element query” styles.

*[Demo 7](http://responsiveimagescg.github.io/ALA-Whitworth-Demo/demo7/index.html)*
“Add to cart” button and “Only 3 left” text are aligned right based on available space using a single set of “element query” styles.

## Quick Setup

The demos illustrating a theoretical element query syntax (Demo 6 and Demo 7) can only be viewed via HTTP—you can’t just open the index files in your browser, if you’ve cloned the repo and want to tinker with these pages locally. You have two options for running this locally without wading through a bunch of Apache nonsense:

### PHP Server
OSX ships with PHP, which makes it _very_ easy to spin up a quick server. Naviate to the repo’s root directory in your terminal and enter the following:

```shell
$ php -S localhost:7777
```

You should see something like:

```shell
Listening on http://localhost:7777
Document root is /Users/wilto/Sites/ricg/whitworth
Press Ctrl-C to quit.
```

Open http://localhost:7777 in your browser and you’ll see the index page.

### NodeJS

If you don’t have it installed already, you’ll need to install Node from https://nodejs.org/ (or `brew install node`, if you use Homebrew).

Once you have Node installed, navigate to the repo’s root directory in your terminal and enter the following:

```shell
$ npm install
```

This will install the node server’s dependencies. Once complete, enter:

```shell
$ node server.js
```

You should see something like:

```shell
Listening on http://localhost:7777
Document root is /Users/wilto/Sites/ricg/whitworth
Press Ctrl-C to quit.
```

Open http://localhost:7777 in your browser and you’ll see the index page.

