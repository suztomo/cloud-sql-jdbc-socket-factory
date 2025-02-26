# Changelog

## [1.3.0](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/compare/v1.2.3...v1.3.0) (2021-05-27)


### Features

* add support for Postgres IAM authentication in JDBC and R2DBC connectors ([#490](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/490)) ([3799c78](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/3799c78c257d3aafcb535ca5d339f87dddee8843))


### Bug Fixes

* exclude unreachable optional dependency in r2dbc-core ([#510](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/510)) ([448a353](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/448a35339edde00be43b509239457b1c856d855a))
* require TLSv1.3 when connecting using IAM authentication ([#506](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/506)) ([822a203](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/822a203ce25d49c58cd1d6a843b60da23d16fbd1))

### [1.2.3](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/compare/v1.2.2...v1.2.3) (2021-05-03)


### Bug Fixes

* declare used maven dependencies ([#478](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/478)) ([8483003](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/8483003e2a6b0ac5bc813b9ad8995ff8acdd14ae))

### [1.2.2](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/compare/v1.2.1...v1.2.2) (2021-04-06)


### Bug Fixes

* update dependencies to latest versions ([#452](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/452)) ([48c4c83](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/48c4c837c9aee87277cd64650139597c033e0bae))

### [1.2.1](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/compare/v1.2.0...v1.2.1) (2021-02-16)


### Documentation

* fix error in r2dbc URLs ([#384](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/384)) ([52990d0](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/52990d00254d1e36e8e1fc8e788a6953ef1b3722))

## [1.2.0](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/compare/v1.1.0...v1.2.0) (2020-11-18)


### Features

* add r2dbc support for MS SQL Server ([#328](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/328)) ([fddcc7f](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/fddcc7f42f63caa9fc3026fa6348df5cf0751af8))
* **mysql:** Deprecated the mysql-socket-factory-connector-j-6 artifact ([#342](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/342)) ([c11b63a](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/c11b63a574d4c55c71d191ef2070b5e770b17b9e))
* add SQL Server JDBC support ([#263](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/263)) ([2a60a67](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/2a60a67d3a7a31f4138894e8cc8e5dfd6b3a2c04))
* use regionalized instance ids to prevent global conflicts with sqladmin v1 ([#303](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/303)) ([4bacca4](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/4bacca40b49cc1867a06cf4b2b7cc04c94ad9a07))


## [1.1.0](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/compare/v1.0.16...v1.1.0) (2020-09-15)


### Features

* Add r2dbc support for postgresql and mysql ([#231](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/231)) ([279c619](https://www.github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/279c619e66c83bf94d9168d6ab512512c3042c68))
* Fix dependency convergence errors ([#235](https://github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/issues/235))([462fc4f](https://github.com/GoogleCloudPlatform/cloud-sql-jdbc-socket-factory/commit/462fc4ffeb20b3f7f5243e86619bcecaa24157f0))
