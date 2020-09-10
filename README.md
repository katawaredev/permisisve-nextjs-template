# NextJS Permissive Boilerplate

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Contributor Covenant](https://img.shields.io/badge/Contributor%20Covenant-v2.0%20adopted-ff69b4.svg)](CODE_OF_CONDUCT.md)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![semantic-release](https://img.shields.io/badge/%20%20%F0%9F%93%A6%F0%9F%9A%80-semantic--release-e10079.svg?style=flat-square)](https://github.com/semantic-release/semantic-release)
[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)
[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)

Bootstrap a developer-friendly NextJS [app template](https://github.blog/2019-06-06-generate-new-repositories-with-repository-templates/) configured with:

- [Permissive config](https://github.com/katawaredev/config) toolset
- [Typescript](https://www.typescriptlang.org/)
- Linting with [ESLint](https://eslint.org/), [stylelint](https://stylelint.io/) and [markdownlint](https://github.com/DavidAnson/markdownlint)
- Formatting with [Prettier](https://prettier.io/)
- Linting, typechecking, testing and formatting [commit hooks](https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks) using [`husky`](https://github.com/typicode/husky) and [lint-staged](https://github.com/okonet/lint-staged)
- [Conventional commits](https://www.conventionalcommits.org/) with [commitlint](https://commitlint.js.org/)
- Testing with [Jest](https://jestjs.io/), [Cypress](https://www.cypress.io/), [`@testing-library/react`](https://testing-library.com/docs/react-testing-library/intro) and [`cypress-audit`](https://github.com/mfrachet/cypress-audit)
- Integration with [Visual Studio Code](https://code.visualstudio.com/)
- SEO optimizations
- ~~Sitemap~~ ([see here](https://github.com/vercel/next.js/issues/15508))
- [PWA](https://web.dev/progressive-web-apps/) enabled (production only)
- [Performance metrics](https://nextjs.org/docs/advanced-features/measuring-performance) enabled
- React profiling
- [React error boundary](https://github.com/bvaughn/react-error-boundary)
- [Docker](https://www.docker.com/) support
- [Github Actions](https://github.com/features/actions) for deploying to [Github Pages](https://pages.github.com/) and checks

## Customize for your project

- Remove [Github Workflows](.github/workflow) if not using it
- [/package.json](package.json)
- [/public/favicon.ico](public/favicon.ico)
- [/public/manifest.json](public/manifest.json)
- [/public/images](public/images)
- [/src/seo.json](src/seo.json)
- Environment variables and checks in [next.config.js](next.config.js); definitions in [next-env.d.ts](next-env.d.ts)
- [SocialProfileJsonLd](src/pages/_app.tsx)
- [Create favicons](https://www.favicon-generator.org/)
- Fix references in [CONTRIBUTING.md](CONTRIBUTING.md), [LICENSE](LICENSE) and [issue templates](.github)
- _(optional)_ [Create custom logger](src/utils/logger.ts)

## Resources

- <https://github.com/eggheadio/egghead-next>
- <https://github.com/Lemoncode/react-testing-by-example>
- <https://dev.to/spe_/debugging-next-js-applications-46b6>
- <https://kentcdodds.com/blog/profile-a-react-app-for-performance/>
- <https://itnext.io/pwa-with-next-js-create-next-app-in-2020-%EF%B8%8F-9ee0e1a6313d>
- <https://dev.to/wescopeland/cypress-super-patterns-how-to-elevate-the-quality-of-your-test-suite-1lcf>
