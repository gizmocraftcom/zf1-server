# Changelog

## 2.0.0

Fork of `diablomedia/zendframework1-server`, published as `gizmocraft/zendframework1-server`.

### Breaking changes

- Requires PHP `>=8.5`. Tested on PHP 8.5 and 8.6.
- Package renamed from `diablomedia/zendframework1-server` to `gizmocraft/zendframework1-server`. It requires `gizmocraft/zendframework1-exception` `^2.0.0`.
- No public API changes. The library code needed no PHP 8.5 or 8.6 fixes.

### Other changes

- Dev dependencies upgraded (PHPUnit 13, PHPStan 2.3, php-cs-fixer 3.95, GrumPHP 2.27). Dropped `composer-require-checker`, which has no release for PHP 8.6.
- Tests migrated to PHPUnit 13 attributes. CI runs PHP 8.5 and 8.6.
