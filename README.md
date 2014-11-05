#Allofu

This theme based on [crisp](https://github.com/kathyqian/crisp-ghost-theme) theme by [Kathy Qian](http://kathyqian.com).

### License
[CC BY-NC-SA 4.0](http://creativecommons.org/licenses/by-nc-sa/4.0/)<br/>
<a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/"><img alt="知识共享许可协议" style="border-width:0" src="https://i.creativecommons.org/l/by-nc-sa/4.0/88x31.png" /></a><br/>

###Demo
[Here](https://memo.ink).

![](http://s12.postimg.org/6y6izobaj/allofu.png)

###Required Steps for Installation
1. Download the files
2. Manually add/remove all links to static pages by copying (or deleting) the code in **allofu/partials/navigation.hbs**
3. Add your comments service in **allofu/post.hbs**
4. Configure the follow buttons in **allofu/partials/follow.hbs**
5. Add the "allofu" folder to the **content/themes** directory of your Ghost installation
6. Select the theme in the settings page of your Ghost admin panel

###Customizations
* Change the link, follow-icon and tag color on *line 88, line 158 and line 198* in **allofu/assets/css/allofu.css**
* Add code for Google Analytics in **allofu/default.hbs** after `{{ghost_foot}}`
* Add your favicon to **allofu/assets**
* Setting your code highlight theme in **allofu/default.hbs line 21**, css file in **allofu/assets/highlight**

###Use code highlight
    <pre class="prettyprint">

        your code

    </pre>
Turn to [google-code-prettify wiki](https://code.google.com/p/google-code-prettify/wiki/GettingStarted) for more information.

###Changelog
**ver 0.0.2  &mdash; Nov 2, 2014**
 * add code highlight support (google-code-prettify)
 * doxy theme by default

**ver 0.0.1  &mdash; Nov 2, 2014**

 * Initial release
 * local fonts & follow-icon
