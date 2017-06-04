DEPRECATION NOTE
-----

This project is essentially a hack designed to get [pouchdb-quick-search](https://github.com/nolanlawson/pouchdb-quick-search) to work correctly without creating DDocs. Probably the best path forward is to deprecate this project and have pouchdb-quick-search use [pouchdb-abstract-mapreduce](https://www.npmjs.com/package/pouchdb-abstract-mapreduce).

pouchdb-mapreduce-utils ![semver non-compliant](https://img.shields.io/badge/semver-non--compliant-red.svg)
======

PouchDB utilities used by pouchdb-mapreduce.

### Usage

```bash
npm install --save-exact pouchdb-mapreduce-utils
```

For full API documentation and guides on PouchDB, see [PouchDB.com](http://pouchdb.com/). For details on PouchDB sub-packages, see the [Custom Builds documentation](http://pouchdb.com/custom.html).

### Warning: semver-free zone!

This package is conceptually an internal API used by PouchDB or its plugins. It does not follow semantic versioning (semver), and rather its version is pegged to PouchDB's. Use exact versions when installing, e.g. with `--save-exact`.

### Source

PouchDB and its sub-packages are distributed as a [monorepo](https://github.com/babel/babel/blob/master/doc/design/monorepo.md).

For a full list of packages, see [the GitHub source](https://github.com/pouchdb/pouchdb/tree/master/packages).


