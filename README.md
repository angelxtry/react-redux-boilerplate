# react-redux-boilerplate

CRA, TypeScript, React, Redux-Saga

## 폴더 구조

```ts
├── public
└── src
    ├── api
    ├── components
    │   ├── Posts
    │   ├── TodoInsert
    │   ├── TodoItem
    │   └── TodoList
    ├── hooks
    │   └── jsonPlaceHolder
    ├── modules
    │   ├── jsonPlaceHolder
    │   ├── lib
    │   └── todos
    └── routes
        ├── Home
        ├── PostDetail
        ├── Posts
        └── TodoApp
```

- api: axios를 이용한 endpoint 관리
- component
  - dumb components
  - store에 직접 접근하지 않는다.
  - hooks를 통해 store에 접근한다.
- hooks
  - store에 직접 접근
- module
  - redux 관련
- routes
  - pages

## 예제

### Todo

Velopert님의 예제 코드

Redux만 사용

```ts
├── public
└── src
    ├── api
    ├── components
    │   ├── TodoInsert
    │   ├── TodoItem
    │   └── TodoList
    ├── hooks
    ├── modules
    │   └── todos
    └── routes
        ├── Home
        └── TodoApp
```

### Post

간단한 Redux-Saga 예제

```ts
├── public
└── src
    ├── api
    ├── components
    │   └── Posts
    ├── hooks
    │   └── jsonPlaceHolder
    ├── modules
    │   ├── jsonPlaceHolder
    │   └── lib
    └── routes
        ├── Home
        ├── PostDetail
        └── Posts
```
