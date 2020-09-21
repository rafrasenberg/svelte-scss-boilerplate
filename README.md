# Svelte SCSS starter

Basically just the Svelte.js starter template, but then with SCSS integrated. Using this as a personal boilerplate.

## How to use?

In any .svelte file just use the `lang="scss"` flag when applying styles. So:

```
<style lang="scss">
    body {
        background-color: $black;
    }
</style>
```

Variables can be used globally when defined in `styles/_variables.scss`!
