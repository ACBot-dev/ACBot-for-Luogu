# ACBot

本项目为开发团队内部版本，切勿外传！

## 目录

- <a href="#ksks">快速开始</a>
- <a href="#gy">关于</a>

## <span id="ksks">快速开始</span>

你需要有 [Python 3](https://www.python.org/) 安装。然后运行以下命令安装依赖项并启动 ACBot。

```bash
git clone https://github.com/ACBot-dev/ACBot.git
```

```bash
cd ACBot
```

如果您使用的是 Windows 操作系统，则输入：

```bash
.\install-dependencies.bat
.\run.bat
```

暂不支持 Linux 或其它操作系统。

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

在ACBot的运行目录下，会自动生成一个config.ini文件，你可以通过修改此文件配置ACBot

一下是config.ini的默认内容:
```
[DEFAULT]
browser = edge
edge_path = C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe
edgedriver_path = C:\edgedriver_win64\msedgedriver.exe
chrome_path = C:\Program Files\Google\Chrome\Application\chrome.exe
chromedriver_path = C:\chromedriver_win32\chromedriver.exe
```

过于简单，直接按照个人修改即可，这里不做过多的解释

## <span id="gy">关于</span>

ACBot 是由 ACBot-dev 团队制作的一个 AC 自动机，它是基于 Python 3 与第三方库的程序。

Love From wzhy233 & dctc1494
