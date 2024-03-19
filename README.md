# Steps to reproduce

## Case @vue/compiler-sfc@2.7.16

Now is `@vue/compiler-sfc@2.7.16`

1. pnpm i
2. format the file `src/App.vue`
3. it shows error:

```
TypeError: Cannot read properties of undefined (reading 'match')
```

## Case @vue/compiler-sfc@3.4.21

1. Edit `package.json` to change the version to `@vue/compiler-sfc@3.4.21`
2. run `pnpm i`
3. format the file `src/App.vue`
4. It works well.
