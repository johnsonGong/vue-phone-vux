# vue-mobile-vux

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Run your unit tests
```
npm run test:unit
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).


### 说明 -- 20190215:
1. vue-cli3.x + vux, 移动端开发实践;
2. 因 vux 官方暂未支持 vue-cli3.x, 需要自行手动配置相关参数-1;

```
    configureWebpack: config => {
        vuxLoader.merge(config, {
            options: {},
            plugins: ['vux-ui']
        })
    }
```

安装命令:

```
> npm i vux --save
// OR
> npm install git://github.com/airyland/vux.git#v2
> npm i vux-loader --save-dev
> npm install vue-loader@14.2.2 -D

```


