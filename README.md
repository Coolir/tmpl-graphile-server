# __MODULENAME__ [![Build Status](https://travis-ci.org/__USERNAME__/__MODULENAME__.svg?branch=master)](https://travis-ci.org/__USERNAME__/__MODULENAME__)

```sh
npm install __MODULENAME__ 
```

## testing

```sh
createdb test_database
psql test_database < sql/roles.sql
psql test_database < sql/test.sql
yarn test
```