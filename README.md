![artemis scheme](https://cloud.githubusercontent.com/assets/8289896/21179187/f4d3ddf8-c1c0-11e6-8aee-3823cd32834c.png)

## 关于 Dodekatheon
Dodekatheon 是希腊神话中的十二主神。此处取 `Apollo` 的扩展之意。
从 hexo-theme-next 得到灵感，扩展了主题的 Scheme，可以在 `_config.yml` 中设定，一键更换风格。
第一个 Scheme 实验品名叫 `Artemis`，即阿尔忒弥斯。

## 关于 Apollo
以下说明来自原 repo。

### 文档

- [中文文档](https://github.com/pinggod/hexo-theme-apollo/blob/master/doc%2Fdoc-zh.md)
- [Document](https://github.com/pinggod/hexo-theme-apollo/blob/master/doc%2Fdoc-en.md)

### 安装

``` bash
hexo init Blog 
cd Blog 
npm install
npm install --save hexo-renderer-jade hexo-generator-feed hexo-generator-sitemap hexo-browsersync hexo-generator-archive
git clone https://github.com/pinggod/hexo-theme-apollo.git themes/apollo
```

### 启用

修改 `_config.yml` 的 `theme` 配置项为 `apollo`:

```yaml
theme: apollo

# 在归档页面显示所有文章
# 需要上面安装的 hexo-generator-archive 插件支持
archive_generator:
    per_page: 0
    yearly: false
    monthly: false
    daily: false
```

### 更新

``` bash
cd themes/apollo 
git pull
```

### License

MIT


