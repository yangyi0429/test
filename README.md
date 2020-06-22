# test
<!DOCTYPE html>
<html lang="zh-cn">
<head>
    <meta charset="utf-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <meta name="referrer" content="never" />
    <meta property="og:description" content="chrome浏览器中 F12 功能的简单介绍 chrome浏览器中 F12 功能的简单介绍 chrome浏览器中 F12 功能的简单介绍 由于F12是前端开发人员的利器，所以我自己也在不断摸索中，查看" />
    <meta http-equiv="Cache-Control" content="no-transform" />
    <meta http-equiv="Cache-Control" content="no-siteapp" />
    <meta http-equiv="X-UA-Compatible" content="IE=edge" />
    <title>【F12】chrome浏览器中 F12 功能的简单介绍 - 猪猪宝丫 - 博客园</title>
    <link id="favicon" rel="shortcut icon" href="//common.cnblogs.com/favicon.ico?v=20200522" type="image/x-icon" />
    
    <link rel="stylesheet" href="/css/blog-common.min.css?v=XmRSJIHg4qXJAF9E-IMFMyxdhmRRcfdlk6K8eYlIMPw" />
    <link id="MainCss" rel="stylesheet" href="/skins/simpleblue/bundle-simpleblue.min.css?v=A3b2aPJdyRz0wsOsfRnhl-bqaa45nYsYwvEqo53RYFs" />
    
    <link id="mobile-style" media="only screen and (max-width: 767px)" type="text/css" rel="stylesheet" href="/skins/simpleblue/bundle-simpleblue-mobile.min.css?v=ANbMaizvEwT6k3PbAZsimK7lHpU5W4J73EtfVYJHS_c" />
    
    <link type="application/rss+xml" rel="alternate" href="https://www.cnblogs.com/zhuzhubaoya/rss" />
    <link type="application/rsd+xml" rel="EditURI" href="https://www.cnblogs.com/zhuzhubaoya/rsd.xml" />
    <link type="application/wlwmanifest+xml" rel="wlwmanifest" href="https://www.cnblogs.com/zhuzhubaoya/wlwmanifest.xml" />
    <script src="https://common.cnblogs.com/scripts/jquery-2.2.0.min.js"></script>
    <script src="/js/blog-common.min.js?v=UZrv6lK1AiBrSAKkehn-siGaZuUOOR23787-Dmna4BE"></script>
    <script>
        var currentBlogId = 302446;
        var currentBlogApp = 'zhuzhubaoya';
        var cb_enable_mathjax = false;
        var isLogined = false;
        var skinName = 'SimpleBlue';
    </script>
    
    
    
</head>
<body>
    <a name="top"></a>
    
    <div id="home">
    <div id="header">
        <div id="blogTitle">
            
<div class="title"><a id="Header1_HeaderTitle" class="headermaintitle HeaderMainTitle" href="https://www.cnblogs.com/zhuzhubaoya/">猪猪宝丫</a>
</div>
<div class="subtitle">

</div>

        </div>
        <div id="navigator">
            
<ul id="navList">
    <li id="nav_sitehome"><a id="blog_nav_sitehome" class="menu" href="https://www.cnblogs.com/">
博客园</a>
</li>
    <li id="nav_myhome">
<a id="blog_nav_myhome" class="menu" href="https://www.cnblogs.com/zhuzhubaoya/">
首页</a>
</li>
    <li id="nav_newpost">

<a id="blog_nav_newpost" class="menu" href="https://i.cnblogs.com/EditPosts.aspx?opt=1">
新随笔</a>
</li>
    <li id="nav_contact">
<a id="blog_nav_contact" class="menu" href="https://msg.cnblogs.com/send/%E7%8C%AA%E7%8C%AA%E5%AE%9D%E4%B8%AB">
联系</a></li>
    <li id="nav_rss">
<a id="blog_nav_rss" class="menu" href="javascript:void(0)" data-rss="https://www.cnblogs.com/zhuzhubaoya/rss/">
订阅</a></li>
    <li id="nav_admin">
<a id="blog_nav_admin" class="menu" href="https://i.cnblogs.com/">
管理</a>
</li>
</ul>

            <div class="blogStats">
                
