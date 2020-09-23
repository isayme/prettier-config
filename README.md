# @isayme/prettier-config

[Prettier](https://prettier.io) 支持 [共享配置](https://prettier.io/docs/en/configuration.html#sharing-configurations).

使用方只需要升级版本即可更新至最新的配置模式, 避免配置变更时, 使用方需要复制新的配置项.

## 如何使用

安装此包: `npm install --save-dev @isayme/prettier-config`

### 方法一

`package.json` 文件中增加属性: `"prettier": "@isayme/prettier-config"`

```
// 示例 package.json
{
  "name": "your node ",
  "version": "v0.0.1",
  "prettier": "@isayme/prettier-config"
}
```

### 方法二(推荐)

在 Prettier 的配置文件中直接填`"@isayme/prettier-config"`, 注意其中使用的是双引号.
