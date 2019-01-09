> 博客作者： Cellei  
> 博客地址： http://www.cellei.com  
> 版权声明： 本博客所有文章除特别声明外，均采用 CC BY-NC-SA 4.0 许可协议。转载请注明出处！  

我的博客源文件备份，Issues作为评论仓库，使用 Hexo 搭建。  

~~博客目前托管在 [Coding Pages](https://coding.net/v1/pages/)~~  
~~参考 [使用 WebIDE 搭建 Hexo 个人博客](https://blog.coding.net/blog/webide-hexo)~~  

博客已经放到了阿里云。  

博客主题使用 [hexo-theme-next](https://github.com/theme-next/hexo-theme-next)  
~~参考 [Next 使用文档](http://theme-next.iissnan.com/)~~  

~~评论系统使用 [Gitment](https://github.com/imsun/gitment)~~  
~~参考 [Gitment：使用 GitHub Issues 搭建评论系统](https://imsun.net/posts/gitment-introduction/)~~  

评论系统换成了[Gitalk](https://github.com/gitalk/gitalk)  

### 环境准备
首先安装 [Node.js](https://nodejs.org/)  

clone到本地：  
```
git clone https://gitee.com/cellei/cellei-blog.git
```

进入博客目录：  
```
cd cellei-blog
```

安装Hexo：  
```
npm install -g hexo-cli
```

Hexo环境准备，安装依赖插件：  
```
npm install
```

依赖的插件列表在 `package.json` 文件中。  

