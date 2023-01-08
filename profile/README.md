# RDF/JS Base

The packages in this organization implement many basic features required to handle RDF data in JavaScript.
Interfaces defined in [RDF/JS](http://rdf.js.org/) specifications are used if available.
Other interfaces are aligned to the concepts of RDF/JS and EcmaScript standards.

## RDF-Ext

The combined usage of multiple `@rdfjs-base` packages can be complicated.
To simplify the usage, [RDF-Ext](https://rdf-ext.org/) does all the factory handling for you.
It is recommended for most people.
Using individual `@rdfjs-base` packages could be of interest once you think about bundle size.
Before you reach that point, you should just stay with [RDF-Ext](https://rdf-ext.org/).

## ESM vs. CommonJS

Most packages already use [ESM](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Modules) only.
They are intentional ESM only, so they don't require a build system and keep the time required for maintenance low.
If you need a [CommonJS](https://nodejs.org/docs/latest/api/modules.html) version of a package, you should check for older major versions.
Don't worry about a package being outdated.
New features aren't backported, but reported bugs will be fixed.

## Contributing

Contributions are very welcome.
Please see the [contributing guidelines](https://github.com/bergos/open-source-software/blob/master/CONTRIBUTING.md) for more details.  
