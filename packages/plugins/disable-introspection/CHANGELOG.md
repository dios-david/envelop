# @envelop/disable-introspection

## 3.1.0

### Minor Changes

- Updated dependencies [78b3db2]
- Updated dependencies [f5eb436]
  - @envelop/core@2.1.0

## 3.0.0

### Patch Changes

- Updated dependencies [4106e08]
- Updated dependencies [aac65ef]
- Updated dependencies [4106e08]
  - @envelop/core@2.0.0

## 2.0.0

### Patch Changes

- Updated dependencies [d9cfb7c]
  - @envelop/core@1.7.0

## 1.2.1

### Patch Changes

- b1a0331: Properly list `@envelop/core` as a `peerDependency` in plugins.

  This resolves issues where the bundled envelop plugins published to npm had logic inlined from the `@envelop/core` package, causing `instanceof` check of `EnvelopError` to fail.

- Updated dependencies [b1a0331]
  - @envelop/core@1.6.1

## 1.2.0

### Minor Changes

- 090cae4: GraphQL v16 support

## 1.1.0

### Minor Changes

- 04120de: add support for GraphQL.js 16

## 1.0.0

### Major Changes

- 40bc444: v1 major release for envelop packages

## 0.2.1

### Patch Changes

- 28ad742: Improve TypeScript types

## 0.2.0

### Minor Changes

- effc18b: add optional conditional "disableIf" with context and params

## 0.1.0

### Minor Changes

- eb6f53b: ESM Support for all plugins and envelop core

## 0.0.1

### Patch Changes

- d1c0ce0: Initial implementation of the plugin.
