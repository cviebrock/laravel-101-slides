# Laravel 101 Slides

These are the slides I used for my "Laravel 101" presentation at the Winnipeg PHP Meetup on March 26, 2014.

The slideshow framework is **reveal.js**: a framework for easily creating beautiful presentations using HTML. [Check out the live demo](http://lab.hakim.se/reveal-js/) or [fork it](https://github.com/hakimel/reveal.js).

## Viewing the slides

If you just want to see the slides, you can [download the PDF](https://github.com/cviebrock/laravel-101-slides/raw/master/Laravel-101.pdf).

To install reveal.js and run the slideshow locally, you'll need to do the following:

1. Install [Node.js](http://nodejs.org/)

2. Install [Grunt](http://gruntjs.com/getting-started#installing-the-cli)

3. Clone or download this repo
```sh
$ git clone https://github.com/cviebrock/laravel-101-slides.git
```

4. Navigate to the slide folder
```sh
$ cd laravel-101-slides
```

5. Install dependencies
```sh
$ npm install
```

6. Serve the presentation
```sh
$ grunt connect
```

7. Open <http://localhost:8888> to view the presentation

You can change the port by using `grunt connect --port 8001`.


## Thanks

Thanks to [Skullspace](http://skullspace.ca) for hosting the meetup and to [Tipping Canoe](http://tippingcanoe.com) for support and pizza!


## License

MIT licensed
Copyright (c) 2014 Colin Viebrock, http://viebrock.ca

Background images used in the presentation were collected from the internet and are copyright their respective owners.  Submit an issue if you are the original owner and would like it removed.

Reveal.js is copyright (C) 2013 Hakim El Hattab, http://hakim.se
