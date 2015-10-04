# ink_Werttin

> An ink theme based on offical theme.

## 使用说明

#### 预览

[首页](https://cloud.githubusercontent.com/assets/9017470/10266999/daf3a772-6ab1-11e5-9449-5bcc47eabbc7.gif)

[文章页](https://cloud.githubusercontent.com/assets/9017470/10267001/06981ca0-6ab2-11e5-9f6e-ad007b3e66b6.gif)

[归档页](https://cloud.githubusercontent.com/assets/9017470/10267003/26286408-6ab2-11e5-97b4-1cf25b14a98a.gif)

#### 下载

见 [Release 页面](https://github.com/Skimige/ink_Werttin/releases) 。

> 目前的最新版本：Beta @ 1.0.2

#### 功能

 - 默认字体为 `Microsoft Yahei UI` ，对 `sans-serif` 和 `serif` 没啥好感
 - 支持 zh (Chinese) / en (English) 两种语言，请修改根目录的 `config.yml` 中此处：

>     lang: zh #也可换成en

 - 为了使加载速度更快，摒弃了大部分图片。其中包括首页作者Avatar、文章下小Avatar等
 - 文章内**不支持头图功能**（此功能被阉割）
 - 支持图片 Lazyload
 - 支持页面平滑滚动
 - more..

#### 打开姿势

下载完整包，把其中唯一的文件夹扔到 ink 根目录。

修改 `config.yml` 中下列字段如下：

修改前：

```
site:
    ...
    theme: theme
    ...
build:
    ...
    copy:
        - theme/css
        - theme/js
        - theme/favicon.ico
        - theme/robots.txt
        - source/images
    ...
```

修改后：

```
site:
    ...
    theme: ink_Werttin
    ...
build:
    ...
    copy:
        - ink_Werttin/css
        - ink_Werttin/js
        - ink_Werttin/favicon.ico
        - ink_Werttin/robots.txt
        - source/images
    ...
``` 

> 另：虽然确实是去掉了首页的几个头像，但在文章页评论框上，作者简介中的头像并没有去掉。
> 所以…别忘了设置avatar & logo！

## License

遵循 [Apache License 2.0](https://github.com/Skimige/ink_Werttin/blob/master/LICENSE)

## 后记

这是本人第一个正式一点的 Repo ，也不求骗几个 Star 了，求别吐槽就行……
