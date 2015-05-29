# Whitworth Demos

These demos accompany [Element Queries: Once More Unto the Breach](http://alistapart.com/article/element-queries), illustrating the how media queries are flawed in terms of modular design, and the proposed function of an “element query” syntax.

## Quick Setup

The demos illustrating a theoretical element query syntax (Demo 6 and Demo 7) can only be viewed via HTTP—you can’t just open the index files in your browser. So, you have two options for running this locally without wading through a bunch of Apache nonsense:

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

