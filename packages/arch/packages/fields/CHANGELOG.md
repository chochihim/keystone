# @arch-ui/fields

## 2.0.3

### Patch Changes

- [`946a52fd`](https://github.com/keystonejs/keystone/commit/946a52fd7057bb73f4ffd465ef51498172926866) [#1995](https://github.com/keystonejs/keystone/pull/1995) Thanks [@Vultraz](https://github.com/Vultraz)! - Updated `react` and `react-dom` to 16.12.0.
- Updated dependencies [[`946a52fd`](https://github.com/keystonejs/keystone/commit/946a52fd7057bb73f4ffd465ef51498172926866)]:
  - @arch-ui/icons@0.0.6
  - @arch-ui/lozenge@0.0.9

## 2.0.2

### Patch Changes

- [`8226eb47`](https://github.com/keystonejs/keystone/commit/8226eb4709ea8ad5773c900eaaa96068d3cb6bad) [#1819](https://github.com/keystonejs/keystone/pull/1819) Thanks [@w01fgang](https://github.com/w01fgang)! - Upgraded `@emotion/core` and `@emotion/styled`.
- Updated dependencies [[`8226eb47`](https://github.com/keystonejs/keystone/commit/8226eb4709ea8ad5773c900eaaa96068d3cb6bad)]:
  - @arch-ui/lozenge@0.0.8

## 2.0.1

### Patch Changes

- [42c3fbc9](https://github.com/keystonejs/keystone-5/commit/42c3fbc9): Upgrade emotion to 10.0.14

## 2.0.0

### Major Changes

- [91fffa1e](https://github.com/keystonejs/keystone-5/commit/91fffa1e):

  - **Blocks**
    - Blocks must now be classes, which implement the `Block` interface.
    - `type` is no longer passed to a Block's constructor (it is expected to know it already).
    - Remove the `embed` block
    - `Block#dependencies` is removed; any depended upon views should be returned from `Block#getAdminViews()`.
    - `Block#extendAdminMeta()` is renamed to `Block#getViewOptions()`.
    - Add new `Block#getAdminViews()` method.
  - **Field Types**
    - `Field#extendViews()` is renamed to `Field#extendAdminViews()`.

## 1.0.0

### Major Changes

- [16befb6a](https://github.com/keystonejs/keystone-5/commit/16befb6a):

  Update the FieldLabel component to take `htmlFor`, `field` and `errors` as props in order to have a consistent mechanism for surfacing the isRequired flag and any access denied errors.

* Updated dependencies [19fe6c1b](https://github.com/keystonejs/keystone-5/commit/19fe6c1b):
  - @arch-ui/theme@0.0.5

## 0.0.5

### Patch Changes

- [81dc0be5](https://github.com/keystonejs/keystone-5/commit/81dc0be5):

  - Update dependencies

## 0.0.4

- [patch][e75c105c](https://github.com/keystonejs/keystone-5/commit/e75c105c):

  - admin revamp

## 0.0.3

- [patch][7417ea3a](https://github.com/keystonejs/keystone-5/commit/7417ea3a):

  - Update patch-level dependencies

## 0.0.2

- [patch] 23c3fee5:

  - Update babel packages and plugins

- [patch] 113e16d4:

  - Remove unused dependencies
