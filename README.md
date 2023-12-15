
# gpt-4   支持+中文+视频+语音+对话



### 使用方法：

- 1.克隆代码： git clone [ git@github.com:dockercore/Conversation-with-gp4-video.git](https://github.com/dockercore/Conversation-with-gp4-video.git)
- 2.进入项目：Conversation-with-gp4-video
- 3.解决项目依赖：npm install  #安装可能会报错设置淘宝源npm config set registry https://registry.npm.taobao.org ,再试就好了
- 4.新增openai api-keys，打开这个文件 .env 再里面  VITE_OPENAI_KEY= “填写你自己的openai key”，没有的话在这里创建https://platform.openai.com/api-keys
- 5.运行 npm run dev ；
- 6.另外.全局proxy模式 或者 替换的包含api.openai.com 这个域名即可。
- 7.打开 chrome 浏览器或者火狐浏览器输入这个地址：，http://localhost:5173,记得给 摄像头权限和语音权限哈,选择gpt4 点击start 对着 电脑说 中文 即可。


### 使用门槛：
- 使用模型：gpt-4-vision-preview
- 必须是开通openai key付费用户
- 使用端口 443 必须
- 默认调用接口：api.openai.com可以修改成自己的域名
