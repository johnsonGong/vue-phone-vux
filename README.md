# vue-phone-vux
vue cli3.x + vux, 移动端开发实践

暂未适配 vue-cli@3.x

# 尝试修改配置
`
 // vux 相关配置,使用vux-ui
    configureWebpack: config => {
        vuxLoader.merge(config, {
            options: {},
            plugins: ['vux-ui']
        })
    }
`