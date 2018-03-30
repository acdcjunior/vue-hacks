# vue-hacks
Collection of components you shouldn't use with Vue, but you do anyway.

For each individual component, check its HTML.


# Vue common mistakes

- Creating new properties in an existing object without using `Vue.set`
- Using arrow functions when declaring `data`, `methods`, `watch`ers and `computed`s.

# Vue common requests (not necessarily mistakes)

- Calling deeply nested methods, or parent's methods
- Bubble up custom component events
- When using `v-for` and some flag, want to individualize the flag for each element (instead of having one global flag).
  - https://stackoverflow.com/a/49580121/1850609
  - https://stackoverflow.com/a/49580548/1850609
