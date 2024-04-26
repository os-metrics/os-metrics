# Welcome to OS Metrics

This project is very early in development. The concept of OS Metrics is a Hub to track the Story of your account. It will feature visual data representations of your luck factor within various parts of the game, from skilling pets to drops from Raids. Since many new users will likely be in late stages of the game, each user will be able to add their own drops to their OS Metrics boss logs (within their dashboard, with the ability to add a screenshot - such as the ones that RuneLite takes automatically) as data points and there will also be data points added automatically via RuneLite plugin, these points will be differentiated in a visual way for the sake of authenticity (other users will be able to see which data points are verifiable and which were added manually). OS Metrics will function in two parts:

 - A RuneLite Plugin: This will track data and send it directly to the users OS Metrics Profile. As of right now I have no idea how to create a RuneLite plugin, so I'll add more here later.
 - A Web App: This will be a Hub where users can view and update their own profiles, view their luck for various pieces of content via graphs with the ability to compare alongside a various graphs and charts, highlighting where they stand versus the average user. Users will also be able to check and see their friend's logs. I would also like to create a feed that shows the luckiest users (only for verifiable drops) within timeframes (daily, weekly, monthly, all time, etc.). Finally, I also want to create a system that clans and groups can use for bingo. Whether it's a seperate bingo system that can utilize the data on OS Metrics, or just the ability to verify drops as they pertain to a bingo board, I don't know yet.

I'll add more to this as I have the time to start working on this project and coming up with more ideas and features. Information on how to contribute below.

## Contributing

OS Metrics makes use of the following features:

- [Mantine](https://mantine.dev)
- [PostCSS](https://postcss.org/) with [mantine-postcss-preset](https://mantine.dev/styles/postcss-preset)
- [TypeScript](https://www.typescriptlang.org/)
- [Storybook](https://storybook.js.org/)
- [Jest](https://jestjs.io/) setup with [React Testing Library](https://testing-library.com/docs/react-testing-library/intro)
- ESLint setup with [eslint-config-mantine](https://github.com/mantinedev/eslint-config-mantine)

All contributions are appreciated - if you are familiar with all of the tools being used and want to write tests and create Storybook components, all the better!

## npm scripts

### Build and dev scripts

- `dev` – start dev server
- `build` – bundle application for production
- `analyze` – analyzes application bundle with [@next/bundle-analyzer](https://www.npmjs.com/package/@next/bundle-analyzer)

### Testing scripts

- `typecheck` – checks TypeScript types
- `lint` – runs ESLint
- `prettier:check` – checks files with Prettier
- `jest` – runs jest tests
- `jest:watch` – starts jest watch
- `test` – runs `jest`, `prettier:check`, `lint` and `typecheck` scripts

### Other scripts

- `storybook` – starts storybook dev server
- `storybook:build` – build production storybook bundle to `storybook-static`
- `prettier:write` – formats all files with Prettier
