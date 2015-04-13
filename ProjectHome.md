This project is a Java implementation of URI templates and follows as close as possible the URI template notation defined in http://code.google.com/p/uri-templates/ and was inspired by Joe Gregorio's URI Template idea.

## URI Templates ##

URI templates can be used to produce URI given a set of parameters.

For example:
```
  /{username}/home
```
Becomes...
```
  /jsmith/home
```
When supplied with a `username` which value is `jsmith`.

For more documentation on how to use this library to expand URI templates, see
> [How to use URI Templates](http://code.google.com/p/wo-furi/wiki/URITemplateHowTo)

## URI Patterns ##

This library also uses the URI template notation for pattern matching.

The idea stemmed from when we started using the URI template notation in the configuration of our server. We found it useful to be able to use the same notation for matching URIs and finding out possible parameters as for generating URIs.

This library provides additional methods for binding variables to data objects.

For more documentation on how to use this library for URI pattern matching, see the
> [How to use URI Patterns](http://code.google.com/p/wo-furi/wiki/URIPatternHowTo)