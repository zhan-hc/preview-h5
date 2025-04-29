# preview-h5
这是一个支持预览pdf的，用的是pdfjs的下载的代码



 ---- new-brower 

|

 ---- old-brower（兼容低版本的浏览器，处理了一些es2020等新语法）



## 使用

只需要把对应的文件夹内的文件部署到对应的服务器里然后通过

```
 window.location.href = [项目前端地址] + '/pdf/web/viewer.html?file=远端PDF地址'
```

就可以访问了
