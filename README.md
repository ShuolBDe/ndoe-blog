#node-blog

--20150924更

    需要安装mongodb，祝好
  
--20150928更

    1、接下来需要引入markdown，记得看下说明文档
  
    2、win7下进行到P40，接下来需要看下mac和linux上的开发效果
  
    3、todo：最好先弄下less的问题，突然发现裸写css好蛋疼。。
  
    4、notice：记得启动mongodb。。
    
--20151008

    1、添加了两个新组建（markdown-文章编辑工具、multer-文件上传）
    
    2、notice：req.params和req.body的区别：前者是url上的参数，后者是提交表单中含有的参数
    
    3、todo：了解mongo的update时，更新复合数据（{$set: {post: post}}）以及remove时，删除数据（{w: 1}）的意思
