# Fork of Nathan Reyes' <nathanreyes@me.com> VCalendar
It will not be maintained. Please, use original package `v-calendar` [https://github.com/nathanreyes/v-calendar](https://github.com/nathanreyes/v-calendar)

Patches:
- nuxt3 ssr support
- only CJS lib build

# VCalendar Plugin for Vue 3

A Vue plugin for attributed calendars date pickers using Vue 3, Typescript and Rollup.

### Install Plugin

```shell
yarn add v-calendar-ssr@3.0.0-alpha.6-ssr
```

### Usage

```vue
<template>
  <DatePicker v-model="date" />
</template>

<script>
  import { DatePicker } from 'v-calendar-ssr';

  export default {
    components: {
      DatePicker,
    },
    setup() {
      return {
        date: new Date(),
      };
    },
  }
</script>

```
