# OneWord
**Lightweight random natural statement output API,no datebase and fast.**
Project url:[https://github.com/VikACG/oneword](https://github.com/VikACG/oneword)
Please choose your language what you want read:
 - [English](#English)
 - [简体中文](#%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87)
 - [正體中文](#%E6%AD%A3%E9%AB%94%E4%B8%AD%E6%96%87)
# English
This is a natural statement output API for Vikasu that does not require a database connection. It reads the pre-stored statements in the TXT file to randomly output the content.
## Installation
Extract the files in the directory to any location, as long as you can GET or POST through the network. Note that the program must include the following files to work properly.
 - index.php
 - wordlist.txt

Where *wordlist.txt* can be changed to any name according to your needs, you only need to modify it in line 10 of the index.php code:

    $file = file($path."/wordlist.txt");
## Customize the contents of random output
This project has pre-stored some natural statements in *wordlist.txt*, all of which come from the popular Chinese online novels "**Xiling Empire**" and "**Yìcháng shēngwù jiànwén lù**", if you like these Sentence, may wish to support the original author [Yuan Tong](https://my.qidian.com/author/4362948).
List of cited books:
 1. [Xiling Empire](https://book.qidian.com/info/1463673)
 2. [Yìcháng shēngwù jiànwén lù](https://book.qidian.com/info/3242304)

The program will randomly read a line of text output, that is, the statement is limited to one line per line. No line break will output the entire line of text.
## Output content to the specified location on the page
Since the API can achieve a variety of output methods, we are here to teach you the most common output method: output the specified content to the specified content of the web page.
Assuming your project deployment address is https://api.exmaple.com/oneword/index.php, insert the following code into the location you need to output:

    <script type="text/javascript" src="https://api.exmaple.com/oneword/index.php?format=js&charset=utf-8"></script>
    <div id="oneword"><p><script type="text/javascript">oneword()</script></p></div>
Replace https://api.exmaple.com/oneword/index.php in the src definition in the script element on the first line of the code with your project deployment address, which remains the same except for special requirements.
## Open source statement
This project uses MIT License. Please follow the agreement during secondary development. If you think the project is good, you don't need to donate, just use and promote our service to your friends:

 - [VikACG For Web - Happy Home of ACGer](https://www.vikacg.com)
 - [VikACG Mobile App - Discover ACG resources anytime, anywhere](https://app.vikacg.com)

In the end, thank you for choosing this open source program.
# 简体中文
这是一款Vikasu自用的无需数据库连接的自然语句输出API，通过读取TXT文件中预先存储的语句来随机输出内容。
## 安装
将目录中的文件解压至任意位置，只要您可以通过网络可以GET或POST即可，需要注意的是程序必须包含以下文件才能正常工作
 - index.php
 - wordlist.txt

其中 *wordlist.txt* 可以根据您的需求更改为任何名称，您仅需要在index.php的代码的第10行修改即可：

    $file = file($path."/wordlist.txt");
## 自定义随机输出的内容
本项目已经在*wordlist.txt* 预先存储好了一些自然语句，这些语句均来自中文人气网络小说《**希灵帝国**》和《**异常生物见闻录**》，如果您喜欢这些句子，不妨支持一下原作者[远曈](https://my.qidian.com/author/4362948)吧。
引用书籍列表：
 1. [希灵帝国](https://book.qidian.com/info/1463673)
 2. [异常生物见闻录](https://book.qidian.com/info/3242304)

程式会随机读取一行文字输出，也即语句每行仅限一条，没有换行符将会把整行文字输出。
## 输出内容到网页上指定位置
由于该API可以实现的输出方式多样，我们在此教您最常用的输出方法：输出指定内容到网页的指定内容。
假设您的项目部署地址为https://api.exmaple.com/oneword/index.php，那么请将以下代码插入您需要输出的位置：

    <script type="text/javascript" src="https://api.exmaple.com/oneword/index.php?format=js&charset=utf-8"></script>
    <div id="oneword"><p><script type="text/javascript">oneword()</script></p></div>
请将代码第一行中script元素中的src定义中的https://api.exmaple.com/oneword/index.php替换成您的项目部署地址，除特殊需求外其他保持不变。
## 开源声明
本项目采用MIT License，在进行二次开发时请遵守该协议，如果您觉得该项目不错，您不需要捐赠，仅需要使用并向您的朋友推广我们的服务：

 - [维咔VikACG网页版-肥宅的欢乐家园](https://www.vikacg.com)
 - [维咔VikACG App-随时随地发现ACG资源](https://app.vikacg.com)

在最后，感谢您选择这款开源程序。

# 正體中文
這是一款Vikasu自用的無需數據庫連接的自然語句輸出API，通過讀取TXT文件中預先存儲的語句來隨機輸出內容。
## 安裝
將目錄中的文件解壓至任意位置，只要您可以通過網絡可以GET或POST即可，需要注意的是程序必須包含以下文件才能正常工作
 - index.php
 - wordlist.txt

其中 *wordlist.txt* 可以根據您的需求更改為任何名稱，您僅需要在index.php的代碼的第10行修改即可：

    $file = file($path."/wordlist.txt");
## 自定義隨機輸出的內容
本項目已經在 *wordlist.txt* 預先存儲好了一些自然語句，這些語句均來自中文人氣網絡小說《**希靈帝國**》和《**異常生物見聞錄**》，如果您喜歡這些句子，不妨支持一下原作者[遠曈](https://my.qidian.com/author/4362948)吧。
引用書籍列表：
 1. [希靈帝國](https://book.qidian.com/info/1463673)
 2. [異常生物見聞錄](https://book.qidian.com/info/3242304)

程式會隨機讀取一行文字輸出，也即語句每行僅限一條，沒有換行符將會把整行文字輸出。
## 輸出內容到網頁上指定位置
由於該API可以實現的輸出方式多樣，我們在此教您最常用的輸出方法：輸出指定內容到網頁的指定內容。
假設您的項目部署地址為https://api.exmaple.com/oneword/index.php，那麼請將以下代碼插入您需要輸出的位置：

    <script type="text/javascript" src="https://api.exmaple.com/oneword/index.php?format=js&charset=utf-8"></script>
    <div id="oneword"><p><script type="text/javascript">oneword()</script></p></div>
請將代碼第一行中script元素中的src定義中的https://api.exmaple.com/oneword/index.php替換成您的項目部署地址，除特殊需求外其他保持不變。
## 開源聲明
本項目採用MIT License，在進行二次開發時請遵守該協議，如果您覺得該項目不錯，您不需要捐贈，僅需要使用并向您的朋友推廣我們的服務：

 - [維咔VikACG網頁版-肥宅的歡樂家園](https://www.vikacg.com)
 - [維咔VikACG App-隨時隨地發現ACG資源](https://app.vikacg.com)

在最後，感謝您選擇這款開源程序。

---
Copyright © 2019 Vikasu Inc.