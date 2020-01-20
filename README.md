# admin-element-vue

## 自定义配置

### 一、**(必须)** 复制 'vue.config.default.js' 重命名为 ' vue.config.js'
查看 [配置参考](https://cli.vuejs.org/config/).

### 二、**(必须)**  复制 'src/main.ext.default.js' 重命名为 'src/main.ext.js'
满足不同用户、不同环境下，内容可自定义进行增删减

### 三、**(建议)** 开发模式下，不要直接修改 '.env.development'
复制 '.env.development' 重命名为 ' .env.development.local' , 修改对应的参数.

### 四、**(建议)** 生产模式下，不要直接修改 '.env.production'
复制 '.env.production' 重命名为 ' .env.production.local' , 修改对应的参数.

## 项目设置
```
npm ci ( npm install )
```

### 一、Compiles and hot-reloads for development
```
npm run serve
```

### 二、Compiles and minifies for production
```
npm run build
```

### 三、运行单元测试
```
npm run test:unit
```

### 四、运行端到端测试
```
npm run test:e2e
```

### 无、修复
```
npm run lint
```

### 六、精简 svg icon
```
npm run svgo
```