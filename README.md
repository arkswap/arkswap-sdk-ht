# Akrswap SDK

[![code style: prettier](https://img.shields.io/badge/code_style-prettier-ff69b4.svg?style=flat-square)](https://github.com/prettier/prettier)
[![Actions Status](https://github.com/AkrSwap/akrswap-sdk/workflows/CI/badge.svg)](https://github.com/AkrSwap/akrswap-sdk)
[![npm version](https://img.shields.io/npm/v/@akrswap/sdk/latest.svg)](https://www.npmjs.com/package/@akrswap/sdk/v/latest)


In-depth documentation on this SDK is available at [akrswap.org](https://akrswap.org/docs).

## Running tests

To run the tests, follow these steps. You must have at least node v10 and [yarn](https://yarnpkg.com/) installed.

First clone the repository:

```sh
git clone https://github.com/AkrSwap/akrswap-sdk.git
```

Move into the akrswap-sdk working directory

```sh
cd akrswap-sdk/
```

Install dependencies

```sh
yarn install
```

Run tests

```sh
yarn test
```

You should see output like the following:

```sh
yarn run v1.22.4
$ tsdx test
 PASS  test/constants.test.ts
 PASS  test/pair.test.ts
 PASS  test/fraction.test.ts
 PASS  test/miscellaneous.test.ts
 PASS  test/entities.test.ts
 PASS  test/trade.test.ts

Test Suites: 1 skipped, 6 passed, 6 of 7 total
Tests:       3 skipped, 82 passed, 85 total
Snapshots:   0 total
Time:        5.091s
Ran all test suites.
✨  Done in 6.61s.
```
