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
  enums.js
  index.js
  index.spec.js
  index.storie.js
  presentational.js
  presentational.spec.js
  styles.js
  types.js
```

## Pages

```
AccountPage/
  components/
  modals/
  images/
  index.js
  index.spec.js
  presentational.js
  presentational.spec.js
  styles.js
```

## Services

```
 PushNotificationService/
    enums.js
    index.js
    index.spec.js
    types.js
```

### Custom Hooks

```

```

# Naming

## Files

CamelCase

## Variables

- camelCase

## Components

- CamelCase

## Services

- CamelCase

# Classes vs Functions

## When to use classes ?

- Mobx Stores

```
class UserStore { }
```

### When to use Functions?

- Components
- Pages
- Utils
- Services
- Core

```
function Account() {
  return ();
}
```

# Tests

  - Jest + React Testing Library
