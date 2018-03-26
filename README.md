# Alfred Workflows/Extensions/Themes

Make your Alfred more powerful. **([Alfred 2] powerpack required)**  

For more workflows, check [AlfredWorkflow.com] and [Workflow Searcher]

* * *

## Sublime Like *(Alfred 2 Theme)*
[\[Download Link\]][9]

Make your Alfred look like [Sublime Text 2] `⌘ +Sift +P`

![Sublime Like][10]

* * *

## Copy Path *(v1.0 Released 2014.05.05)*
![Copy-Path-logo]

[\[Download Link\]][12]    

Copy files' path in Finder to Clipboard.

#### Examples:

![Copy-Path-screenshot]

* * *

## Workflow Searcher *(v1.2 Released 2013.04.25)*
![Workflow-Searcher-logo]

[\[Download Link\]][11]    

Search workflows from [AlfredWorkflow.com API] List   

* Get the download & released link of the workflow you search.
* API file Cache `6 minutes`(360s)

#### Examples:

![Workflow-Searcher-screenshot]

* * *

## Shorten URL *(v1.5)*
![4]

[\[Download Link\]][8]    

This workflow support URL shortener like below.  


    goo.gl/
    bit.ly/
    t.cn/
    j.mp/
    is.gd/
    v.gd/
    git.io/
    
