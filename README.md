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

### Adding New Event to Event Page

1. Open terminal in root folder, create new event type markdown file by typing:
``` bash
$ hugo new event/<event name>.md
```
2. Fill in parameters in front matter: 
> * externalLink (link to event page)
> * image (image should be in ./static/img/event)
> * modal (modal id)
> * title
3. Add description as content below front matter.
4. That's it :D

