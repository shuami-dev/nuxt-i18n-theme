## Nuxt i18n and Theme

A Nuxt.js package that provides localization (i18n), and theme management functionalities.
This package aims to simplify the implementation of multilingual support and dynamic them mode in your Nuxt applications.

### Features

- Session management using `sessionStorage`.
- Localization support with dynamic language fetching.
- Theme management for light and dark modes.
- Includes global CSS for styling.
- Share application Id (e.g: event id, project id etc)
- Share other optional parameter (e.g: optional id)

### Installation

To install the package, run the following command:

```bash
npm install @shuami-dev/nuxt-i18n-theme
```

### Usage

1. Add to Nuxt Config\
    In your nuxt.config.ts, add the package to your CSS array:

```ts
export default defineNuxtConfig({
  css: ["@shuami-dev/nuxt-i18n-theme/style.css"],
})