<span id="stats_post_count">随笔 - 
385&nbsp;</span>
<span id="stats_article_count">文章 - 
0&nbsp;</span>
<!-- <span id="stats-comment_count"></span> -->
<span id="stats_comment_count">评论 - 
13</span>
            </div>
        </div>
    </div>
    <div id="main">
        <div id="mainContent">
            <div class="forFlow">
                <div id="post_detail">
    <div id="topics">
        <div class="post">
            <h1 class="postTitle">
                
<a id="cb_post_title_url" class="postTitle2 vertical-middle" href="https://www.cnblogs.com/zhuzhubaoya/p/9758648.html">
    <span>【F12】chrome浏览器中 F12 功能的简单介绍</span>
    


</a>

            </h1>
            <div class="clear"></div>
            <div class="postBody">
                
<div id="cnblogs_post_body" class="blogpost-body ">
    <div class="article-header">
<div class="article-title-box">
<h1 class="title-article">chrome浏览器中 F12 功能的简单介绍</h1>
</div>
</div>
<div id="article_content" class="article_content clearfix csdn-tracking-statistics" data-pid="blog" data-mod="popu_307" data-dsm="post">
<div class="htmledit_views">
<p>&nbsp;&nbsp;&nbsp;&nbsp;由于F12是前端开发人员的利器，所以我自己也在不断摸索中，查看一些博客和资料后，自己总结了一下来帮助自己理解和记忆，也希望能帮到有需要的小伙伴，嘿嘿！</p>
<p>首先介绍Chrome开发者工具中，调试时使用最多的三个功能页面是：元素（ELements）、控制台（Console）、源代码（Sources），此外还有网络（Network）等。</p>
<p><img src="https://img-blog.csdn.net/20180410172402581?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /></p>
<p>&nbsp;</p>
<ul>
<li>&nbsp;元素（Elements）：用于查看或修改HTML元素的属性、CSS属性、监听事件、断点等。</li>
<li>控制台（Console）：控制台一般用于执行一次性代码，查看JavaScript对象，查看调试日志信息或异常信息。</li>
<li>源代码（Sources）：该页面用于查看页面的HTML文件源代码、JavaScript源代码、CSS源代码，此外最重要的是可以调试JavaScript源代码，可以给JS代码添加断点等。</li>
<li>网络（Network）：网络页面主要用于查看header等与网络连接相关的信息。</li>
</ul>
<p><strong>1、元素（Elements）</strong></p>
<p>查看元素代码：点击如图<img src="https://img-blog.csdn.net/20180410173113988?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" />箭头（或用者用快捷键Ctrl+Shift+C）进入选择元素模式，然后从页面中选择需要查看的元素，然后可以在开发者工具元素（Elements）一栏中定位到该元素源代码的具体位置&nbsp;。</p>
<p>查看元素属性：可从被定位的源码中查看部分，如class、src，也可在右边的侧栏中查看全部的属性，如下图位置查看</p>
<p><img src="https://img-blog.csdn.net/20180410174131636?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /></p>
<p>&nbsp;</p>
<p>修改元素的代码与属性：可直接双击想要修改的部分，然后就进行修改，或者选中要修改部分后点击右键进行修改，如下图</p>
<p><strong><img src="https://img-blog.csdn.net/20180410175401686?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /><br /></strong></p>
<p><strong>注意：这个修改也仅对当前的页面渲染生效，不会修改服务器的源代码，故而这个功能也是作为调试页面效果而使用。</strong></p>
<p>右边的侧栏个功能的介绍:如下图所示</p>
<p><img src="https://img-blog.csdn.net/20180410180342393?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /></p>
<p>&nbsp;</p>
<p><strong>2、控制台（Console）</strong></p>
<ul>
<li>查看JS对象的及其属性</li>
<li>执行JS语句</li>
<li>查看控制台日志：当网页的JS代码中使用了console.log()函数时，该函数输出的日志信息会在控制台中显示。日志信息一般在开发调试时启用，而当正式上线后，一般会将该函数去掉。</li>

















