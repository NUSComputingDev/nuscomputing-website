# NUSComputing.com Website
> the new, lightweight NUSComputing.com

## Guide

### Requirements

* [hugo](http://gohugo.io)

### Running for the first time

Other than installing the requirements, there is nothing to do!

### Developing

In order to view your changes, you will need to build the source files and serve them (as viewing them using the `file` protocol might be quite wonky).

Don't fret, however! There is an easy way to do so, using Hugo's built-in server. This is the preferred method as it will automatically build and reload any changes you have made after spinning up the server.

You may want to run Hugo's server with the following flags, like so:

``` bash
$ hugo server -w -t hugo-type-theme
```

### Testing

As Hugo is a static website generator, there are currently no automated test suites. Use your eyes to test.

### Production/Build

Once you are satisfied with the results, you can build the static website using the following command:

``` bash
$ hugo
```

The result will be placed in the `public/` directory.
