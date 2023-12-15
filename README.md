#  本项目支持 gpt4视频对话，识别物体



## how to build

- clone this repo, cd into it
- duplicate `.env.example` and name the copy `.env`
- fill out the `VITE_OPENAI_KEY=` value with your OpenAI api key. you must have access to the `gpt-4-vision-preview` model
- you can also try out the Gemini API if you have a key -- fill out `VITE_GEMINI_KEY` in the same `.env`
- then, run:
- `npm install`
- `npm run dev`
- the demo will be running at [http://localhost:5173](http://localhost:5173)

- 1.支持中文语音对话哈
- 2.VITE_OPENAI_KEY= 填写你自己的openai key  没有的话，在这里创建https://platform.openai.com/api-keys 
- 3.全局proxy模式 或者 替换的包含api.openai.com 这个域名即可。
- 4.npm install  #安装可能会报错设置淘宝源npm config set registry https://registry.npm.taobao.org ,再试就好了
- 5.运行 pm run dev ；
- 6.打开 chrome 浏览器或者火狐浏览器，记得给 摄像头权限和语音权限哈 http://localhost:5173 
- 7. http://localhost:5173  选择 gpt4 点击start 对着 电脑说话即可。
note: the in-browser speech recognition works best in Google Chrome
