## [3.8.5](https://github.com/jamesfer/cypher-query-builder/compare/v3.8.4...v3.8.5) (2018-11-15)


### Bug Fixes

* tell rollup to output external modules with node style paths ([248f039](https://github.com/jamesfer/cypher-query-builder/commit/248f039)), closes [#68](https://github.com/jamesfer/cypher-query-builder/issues/68)

## [3.8.4](https://github.com/jamesfer/cypher-query-builder/compare/v3.8.3...v3.8.4) (2018-11-06)


### Bug Fixes

* fix conflicting any promise types ([13a9eff](https://github.com/jamesfer/cypher-query-builder/commit/13a9eff))

## [3.8.3](https://github.com/jamesfer/cypher-query-builder/compare/v3.8.2...v3.8.3) (2018-11-04)


### Bug Fixes

* fix generated references to lodash types ([9b27bab](https://github.com/jamesfer/cypher-query-builder/commit/9b27bab))

## [3.8.2](https://github.com/jamesfer/cypher-query-builder/compare/v3.8.1...v3.8.2) (2018-11-03)


### Bug Fixes

* fix how rollup was emitting imports ([110a022](https://github.com/jamesfer/cypher-query-builder/commit/110a022))

## [3.8.1](https://github.com/jamesfer/cypher-query-builder.git/compare/v3.8.0...v3.8.1) (2018-11-03)


### Bug Fixes

* **Where:** bind where clause parameters during build ([bf0d4c2](https://github.com/jamesfer/cypher-query-builder.git/commit/bf0d4c2))

# [3.8.0](https://github.com/jamesfer/cypher-query-builder/compare/v3.7.0...v3.8.0) (2018-10-31)


### Features

* **Remove:** create remove clause ([9d600b6](https://github.com/jamesfer/cypher-query-builder/commit/9d600b6))

# [3.7.0](https://github.com/jamesfer/cypher-query-builder/compare/v3.6.0...v3.7.0) (2018-09-28)


### Bug Fixes

* **Query:** ensure Query.run doesn't throw synchronously ([feebde0](https://github.com/jamesfer/cypher-query-builder/commit/feebde0))


### Features

* support registering observables using any-observable ([57b2089](https://github.com/jamesfer/cypher-query-builder/commit/57b2089))
* support registering promises using any-promise ([5284e6d](https://github.com/jamesfer/cypher-query-builder/commit/5284e6d))

# [3.6.0](https://github.com/jamesfer/cypher-query-builder/compare/v3.5.5...v3.6.0) (2018-09-27)


### Features

* **Connection:** accept neo4j driver options in connection constructor ([d76d65a](https://github.com/jamesfer/cypher-query-builder/commit/d76d65a))

## [3.5.5](https://github.com/jamesfer/cypher-query-builder/compare/v3.5.4...v3.5.5) (2018-08-14)


### Bug Fixes

* **Where:** remove side effects from build ([f664ebe](https://github.com/jamesfer/cypher-query-builder/commit/f664ebe)), closes [#42](https://github.com/jamesfer/cypher-query-builder/issues/42)

## [3.5.4](https://github.com/jamesfer/cypher-query-builder/compare/v3.5.3...v3.5.4) (2018-08-14)


### Bug Fixes

* **OrderBy:** accept direction case-insensitively ([728497d](https://github.com/jamesfer/cypher-query-builder/commit/728497d))

## [3.5.3](https://github.com/jamesfer/cypher-query-builder/compare/v3.5.2...v3.5.3) (2018-08-13)


### Bug Fixes

* **Clause:** match whole variable when inlining using interpolate ([d0588aa](https://github.com/jamesfer/cypher-query-builder/commit/d0588aa))

## [3.5.2](https://github.com/jamesfer/cypher-query-builder/compare/v3.5.1...v3.5.2) (2018-08-13)


### Bug Fixes

* **Where:** make WhereOp class abstract ([5ccd199](https://github.com/jamesfer/cypher-query-builder/commit/5ccd199))

## [3.5.1](https://github.com/jamesfer/cypher-query-builder/compare/v3.5.0...v3.5.1) (2018-07-08)


### Bug Fixes

* **Set:** Only use += in Set when value is an object ([c61a37f](https://github.com/jamesfer/cypher-query-builder/commit/c61a37f))

# [3.5.0](https://github.com/jamesfer/cypher-query-builder/compare/v3.4.1...v3.5.0) (2018-06-18)


### Bug Fixes

* **OrderBy:** remove deprecation notice about old constraint style ([2c35ac9](https://github.com/jamesfer/cypher-query-builder/commit/2c35ac9))


### Features

* **OrderBy:** add new order by constraint style ([2324831](https://github.com/jamesfer/cypher-query-builder/commit/2324831)), closes [#9](https://github.com/jamesfer/cypher-query-builder/issues/9)