</ul>
<p><strong>3、源代码（Sources）</strong>其主要功能如下介绍</p>
<p><img src="https://img-blog.csdn.net/2018041018293410?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /></p>
<p>&nbsp;</p>
<p><strong>4、网络（Network）大体功能如下：</strong></p>
<p><img src="https://img-blog.csdn.net/20180410184756216?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /></p>
<p><strong>&nbsp;</strong></p>
<p><strong>请求文件具体说明</strong></p>
<p><strong><img src="https://img-blog.csdn.net/20180410185344632?watermark/2/text/aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L20wXzM3NzI0MzU2/font/5a6L5L2T/fontsize/400/fill/I0JBQkFCMA==/dissolve/70" alt="" /><br /></strong></p>
<p><strong>一共分为四个模块：<br /></strong></p>
<ul>
<li>Header：面板列出资源的请求url、HTTP方法、响应状态码、请求头和响应头及它们各自的值、请求参数等等</li>
<li>Preview：预览面板，用于资源的预览。</li>
<li>Response：响应信息面板包含资源还未进行格式处理的内容</li>
<li>Timing：资源请求的详细信息花费时间</li>









</ul>
<ul><ol class="exp-conent-orderlist">
<li class="exp-content-list list-item-1">
<div class="content-list-text">
<p>打开浏览器,按f12,点击Network,可以查看相关网络请求信息,记得是打开f12之后再刷新页面才会开始记录的</p>








</div>
<div class="content-list-media">
<div class="content-list-image clearfix"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009110827235-215258733.png" alt="" /></div>








</div>








</li>
<li class="exp-content-list list-item-2">
<div class="content-list-text">
<p>查看Network基本信息,请求了哪些地址及每个URL的网络相关请求信息都可以看的到</p>
<p>URL，响应状态码，响应数据类型，响应数据大小，响应时间</p>








</div>
<div class="content-list-media"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009110836301-1232344571.png" alt="" /></div>








</li>
<li class="exp-content-list list-item-3">
<div class="content-list-text">
<p>请求URL可进行筛选和分类</p>
<p>选择不同分类,查看请求URL,方便查找</p>








</div>
<div class="content-list-media"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009110846349-1066479371.png" alt="" /></div>








</li>
<li class="exp-content-list list-item-4">
<div class="content-list-text">
<p>也可以直接Filter搜索查询相关URL</p>
<p>可以输入关键字或者正则表达式进行查询</p>








</div>
<div class="content-list-media"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009110858415-1843040361.png" alt="" /></div>








</li>
<li class="exp-content-list list-item-5">
<div class="content-list-text">
<p>Waterfall能分割重要的请求耗时,查看具体请求耗时在哪个地方</p>
<p>鼠标指到相关区域可以看到具体耗时</p>








</div>
<div class="content-list-media"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009110906562-374372873.png" alt="" /></div>








</li>
<li class="exp-content-list list-item-6">
<div class="content-list-text">
<p>我们具体分析下里面每个各代表什么意思,分别耗时多少,通过这个来分析服务器到底是哪个环节出了问题</p>
<p>Queueing 是排队的意思</p>
<p>Stalled 是阻塞 &nbsp;请求访问该URL的主机是有并发和连接数限制的,必须要等之前的执行才能执行之后的,这段时间的耗时</p>
<p>DNS Lookup 是指域名解析所耗时间</p>
<p>Initial connection 初始化连接时间,这里一般是TCP 3次连接握手时间</p>
<p>SSL https特有,是一种协议</p>
<p>Request sent 发送请求所消耗的时间</p>
<p>Waiting 等待响应时间,这里一般是最耗时的</p>
<p>Content Download 下载内容所需要消耗的时间</p>








</div>








</li>








