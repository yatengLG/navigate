# 个人导航
基于[WebStack-Hugo](https://github.com/shenweiyan/WebStack-Hugo)修改而来

##1. 安装hugo
```bash
sudo apt-get install hugo
```

## 2. 修改配置
2.1 背景、标题、等的配置在config.toml中修改
2.2 搜索框部分配置，在/themes/WebStack-Hugo/layouts/partials/content_search.html中修改
2.3 header部分链接、导航链接、友链等在/data/*.yml中修改

## 3. 修改时，可进行实时查看。运行
```bash
hugo server
```

## 4. 最后通过命令生成静态页面内容
```bash
hugo -D
```
## 5. 生成的静态页面在/docs目录下