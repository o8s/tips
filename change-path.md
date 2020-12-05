# 修改Node包管理器缓存地址

## npm

```bash
npm config set prefix 'prefix-path'
npm config set cache 'cache-path'
```

## yarn

```bash
yarn config set global-folder 'global-path'
yarn config set cache-folder 'cache-path'
```

将 `prefix-path` 和 `prefix-path\bin` 加入环境变量

