# Theme Vue Base
基于@vue/theme v1.0.1进行的精简，用于github

## Development Setup

```bash
$ pnpm install
$ npm run dev
```

## Developing with Real Content

1. Clone repositories:

   ```bash
   git clone git@github.com:MShineRay/theme.git
   ```

2. Link theme into docs repo:

   ```bash
   # In ./theme
   pnpm install
   # Make @a0znpm/theme-vue-base available for global linking
   pnpm link --global

### Available Scripts

Here is the list of available scripts that can be used during the development.

```bash
# Boot local dev server.
$ npm run dev

# Build demo, then serve locally. This is for testing
# production build in the local environment.
$ npm run serve

# Run lint via Prettier.
$ npm run lint

# Run type check via tsc.
$ npm run type
```

## License

[MIT](http://opensource.org/licenses/MIT)

Copyright (c) 2021-present
