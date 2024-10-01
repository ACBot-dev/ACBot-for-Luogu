# ACBot

Auto AC Bot for Luogu (已被害死)

## 目录

- <a href="#ksks">快速开始</a>
- <a href="#gy">关于</a>

## <span id="ksks">快速开始</span>

对于Edge浏览器用户，你需要安装EdgeDriver：
```html
https://developer.microsoft.com/en-us/microsoft-edge/tools/webdriver/
```

对于Chrome浏览器用户，你需要安装ChromeDriver:

国内镜像:
```html
https://chromedriver.storage.googleapis.com/index.html?spm=a2c6h.12873639.article-detail.7.8c827220LeCh0h
```

官网(需翻墙):
```html
https://developer.chrome.com/docs/chromedriver/downloads?hl=zh-cn
```

就是这样！

## <span id="ksks">配置ACBot</span>

在 % appdata %//ACBot 下，会自动生成一个名为 ACBot 的文件夹，你可以通过修改此文件夹下的子目录 Config 内的Config.ini 文件来配置ACBot

一下是config.ini的默认内容:
```
[DEFAULT]
browser = edge
edge_path = C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe
edgedriver_path = C:\edgedriver_win64\msedgedriver.exe
chrome_path = C:\Program Files\Google\Chrome\Application\chrome.exe
chromedriver_path = C:\chromedriver_win32\chromedriver.exe
anti-comments = True
anti-non-code = True
```

过于简单，直接按照个人修改即可，这里不做过多的解释

## <span id="gy">关于</span>

ACBot 是由 ACBot-dev 团队制作的一个 AC 自动机，它是基于 Python 3 与第三方库的程序。
