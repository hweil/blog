# 指南

## Home Page

+ Home Chapter one
+ Home Chapter two
+ Home Chapter three

[Go Home](./home.md)

## Test Page

**nihao**

+ 测试数据 标题 逆臣

1. skjfsd
2. sdkfjskdf
3. sdkfjsd


``` js
 var name = 'onew'
 console.log(123123 222)
```

```ts{1,6-8}
import type { UserConfig } from '@vuepress/cli'

export const config: UserConfig = {
  title: '你好， VuePress',

  themeConfig: {
    logo: 'https://vuejs.org/images/logo.png',
  },
}
```

@[code js](./guide/test.js)

``` js
一加一等于： {{ 1 + 1 }}

<span v-for="i in 3"> span: {{ i }} </span>
```