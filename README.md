prettier 的配置文件

### Install

`npm install --dev @baixiaogou/prettier-config`

### 配置

在`package.json`中
```javascript
    "prettier": "@baixiogou/prettier-config"
```

或者
使用`prettier`配置文件
```javascript
// .pretterc.js
module.exports = {
    ...require('@baixiaogou/prettier-config'),
    // 额外的覆盖配置
}
```
