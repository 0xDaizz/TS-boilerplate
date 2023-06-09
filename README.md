# TS-boilerplate

Typescript + ESlint + Prettier boilerplate for pnpm.

## 절차 :

0. Install TS

```
pnpm i -g typescript

tsc --init  // generate tsconfig.json
```

1. Install ESlint

```
pnpm i -D eslint eslint-config-airbnb-typescript eslint-config-airbnb-base eslint-plugin-import eslint-plugin-prettier eslint-config-prettier
```

-   eslint-config-airbnb-typescript : TS를 위한 airbnb 구성
-   eslint-config-airbnb-base : airbnb 구성인데, react 제외한 거
-   eslint-plugin-import : ES6의 import 구문 지원
-   eslint-plugin-prettier : Prettier의 포맷팅을 eslint에 추가
-   eslint-config-prettier : eslint에서, prettier와 겹치는 것 비활성화

2.

```
@typescript-eslint/eslint-plugin@latest @typescript-eslint/parser@latest
```

3.

```
pnpm i -D prettier
```
