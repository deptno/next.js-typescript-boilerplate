# changelog

### 6.0.1

- unsupport naver analytics(unsafe)
- update packages
  - next@6.0.1
  - typescript@2.8.3
  - ...etc@latest

### 5.1.0

- update packages
  - typescript@2.7.2
  - next@5.1.0
  - ...etc@latest

### 5.0.5

- ci
- fix
  - Layout.tsx global style is not rendered in output <head> [issue#7](https://github.com/deptno/next.js-typescript-starter-kit/issues/7)

### 5.0.4

- update jest config
- scripts
  - `npm run ts:check` # typescript error check
  - `npm run test:watch`
  - `npm run test:coverage`


### 5.0.3

- fix
  - store-reducer connection
- add enzyme
  - scripts
     - `npm run test`
     - `npm run test:watch`
- rename dev script `npm run dev` > `npm run start:dev`

### 5.0.2

- add storybook

### 5.0.1

- name change
  - next.js-typescript-boilerplate -> next.js-typescript-starter-kit

### 5.0.0

- package.json scripts
  - add `export`, to export static assets(MUST run after `npm run build`)
  - remove `ts:compile` script (no more need to run tsc)

- apply new packages
  - @next/next-typescript

- update packages
  - next@5.0.0
  - react@16.2
  - react-dom@16.2
  - typescript@2.7.1

### 4.1.4

- update packages
  - next@4.1.4
  - react@16.1
  - react-dom@16.1
  - typescript@2.6.1
- update packages client load
  - bootstrap@4.0.0-beta.2
- version align with next

---

## env

### development

#### installation

```
npm install
npm run start:dev # run
```

#### test

```
npm run test # test
npm run test:watch
npm run test:coverage # report coverage
```

### production

```
npm install
npm run build # create .next directory
npm start # start server
```

or

```
npm install
npm run build # create .next directory
npm run export # create .out directory
```

## license

MIT