You can use Hotkey to trigger without outpen Alfred input window.  
Also available in [PopClip Extension](https://github.com/hzlzh/PopClip-Extensions)

#### Tips:

* To use this workflow without copy/paste, just use Alfred trigger HotKey [\[#1\]](https://github.com/hzlzh/Alfred-Workflows/issues/1)  
* How to custom your own service sort? [\[#2\]](https://github.com/hzlzh/Alfred-Workflows/issues/2)  

 
![Shorten-URL-trigger][5]
![Shorten-URL-notification][6]

(If you need more services to be added, please let me know.)

### goo.gl setup

For this to work you need to add your [Google API key](https://developers.google.com/url-shortener/v1/getting_started#APIKey) first by modifying the corresponding string of **short** Script Filter in Alfred Workflow.

Default string:

``` python
0 : {'api_url':'https://www.googleapis.com/urlshortener/v1/url','title':'goo.gl','des':'http://goo.gl/'},
```

You need to add a `?key=` value to `url`:

``` python
0 : {'api_url':'https://www.googleapis.com/urlshortener/v1/url?key=YOUR_API_KEY_HERE','title':'goo.gl','des':'http://goo.gl/'},
```

* * *

## SEO Checker *(v1.0)*

![SEO-Checker-logo]

[\[Download Link\]][SEO-Checker.alfredworkflow]    

Check domain's PR, Alexa, etc instantly in Alfred feedback.

![SEO-Checker-input]
![SEO-Checker-notification]

(If you need more SEO services to be added, please let me know.)  

* * *

## GeekPark *(v1.1)*

![GeekPark-logo]

[\[Download Link\]][GeekPark.alfredworkflow]

一个给GeekPark用户的Alfred 2 workflow.  
目前功能有：

* 获取最新极客阅读，指令：n 或 new
* 获取最新极客广播，指令：v 或 video
* 列表状态下按住`Command`键，可以只复制URL到剪切板
* 列表状态下按住`Opition`键，在搜索引擎中检索该文章
* 更多功能添加中...
	
![GeekPark-latest]

* * *

## V2EX *(v1.0)*

![V2EX-logo]

[\[Download Link\]][V2EX.alfredworkflow]

一个给V2EXer用的Alfred 2 workflow.  
目前功能有：

* 获取最新文章列表，指令：n 或 new
* 获取指定用户的文章列表，指令：@hzlzh
* 列表状态下按住`Command`键，可以只复制URL到剪切板
* 列表状态下按住`Opition`键，在搜索引擎中检索该文章
* 更多功能添加中...
	
![V2EX-latest]

* * *

## CDN Searcher *(v1.0)*

![CDN-Searcher-logo]

[\[Download Link\]][CDN-Searcher.alfredworkflow]

* 快速获得 JS/CSS/Image 等项目的 CDN 的链接，如：jQuery、Bootstrap等
* 这是第一版，下一版会支持版本选择等功能
* API文件会在本地缓存，时间为24小时
* CDN服务使用：[http://staticfile.org/](http://staticfile.org/)
	
![CDN-Searcher-latest]

* * *

## Quick Open Finder *(v1.0)*

[\[Download Link\]][Quick-Open-Finder.alfredworkflow]

* Quick open `Finder.app` wirh hotkey.

* * *

## XAMPP Control *(v1.1)*
![XAMPP Control Logo]

[\[Download Link\]][XAMPP-Control.alfredextension]

Start/Stop Apache & MySQL & FTP of XAMPP in Alfred with PowerPack. From now on you will be no longer launch XAMPP in your Dock continually.

![XAMPP-Control-trigger]

*Note:* # Note: You may need to input your admin **ROOT** password just once when using this extension. To reset your **ROOT** password just run `xampp root`

run `xampp {query}` from the command chart below.

    start         Start XAMPP (Apache, MySQL and eventually others)
    startapache   Start only Apache
    startmysql    Start only MySQL
    startftp      Start only ProFTPD
    
    stop          Stop XAMPP (Apache, MySQL and eventually others)
    stopapache    Stop only Apache
    stopmysql     Stop only MySQL
    stopftp       Stop only ProFTPD
    
    reload        Reload XAMPP (Apache, MySQL and eventually others)
    reloadapache  Reload only Apache
    reloadmysql   Reload only MySQL
    reloadftp     Reload only ProFTPD
    
    restart       Stop and start XAMPP
    security      Check XAMPP's security
    
    enablessl     Enable SSL support for Apache
    disablessl    Disable SSL support for Apache
    
    backup        Make backup file of your XAMPP config, log and data files
    
    fix_rights    Resets file permissions.
    

* * *

Release Note

`v1.1`

* Authenticate.app supported & root password auto-saved
* Extension Updater supported

## License

Released under [MIT](http://rem.mit-license.org/)  LICENSE.

Post: [http://hzlzh.io/tag/alfred](http://hzlzh.io/tag/alfred)  
Github: [hzlzh/Alfred-Workflows/](https://github.com/hzlzh/Alfred-Workflows/)


[XAMPP Control Logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/XAMPP-Control-icon.png "XAMPP Control for Alfred Logo"
[XAMPP-Control.alfredextension]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/XAMPP-Control.alfredextension "XAMPP Control Download Link"
[XAMPP-Control-trigger]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/XAMPP-Control-trigger.png "XAMPP Control for Alfred Screenshot"
[4]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Shorten-URL-icon.png
[5]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Shorten-URL-trigger.png
[6]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Shorten-URL-notification.png
[7]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Shorten-URL-workflow.png
[8]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/Shorten-URL.alfredworkflow "Download Shorten-URL.alfredworkflow"
[9]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/Sublime-Like.alfredappearance
[10]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Sublime-like.png
[11]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/Workflow-Searcher.alfredworkflow "Download Workflow-Searcher.alfredworkflow"
[12]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/Copy-Path.alfredworkflow "Download Copy-Path.alfredworkflow"

[Workflow-Searcher-logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Workflow-Searcher-logo.png
[Workflow-Searcher-screenshot]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Workflow-Searcher-screenshot.png

[SEO-Checker-logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/SEO-Checker-logo.png
[SEO-Checker.alfredworkflow]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/SEO-Checker.alfredworkflow
[SEO-Checker-input]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/SEO-Checker-input.png
[SEO-Checker-notification]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/SEO-Checker-notification.png
[V2EX-logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/V2EX-logo.png
[V2EX-latest]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/V2EX-latest.png
[V2EX.alfredworkflow]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/V2EX.alfredworkflow
 [GeekPark-logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/GeekPark-logo.png
 [Copy-Path-logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Copy-Path-logo.png
 [GeekPark.alfredworkflow]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/GeekPark.alfredworkflow
 [GeekPark-latest]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/GeekPark-screenshot.png
 [CDN-Searcher-logo]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/CDN-Searcher-logo.png
 [CDN-Searcher.alfredworkflow]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/CDN-Searcher.alfredworkflow
 [CDN-Searcher-latest]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/CDN-Searcher-latest.png
 [Copy-Path-screenshot]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/extra/Copy-Path-demo.png

 
 [Quick-Open-Finder.alfredworkflow]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/Quick-Open-Finder.alfredworkflow

 
 
 
 
 [AlfredWorkflow.com API]: https://github.com/hzlzh/AlfredWorkflow.com#workflows-json-api-updated-2013425
 [AlfredWorkflow.com]: http://www.alfredworkflow.com/ 'Alfred Workflow List'
 [Workflow Searcher]: https://github.com/hzlzh/Alfred-Workflows/raw/master/Downloads/Workflow-Searcher.alfredworkflow   
 
[Alfred 2]: http://www.alfredapp.com/