</ol>
<ul>
<li class="exp-content-list list-item-7">
<div class="list-icon">7</div>
<div class="content-list-text">
<p>我们了解了上面每个耗时的时间,才能根据对应时间来修改和优化服务器访问的速度</p>
<p>留个作业,大家看看下面这张图,分别都耗时在哪里呢,我们又该怎么定位问题及解决方案呢?我们之后讲解</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<div>
<div>
<p><strong>如何使用浏览器的F12调试页面？</strong></p>
<p>&nbsp;一个程序员按照要求编写一个网页，不可能一次编写就完全达到目的，一般要对自己的的代码修改调试几次后才能到达要求，浏览器的F12开发人员工具就可以很方便的帮助程序员调试自己的代码。</p>
<p>&nbsp; &nbsp; &nbsp; &nbsp; F12 开发人员工具是一套按需采用的工具，网站开发人员可以随时在任何网页上使用 F12 工具，从而快速调试 JavaScript、HTML 和级联样式表 (CSS)，还可以跟踪并查明网页或网络的性能问题。</p>
<p>&nbsp; &nbsp; &nbsp; F12调试页面各个功能分别是什么？</p>
<p>&nbsp;<img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112153521-1698682115.png" alt="" /></p>
<p>&nbsp;</p>
<div class="image-package">
<div class="image-container" style="max-width: 700px; max-height: 699px;">
<div class="image-view" data-width="1395" data-height="699">&nbsp;</div>








</div>








</div>
<p>Elements标签页</p>
<p>Elements标签页的左侧就是对页面HTML结构的查看与编辑，你可以直接在某个元素上双击修改元素的属性。</p>
<p>&nbsp;</p>
<div class="image-package">
<div class="image-container" style="max-width: 700px; max-height: 658px;">
<div class="image-view" data-width="887" data-height="834"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112204863-862968394.png" alt="" />
<p>&nbsp;</p>






</div>








</div>








</div>
<p>Elements标签页的右侧</p>
<p>&nbsp;</p>
<div class="image-package">
<div class="image-container" style="max-width: 331px; max-height: 1638px;">
<div class="image-view" data-width="331" data-height="775"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112215886-1353618376.png" alt="" />
<p>&nbsp;</p>





</div>








</div>








</div>
<p>Network标签页</p>
<p>Network标签页对于分析网站请求的网络情况、查看某一请求的请求头和响应头还有响应内容很有用。注意是在你打开Chrome开发者工具后发起的请求，才会在这里显示</p>
<div class="image-package">
<div class="image-container" style="max-width: 700px; max-height: 698px;">
<div class="image-view" data-width="1050" data-height="698"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112227978-1348717541.png" alt="" />
<p>&nbsp;</p>




</div>








</div>








</div>
<p>Sources标签页</p>
<p>Sources标签页可以查看到请求的资源情况，包括CSS、JS、图片等的内容。也可以设置各种断点。对存储的内容进行编辑然后保存也会实时的反应到页面上。</p>
<p>&nbsp;<img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112236552-1469961277.png" alt="" /></p>
<p>&nbsp;</p>
<p>Audits标签页</p>
<p>这个对于优化前端页面、加速网页加载速度很有用;点击run按钮，就可以开始分析页面，分析完了就可以看到分析结果了</p>
<p>&nbsp;</p>
<div class="image-package">
<div class="image-container" style="max-width: 700px; max-height: 531px;">
<div class="image-view" data-width="1050" data-height="797"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112245949-1069130619.png" alt="" />
<p>&nbsp;</p>


</div>








</div>








</div>
<p>Console标签页</p>
<p>就是Javascript控制台了</p>
<p>&nbsp;<img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112254204-1403249234.png" alt="" /></p>
<p>&nbsp;</p>
<div class="image-package">
<div class="image-container" style="max-width: 700px; max-height: 612px;">
<div class="image-view" data-width="1050" data-height="612">&nbsp;</div>








</div>








</div>
<p>在控制台中可以直接模拟手机、调整UA、修改网络连接状态。</p>
<p>&nbsp;</p>
<div class="image-package">
<div class="image-container" style="max-width: 621px; max-height: 674px;">
<div class="image-view" data-width="621" data-height="674"><img src="https://img2018.cnblogs.com/blog/1017421/201810/1017421-20181009112303609-14395621.png" alt="" />
<p>&nbsp;</p>
</div>








</div>








</div>
<p>&nbsp;</p>








</div>








</div>








</div>














</li>








</ul>








</ul>

















</div>

















</div>
</div>
<div id="MySignature"></div>
<div class="clear"></div>
<div id="blog_post_info_block">
    <div id="blog_post_info"></div>
    <div class="clear"></div>
    <div id="post_next_prev"></div>
