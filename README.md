# vue-hacks
Collection of components you shouldn't use with Vue, but you do anyway.

For each individual component, check its HTML.

<br><br><br>

# Vue common issues/mistakes

1. [Change Detection/Reactivity Caveats](https://vuejs.org/v2/guide/reactivity.html#Change-Detection-Caveats) Creating new properties in an existing object without using `Vue.set`
2. Using arrow functions when declaring `data`, `methods`, `watch`ers and `computed`s.
  - https://stackoverflow.com/a/49580445/1850609

# Vue common requests (not necessarily mistakes)

1. Calling deeply nested methods, or parent's methods
  - https://stackoverflow.com/a/49524409/1850609
2. Bubble up custom component events
  - https://stackoverflow.com/a/49524409/1850609
3. When using `v-for` and some flag, want to individualize the flag for each element (instead of having one global flag).
  - https://jsfiddle.net/acdcjunior/L9t5eLey/
  - https://stackoverflow.com/a/49580121/1850609
  - https://stackoverflow.com/a/49580548/1850609
