# Nuxt 3 with Tailwindcss sample

## How to use tailwindcss with Nuxt 3?

1. Add `@nuxtjs/tailwindcss` dependency to your project

```sh
npm install --save-dev @nuxtjs/tailwindcss
```

2. Add it to your modules section in your `nuxt.config`:

```js
export default {
  modules: ['@nuxtjs/tailwindcss']
}
```

3. Create your `tailwind.config.js` by running:

```sh
npx tailwindcss init
```

**That's it!** You can now use Tailwind classes in your Nuxt 3 app ✨
