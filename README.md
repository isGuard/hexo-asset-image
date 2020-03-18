# hexo-asset-image


自动为hexo中的资产图片提供绝对路径

# 安装

```shell
npm install hexo-asset-image --save
```

# 目录

```shell
MacGesture2-Publish
├── apppicker.jpg
├── logo.jpg
└── rules.jpg
MacGesture2-Publish.md
```

确保 Hexo 目录下的`_config.yml` 的 `post_asset_folder: true` 

使用需要 `![logo](目录名称/logo.jpg)` 图片路径为 `目录名称/logo.jpg`.

# 历史

2020-03-18: 为了配合本地的图片访问添加了目录名称

2018-04-18: 支持 hexo-abbrlink
