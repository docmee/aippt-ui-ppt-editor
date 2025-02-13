<p align="center"><img src="https://docmee.cn/favicons/favicon-32x32.png" alt="logo"/></p>
<h1 align="center">文多多 AiPPT</h1>
<p align="center">
	<a href="https://docmee.cn/open-platform" target="_blank">🔗接口文档</a>
	<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
	<a href="https://docmee.cn" target="_blank">🌏官方网站</a>
	<span>&nbsp;&nbsp;•&nbsp;&nbsp;</span>
	<a href="#-商业合作">💬合作交流</a>
</p>


# 文多多PPT编辑器

API 开放平台：https://docmee.cn/open-platform/api

这个编辑器适用于通过 API 接口对接生成 PPT，已经获取到 pptId，后续编辑采用当前项目实现。

支持第一次生成后的动画渲染过程展示和编辑。

编辑器：
<img width="800" src="https://metasign-public.oss-cn-shanghai.aliyuncs.com/github/ppt-iframe-editor.png" style="border:1px solid #ccc">

动画过程：
<img width="800" src="https://metasign-public.oss-cn-shanghai.aliyuncs.com/github/ppt-iframe-editor-animation.gif" style="border:1px solid #ccc">

# ✨ 项目运行

获取 API-KEY: https://docmee.cn/open-platform/authentication

修改 index.html 文件:
```js
var token = 'token_xxx' // TODO 填写你的 token
var pptId = '1877276117434503168' // TODO 填写你的 pptId
var animation = true // TODO 是否开启动画（建议生成PPT第一次展示开启动画，后续进入编辑则不开启）
```

运行命令：
```sh
npm run start
```


# 🤝 商业合作

支持代理 & 私有化部署！

我们的优势，支持定制化行业解决方案，支持原生图表、动画等复杂PPT解析和渲染，支持用户自定义模板，技术方案行业领先，价格行业最低。

官网地址（开放API）：
https://docmee.cn

开放平台（API/UI 接入）：
https://docmee.cn/open-platform


商业合作 & 进群交流：

![qrcode](https://metasign-public.oss-cn-shanghai.aliyuncs.com/github/contact_me_qr.png)
