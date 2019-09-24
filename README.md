# Kinvo React/React Native Guidelines (under construction)

## Summary
  1.  [Folder Structure](#)
  2.  [Naming](#)
  3.  [Classes vs Functions](#)
  4.  [Tests](#)

# Folder structure

## Project

**assets** - \
**common** - Common between both platforms\
**config** - Necessary configurations to applicatiion\
**core** - \
**data** - \
**navigation** - \
**pages** - \
**services** - \
**shared** - \

```
  src/
    assets/
      images/
      fonts/
    common/
    config/
    core/ * Change the name
    data/
      store/
      cache/
    navigation/
    pages/
    services/
    shared/
      modals/
      components/
      hooks/
      styles/
      utils/
      enums/

```

## Component

```
Button/
  components/
  Button.spec.js
  Button.storie.js
  index.js
  presentational.js
  styles.js
```

## Pages

```
AccountPage/
  components/
  modals/
  images/
  AccountPage.spec.js
  index.js
  presentational.js
  styles.js
```

## Services

```
class AccountService {
  static async create() {}
  static async update() {}
  static async delete() {}
}
```

### Custom Hooks

```

```

# Naming

## Files

- Components
  - CamelCase
- Others
  - camelCase

## Variables

- camelCase

## Components

- CamelCase

## Services

- camelCase

# Classes vs Functions

## When to use classes ?

- Utils
- Services
- Mobx Stores

```
class AccountService { }
```

### When to use Functions?

- Components
- Pages

```
function Account() {
  return ();
}
```

# Tests

  - Jest + React Testing Library
