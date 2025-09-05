# 上海好耐电子科技有限公司 官网

目前本网站由[燕先生](https://www.mthorizon.com/contact.html)维护。

代码仓库地址：[https://github.com/mt-horizon/mt-horizon.github.io]

## 目前公司网站情况

1. [https://mthorizon.com]
旧版网站，服务器位于华为云企业门户EWP（原云速建站）服务。现在中文电脑版和中文手机版网站访问后会自动跳转到新版网站2，英文版则不会跳转。

2. [https://www.mthorizon.com]
新版网站，服务器位于Github Pages服务。

3. [https://yanjisheng.mthorizon.com]
开发中的新版网站，服务器位于Github Pages服务（与2是分开的实例）。现自动跳转到2。

4. [http://pro7ff3c2e1.cname.hwcloudsite.cn]
旧版网站，与1是同一个实例，但不会跳转到2，保留旧版网站访问功能。

## 如何上传图片、PDF文件

1. 登录[华为云](https://auth.huaweicloud.com/authui/login.html#/login)。
2. 进入“控制台” - “企业门户EWP（原云速建站）”。
![上传步骤1](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload1.PNG)
3. 点击“网站设计”，然后点击“确定”。请注意新窗口是否被拦截，如被拦截，请在浏览器的“隐私与安全”设置中关闭“阻止弹出式窗口”，或为其添加例外项。
![上传步骤2](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload2.PNG)
4. 点击页面右侧“站点编辑”。
![上传步骤3](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload3.PNG)
5. 点击页面左侧的“文件”，然后点击右上角“上传文件”。
![上传步骤4](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload4.PNG)
![上传步骤5](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload5.PNG)
6. 选择需要上传的文件，注意不要超过规定的大小。文件名最好不要有中文，如果有中文，则会被系统自动重命名为随机的四个英文字母。
7. 在需要使用图片（文件）的地方，输入如下的URL，请把`filename.jpg`替换为上传文件的文件名。
`https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/filename.jpg`

## 如何编辑旧版网站

1. 登录华为云，进入“企业门户EWP（原云速建站）”，点击“网站设计”（这里与前面上传文件的前3步是一样的）。
2. 如果想编辑文章或者产品，点击左侧“文章”或“产品”进行编辑。
3. 如果想编辑其他页面（包括首页），或者编辑javascript跳转，点击右侧“站点编辑”进行编辑。
4. 编辑javascript跳转时，先选择编辑页面为“底版” - “Common”，然后在页面上找到一个“代码”的虚线框。如果找不到，则在页面左侧点击“添加” - “代码”，并拖动到页面上。这里注意，务必不要让一个页面有两个或两个以上的“代码”框，否则两处代码可能会冲突，导致一些不可预期的结果。
![编辑老网站1](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload6.PNG)
![编辑老网站2](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload7.PNG)
5. 选中“代码”框后，点击“编辑”，即可编辑javascript代码。注意，javascript代码应包含在`<script>`标签中。
![编辑老网站3](https://pro7ff3c2e1-pic10.ysjianzhan.cn/upload/upload8.PNG)
6. 旧版网站的中文网站、英文网站，以及电脑版网站和手机版网站，均需要**分别**编辑。