# Allofu [![Build Status](https://travis-ci.org/alim0x/allofu-ghost-theme.svg)](https://travis-ci.org/alim0x/allofu-ghost-theme)

This theme based on [crisp](https://github.com/kathyqian/crisp-ghost-theme) theme by [Kathy Qian](http://kathyqian.com).

该主题基于[Kathy Qian](http://kathyqian.com)的[crisp](https://github.com/kathyqian/crisp-ghost-theme)主题。

### License
[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br/>

![](http://i60.tinypic.com/10oh0n6.png)

### 安装步骤
1. 下载文件
2. 在 **allofu/partials/comments.hbs** 中添加你的评论服务
3. 在 **allofu/partials/follow.hbs** 中设置你的个人信息链接图标
4. 将 "allofu-ghost-theme" 文件夹添加到你的Ghost的 **content/themes** 文件夹中
5. 从Ghost管理面板中选择主题

### Required Steps for Installation
1. Download the files
2. Add your comments service in **allofu/partials/comments.hbs**
3. Configure the follow buttons in **allofu/partials/follow.hbs**
4. Add the "allofu-ghost-theme" folder to the **content/themes** directory of your Ghost installation
5. Select the theme in the settings page of your Ghost admin panel

### 自定义
* 在 **allofu/assets/css/allofu.css** 中的 *第89行，第160行，第200行* 更改你的链接，个人信息链接图标以及文章标签的颜色
* 在 **allofu/default.hbs** 中的`{{ghost_foot}}`后添加你的Google Analytics
* 将 “fav.ico” 添加到 **allofu/assets** 文件夹可修改浏览器标签小图标
* 在 **allofu/default.hbs line 26** 中可设置代码高亮配色方案（默认为solarized_dark）
  * 更多可用的配色主题请查看[highlight.js styles directory](https://github.com/isagalaev/highlight.js/tree/master/src/styles)（别忘了在“.css”后缀前加上“.min”）

### Customizations
* Change the link, follow-icon and tag color on *line 89, line 160 and line 200* in **allofu/assets/css/allofu.css**
* Add code for Google Analytics in **allofu/default.hbs** after `{{ghost_foot}}`
* Add your favicon "fav.ico" to **allofu/assets**
* Setting your code highlight theme in **allofu/default.hbs line 26** (solarized_dark by default)
  * For other available styles look into the highlight.js [styles directory](https://github.com/isagalaev/highlight.js/tree/master/src/styles) (and don't forget to add ".min" before ".css").

### Use code highlight/使用代码高亮
    <pre><code>...</code></pre>
or

    <pre><code class="html">...</code></pre>

Turn to https://highlightjs.org/usage/ for more information.

前往 https://highlightjs.org/usage/ 获取更多信息。

### Changelog
**ver 0.0.3  &mdash; Mar 10, 2015**
 * replace local fonts and font-awesome
 * replace prettify.js with highlight.js for easier use

**ver 0.0.2  &mdash; Nov 2, 2014**
 * add code highlight support (google-code-prettify)
 * doxy theme by default

**ver 0.0.1  &mdash; Nov 2, 2014**

 * Initial release
 * local fonts & follow-icon
