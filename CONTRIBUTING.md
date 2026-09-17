# Contributing

Discuss focused changes in the [issue tracker](https://github.com/altophp/json-patch/issues).
Install development dependencies with `composer install` and run `composer qa`
for style, static analysis, and tests. `composer cs:fix` applies style fixes.
The library supports PHP 8.3; check Composer's current development requirements
when choosing the runtime for its tooling.

Add tests for operation order, pointer escaping, unchanged original documents,
and replaying generated patches. Documentation examples should print the target
document, not only assert that it matches.