</div>
            </div>
 ddToWz(9758648);return false;">收藏</a></div>
        </div>
<script>markdown_highlight();</script>
<script>
    var allowComments = true, cb_blogId = 302446, cb_blogApp = 'zhuzhubaoya', cb_blogUserGuid = '6a1f7667-586e-e611-9fc1-ac853d9f53cc';
    var cb_entryId = 9758648, cb_entryCreatedDate = '2018-10-09 09:54', cb_postType = 1; 
    loadViewCount(cb_entryId);
    loadSideColumnAd();
</script><a name="!comments"></a>
<div id="blog-comments-placeholder"></div>
<script>
    var commentManager = new blogCommentManager();
    commentManager.renderComments(0);
</script>

<div id="comment_form" class="commentform">
    <a name="commentform"></a>
    <div id="divCommentShow"></div>
    <div id="comment_nav"><span id="span_refresh_tips"></span><a href="javascript:void(0);" onclick="return RefreshCommentList();" id="lnk_RefreshComments" runat="server" clientidmode="Static">刷新评论</a><a href="#" onclick="return RefreshPage();">刷新页面</a><a href="#top">返回顶部</a></div>
    <div id="comment_form_container"></div>
    <div class="ad_text_commentbox" id="ad_text_under_commentbox"></div>
    <div id="ad_t2"></div>
    <div id="opt_under_post"></div>
    <script async="async" src="https://www.googletagservices.com/tag/js/gpt.js"></script>
    <script>
        var googletag = googletag || {};
        googletag.cmd = googletag.cmd || [];
    </script>
    <script>
        var mobileVisit = screen.width < 500;
        googletag.cmd.push(function () {
            googletag.defineSlot("/1090369/C1", [300, 250], "div-gpt-ad-1546353474406-0").addService(googletag.pubads());
            if (!mobileVisit) {
                googletag.defineSlot("/1090369/C2", [468, 60], "div-gpt-ad-1539008685004-0").addService(googletag.pubads());
            }
            googletag.pubads().enableSingleRequest();
            googletag.enableServices();
        });
    </script>
    <div id="cnblogs_c1" class="c_ad_block">
        <div id="div-gpt-ad-1546353474406-0" style="height:250px; width:300px;"></div>
    </div>
    <div id="under_post_news"></div>
    <div id="cnblogs_c2" class="c_ad_block">
        <div id="div-gpt-ad-1539008685004-0" style="height:60px; width:468px;"></div>
    </div>
    <div id="under_post_kb"></div>
    <div id="HistoryToday" class="c_ad_block"></div>
    <script type="text/javascript">
        fixPostBody();
        deliverBigBanner();
setTimeout(function() { incrementViewCount(cb_entryId); }, 50);        deliverAdT2();
        deliverAdC1();
        deliverAdC2();
        loadNewsAndKb();
        loadBlogSignature();
LoadPostCategoriesTags(cb_blogId, cb_entryId);        LoadPostInfoBlock(cb_blogId, cb_entryId, cb_blogApp, cb_blogUserGuid);
        GetPrevNextPost(cb_entryId, cb_blogId, cb_entryCreatedDate, cb_postType);
        loadOptUnderPost();
        GetHistoryToday(cb_blogId, cb_blogApp, cb_entryCreatedDate);
    </script>
</div>    </div>
</div>
            </div>
        </div>

        <div id="sideBar">
            <div id="sideBarMain">
                
<div id="sidebar_news" class="newsItem">
            <script>loadBlogNews();</script>
</div>

<div id="sidebar_ad"></div>
                <div id="calendar"><div id="blog-calendar" style="display:none"></div></div>                
                <script>loadBlogDefaultCalendar();</script>
                <div id="leftcontentcontainer">
                    <!-- begin:SingleColumn -->
                    <div id="blog-sidecolumn"></div>
                    <script>loadBlogSideColumn();</script>
                    <!-- end:  SingleColumn -->
                </div>
            </div>
        </div>
        <div class="clear"></div>
    </div>
    <div class="clear"></div>
    <div id="footer">
        <!--done-->
<br />

    </div>
</div>

    
</body>
</html>

