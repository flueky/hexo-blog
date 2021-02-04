## hexo-blog

hexo 博客示例

第一次使用，需要执行 `npm install` 安装 **hexo** 有关文件。

使用git clone --branch [tags|branches] [git地址]命令导出代码。

```Shell
# 导出主分支
git clone --branch master https://github.com/flueky/hexo-blog.git 
# 导出 v0.0.2 tag 
git clone --branch v0.0.2 https://github.com/flueky/hexo-blog.git 
```

### 版本说明

#### v0.0.1

初始 hexo 配置。

#### v0.0.2

使用 material-x 主题。

主题直接拷贝自 [xaoxuu](https://xaoxuu.com/)。

```Shell
git clone https://github.com/xaoxuu/hexo-theme-material-x themes/material-x
```

主题使用了搜索功能，需要安装依赖。

```Shell
npm i -S hexo-generator-search hexo-generator-json-content
```

**此处已经配置好依赖，执行 `npm install` 时默认安装。**

#### v0.0.3

添加了 分类 、标签 、友链等缺少的页面。

#### v0.0.4

添加背景音乐、点击效果、评论、字数统计、百度统计、雪花效果、运行时间、动态线条、动态彩带。

#### v0.0.5

添加透明效果。

#### v0.1.0

更新hexo版本。
移除source/_posts和source/_drafts目录，改用快捷方式。