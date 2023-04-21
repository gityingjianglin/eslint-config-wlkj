# eslint-config-wlkj

eslint-config-wlkj 提供基于.eslintrc文件extends扩展的基础配置文件

## Usage

### eslint-config-wlkj

默认导出包含所有的ESLint检测规则，包括ECMAScript 6.

安装包
```sh
npm install --save-dev eslint-config-wlkj eslint
```
添加以下内容到.eslintrc 文件
```
{
  "extends": "eslint-config-wlkj"
}
```

### eslint-config-wlkj/legacy

适用一些es5的项目

安装包
```sh
npm install --save-dev eslint-config-wlkj eslint
```
添加以下内容到.eslintrc 文件
```
{
  "extends": "eslint-config-wlkj/legacy"
}
```

### eslint-config-wlkj/react
安装包和一些必要的插件
```sh
npm install --save-dev eslint-config-wlkj eslint babel-eslint eslint-plugin-react eslint-plugin-import eslint-plugin-jsx-a11y
```
添加以下内容到.eslintrc 文件
```
{
  "extends": "eslint-config-wlkj/react"
}
```

## License
MIT
