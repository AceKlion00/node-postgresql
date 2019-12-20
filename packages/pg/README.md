# node-postgres

[![Build Status](https://secure.travis-ci.org/brianc/node-postgres.svg?branch=master)](http://travis-ci.org/brianc/node-postgres)
[![Dependency Status](https://david-dm.org/brianc/node-postgres.svg)](https://david-dm.org/brianc/node-postgres)
<span class="badge-npmversion"><a href="https://npmjs.org/package/pg" title="View this project on NPM"><img src="https://img.shields.io/npm/v/pg.svg" alt="NPM version" /></a></span>
<span class="badge-npmdownloads"><a href="https://npmjs.org/package/pg" title="View this project on NPM"><img src="https://img.shields.io/npm/dm/pg.svg" alt="NPM downloads" /></a></span>

Non-blocking PostgreSQL client for Node.js.  Pure JavaScript and optional native libpq bindings.

## Monorepo

This repo is a monorepo which contains the core [pg](https://github.com/brianc/node-postgres) module as well as a handful of related modules.

- [pg-cursor](https://github.com/brianc/node-postgres/tree/master/packages/pg-cursor)


## Documenation

Each package in this repo should have it's own readme more focused on how to develop/contribute.  For overall documentation on the project and the related modules managed by this repo please see:

### :star: [Documentation](https://node-postgres.com) :star:

### Features

* Pure JavaScript client and native libpq bindings share _the same API_
* Connection pooling
* Extensible JS ↔ PostgreSQL data-type coercion
* Supported PostgreSQL features
  * Parameterized queries
  * Named statements with query plan caching
  * Async notifications with `LISTEN/NOTIFY`
  * Bulk import & export with `COPY TO/COPY FROM`

### Extras

node-postgres is by design pretty light on abstractions.  These are some handy modules we've been using over the years to complete the picture.
The entire list can be found on our [wiki](https://github.com/brianc/node-postgres/wiki/Extras).

## Support

node-postgres is free software.  If you encounter a bug with the library please open an issue on the [GitHub repo](https://github.com/brianc/node-postgres). If you have questions unanswered by the documentation please open an issue pointing out how the documentation was unclear & I will do my best to make it better!

When you open an issue please provide:
- version of Node
- version of Postgres
- smallest possible snippet of code to reproduce the problem

You can also follow me [@briancarlson](https://twitter.com/briancarlson) if that's your thing. I try to always announce noteworthy changes & developments with node-postgres on Twitter.

### Professional Support

I offer professional support for node-postgres.  I provide implementation, training, and many years of expertise on how to build applications with Node, Express, PostgreSQL, and React/Redux.  Please contact me at [brian.m.carlson@gmail.com](mailto:brian.m.carlson@gmail.com) to discuss how I can help your company be more successful!

### Sponsorship :star:

[If you or your company are benefiting from node-postgres and would like to help keep the project financially sustainable please consider supporting](https://github.com/sponsors/brianc) to its development.

Also, you can view a historical list of all [previous and existing sponsors](https://github.com/brianc/node-postgres/blob/master/SPONSORS.md).

## Contributing

__:heart: contributions!__

I will __happily__ accept your pull request if it:
- __has tests__
- looks reasonable
- does not break backwards compatibility

If your change involves breaking backwards compatibility please please point that out in the pull request & we can discuss & plan when and how to release it and what type of documentation or communicate it will require.

## Troubleshooting and FAQ

The causes and solutions to common errors can be found among the [Frequently Asked Questions (FAQ)](https://github.com/brianc/node-postgres/wiki/FAQ)

## License

Copyright (c) 2010-2019 Brian Carlson (brian.m.carlson@gmail.com)

 Permission is hereby granted, free of charge, to any person obtaining a copy
 of this software and associated documentation files (the "Software"), to deal
 in the Software without restriction, including without limitation the rights
 to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
 copies of the Software, and to permit persons to whom the Software is
 furnished to do so, subject to the following conditions:

 The above copyright notice and this permission notice shall be included in
 all copies or substantial portions of the Software.

 THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
 IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
 FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
 AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
 LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
 OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
 THE SOFTWARE.