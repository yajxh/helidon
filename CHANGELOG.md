# Changelog
All notable changes to this project will be documented in this file.

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
### Notes

### Improvements

### Fixes

## [0.10.0] - 2018-09-14
### Notes

In this release we have refactored some HTTP classes and moved
them from `io.helidon.webserver` to a new package `io.helidon.common.http`.
This is an incompatible change and you will need to update your `import`
statements. See
[javadocs](https://helidon.io/docs/0.10.0/apidocs/io/helidon/common/reactive/package-summary.html)
for details.

### Improvements
- Security: improve support for IDCS subject mapping

### Fixes
- Webserver: refactor common HTTP classes to common module
- Documentation: correct various links in documentation
- Security: updates to support chain of JWT and basic auth with OIDC roles
- Archetypes: fix formatting issue in generated pom.xml 

## [0.9.1] - 2018-09-07

### Notes
- Integrate helidon-sitegen 1.0.0, enable the docs

## 0.9.0 - 2018-09-07

### Notes
- Initial source drop on Github

[Unreleased]: https://github.com/oracle/helidon/compare/0.10.0...HEAD
[0.10.0]: https://github.com/oracle/helidon/compare/0.9.1...0.10.0
[0.9.1]: https://github.com/oracle/helidon/compare/0.9.0...0.9.1
