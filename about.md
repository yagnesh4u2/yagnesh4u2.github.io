---
layout: page
title: About
permalink: /about/
---


<!DOCTYPE html>
<!--[if IEMobile 7]><html class="no-js iem7"  lang="en" dir="ltr"><![endif]-->
<!--[if lte IE 6]><html class="no-js lt-ie9 lt-ie8 lt-ie7"  lang="en" dir="ltr"><![endif]-->
<!--[if (IE 7)&(!IEMobile)]><html class="no-js lt-ie9 lt-ie8"  lang="en" dir="ltr"><![endif]-->
<!--[if IE 8]><html class="no-js lt-ie9"  lang="en" dir="ltr"><![endif]-->
<!--[if (gte IE 9)|(gt IEMobile 7)]><!--><html class="no-js"  lang="en" dir="ltr" prefix="og: http://ogp.me/ns# article: http://ogp.me/ns/article# book: http://ogp.me/ns/book# profile: http://ogp.me/ns/profile# video: http://ogp.me/ns/video# product: http://ogp.me/ns/product# content: http://purl.org/rss/1.0/modules/content/ dc: http://purl.org/dc/terms/ foaf: http://xmlns.com/foaf/0.1/ rdfs: http://www.w3.org/2000/01/rdf-schema# sioc: http://rdfs.org/sioc/ns# sioct: http://rdfs.org/sioc/types# skos: http://www.w3.org/2004/02/skos/core# xsd: http://www.w3.org/2001/XMLSchema# schema: http://schema.org/"><!--<![endif]-->

<head>
  <!-- Adobe Digital Data integration -->
  <script type="text/javascript">
    var digitalData = {};
  </script>
    <script id="adobe_dtm" src="https://www.redhat.com/dtm.js" type="text/javascript"></script>
  <meta charset="utf-8" />
<link href="https://opensource.com/rss.xml" rel="alternate" type="application/rss+xml" title="Opensource.com RSS" />
<link rel="shortcut icon" href="https://opensource.com/sites/all/themes/opensource/favicon.ico" type="image/vnd.microsoft.icon" />
<meta name="description" content="This beginner&#039;s guide will quickly and easily get you started using Git." />
<meta name="rating" content="general" />
<meta name="referrer" content="no-referrer" />
<meta name="generator" content="Drupal 7 (http://drupal.org)" />
<link rel="canonical" href="https://opensource.com/article/18/1/step-step-guide-git" />
<link rel="shortlink" href="https://opensource.com/node/41906" />
<meta name="revisit-after" content="1 day" />
<meta property="og:site_name" content="Opensource.com" />
<meta property="og:url" content="https://opensource.com/article/18/1/step-step-guide-git" />
<meta property="og:type" content="article" />
<meta property="og:title" content="A step-by-step guide to Git" />
<meta property="og:description" content="This beginner&#039;s guide will quickly and easily get you started using Git." />
<meta property="og:image" content="https://opensource.com/sites/default/files/lead-images/lightbulb-idea-think-yearbook-lead.png" />
<meta name="twitter:card" content="summary" />
<meta name="twitter:site" content="@opensourceway" />
<meta name="twitter:creator" content="@" />
<meta name="twitter:title" content="A step-by-step guide to Git" />
<meta name="twitter:description" content="This beginner&#039;s guide will quickly and easily get you started using Git." />
<meta name="twitter:image" content="https://opensource.com/sites/default/files/lead-images/lightbulb-idea-think-yearbook-lead.png" />
  <title>A step-by-step guide to Git | Opensource.com</title>

      <meta name="MobileOptimized" content="width">
    <meta name="HandheldFriendly" content="true">
    <meta name="viewport" content="width=device-width">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta http-equiv="cleartype" content="on">

  <link type="text/css" rel="stylesheet" href="https://opensource.com/sites/default/files/css/css_lQaZfjVpwP_oGNqdtWCSpJT1EMqXdMiU84ekLLxQnc4.css" media="all" />
<link type="text/css" rel="stylesheet" href="https://opensource.com/sites/default/files/css/css_ntCz7udh66prM85dlibL5cSl16uR5mFkmPYLsA2b56k.css" media="all" />
<link type="text/css" rel="stylesheet" href="https://opensource.com/sites/default/files/css/css_qbWV8z-nAv7aqUsFySyOpWtipkPMMxfzR6T74v1M4_w.css" media="all" />
<link type="text/css" rel="stylesheet" href="https://opensource.com/sites/default/files/css/css_xTlSDj63zgInPoPiUSqJ5EaKl4BQhMg7rpHqVO-TrCk.css" media="all" />
<link type="text/css" rel="stylesheet" href="https://opensource.com/sites/default/files/css/css_NRb2PYryOMEugaEfXSAvlO-UgHQ5VxMgLRuDt52Y1DU.css" media="all" />
<link type="text/css" rel="stylesheet" href="https://opensource.com/sites/default/files/css/css_PxsPpITToy8ZnO0bJDA1TEC6bbFpGTfSWr2ZP8LuFYo.css" media="all" />
  <script src="/sites/all/themes/opensource/js/use-typekit.js"></script>
  <script>try{Typekit.load({ async: true });}catch(e){}</script>
  <script src="https://opensource.com/sites/default/files/js/js_0RyHJ63yYLuaWsodCPCgSD8dcTIA0dqcDf8-7c2XdBw.js"></script>
<script src="https://opensource.com/sites/default/files/js/js_ObZ-VzTNzAKJIdqfIfZ5G-9ZFHqObDckctOydwVY4hM.js"></script>
<script src="https://opensource.com/sites/default/files/js/js_tBWHhFjU_NjWsmd07Hrx5ScmFu-4-PJD_GwzNMH3UwA.js"></script>
<script src="https://opensource.com/sites/default/files/js/js_fHwpceQt8e8wagFsw7P8DEpXoh7aIQr0FPLBcNUM3LM.js"></script>
<script>(function(i,s,o,g,r,a,m){i["GoogleAnalyticsObject"]=r;i[r]=i[r]||function(){(i[r].q=i[r].q||[]).push(arguments)},i[r].l=1*new Date();a=s.createElement(o),m=s.getElementsByTagName(o)[0];a.async=1;a.src=g;m.parentNode.insertBefore(a,m)})(window,document,"script","https://www.google-analytics.com/analytics.js","ga");ga("create", "UA-33294138-1", {"cookieDomain":".opensource.com"});ga("send", "pageview");</script>
<script src="https://opensource.com/sites/default/files/js/js_rVcPYhZ5_LfvT-dWbCnRngMcccEhwUaw2iNYx0yXj_Q.js"></script>
<script src="https://opensource.com/sites/default/files/js/js_KbByFnBctcQt9juhHXNabaQDr4mJAc1OExQYJ-HcyXk.js"></script>
<script>jQuery.extend(Drupal.settings, {"basePath":"\/","pathPrefix":"","ajaxPageState":{"theme":"opensource","theme_token":"QboBekAOIGIBIM-shPZpZlYhC7sY-5DIl29dsHqH7P8","jquery_version":"1.7","js":{"profiles\/panopoly\/modules\/panopoly\/panopoly_widgets\/panopoly-widgets.js":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_widgets\/panopoly-widgets-spotlight.js":1,"0":1,"1":1,"profiles\/panopoly\/modules\/contrib\/jquery_update\/replace\/jquery\/1.7\/jquery.min.js":1,"misc\/jquery-extend-3.4.0.js":1,"misc\/jquery.once.js":1,"misc\/drupal.js":1,"profiles\/panopoly\/modules\/contrib\/jquery_update\/replace\/ui\/ui\/minified\/jquery.ui.core.min.js":1,"profiles\/panopoly\/modules\/contrib\/jquery_update\/replace\/ui\/ui\/minified\/jquery.ui.widget.min.js":1,"profiles\/panopoly\/modules\/contrib\/jquery_update\/replace\/ui\/ui\/minified\/jquery.ui.tabs.min.js":1,"profiles\/panopoly\/modules\/contrib\/jquery_update\/replace\/ui\/ui\/minified\/jquery.ui.accordion.min.js":1,"misc\/ajax.js":1,"profiles\/panopoly\/modules\/contrib\/jquery_update\/js\/jquery_update.js":1,"sites\/all\/modules\/contrib\/comment_notify\/comment_notify.js":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_images\/panopoly-images.js":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_admin\/panopoly-admin.js":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_magic\/panopoly-magic.js":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_theme\/js\/panopoly-accordion.js":1,"profiles\/panopoly\/modules\/contrib\/caption_filter\/js\/caption-filter.js":1,"sites\/all\/modules\/contrib\/loginlogout\/loginlogout.js":1,"profiles\/panopoly\/libraries\/jquery.imagesloaded\/jquery.imagesloaded.min.js":1,"misc\/progress.js":1,"profiles\/panopoly\/modules\/contrib\/ctools\/js\/ajax-responder.js":1,"sites\/all\/modules\/contrib\/rate\/rate.js":1,"sites\/all\/libraries\/waypoints\/lib\/noframework.waypoints.min.js":1,"sites\/all\/themes\/opensource\/js\/os_waypoints.js":1,"sites\/all\/modules\/contrib\/google_analytics\/googleanalytics.js":1,"2":1,"file":1,"sites\/all\/themes\/opensource\/js\/addtoany-page.js":1,"sites\/all\/libraries\/superfish\/jquery.hoverIntent.minified.js":1,"sites\/all\/libraries\/superfish\/sftouchscreen.js":1,"sites\/all\/libraries\/superfish\/supposition.js":1,"sites\/all\/libraries\/superfish\/superfish.js":1,"sites\/all\/libraries\/superfish\/supersubs.js":1,"sites\/all\/modules\/contrib\/superfish\/superfish.js":1,"sites\/all\/themes\/opensource\/js\/script.js":1,"sites\/all\/themes\/opensource\/js\/cookie-banner.js":1},"css":{"modules\/system\/system.base.css":1,"modules\/system\/system.menus.css":1,"modules\/system\/system.messages.css":1,"modules\/system\/system.theme.css":1,"misc\/ui\/jquery.ui.theme.css":1,"misc\/ui\/jquery.ui.accordion.css":1,"sites\/all\/modules\/contrib\/comment_notify\/comment_notify.css":1,"sites\/all\/modules\/contrib\/calendar\/css\/calendar_multiday.css":1,"profiles\/panopoly\/modules\/contrib\/date\/date_api\/date.css":1,"profiles\/panopoly\/modules\/contrib\/date\/date_popup\/themes\/datepicker.1.7.css":1,"modules\/field\/theme\/field.css":1,"sites\/all\/modules\/contrib\/logintoboggan\/logintoboggan.css":1,"modules\/node\/node.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_admin\/panopoly-admin.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_admin\/panopoly-admin-navbar.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_core\/css\/panopoly-dropbutton.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_magic\/css\/panopoly-magic.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_magic\/css\/panopoly-modal.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_theme\/css\/panopoly-featured.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_theme\/css\/panopoly-accordian.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_theme\/css\/panopoly-layouts.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_widgets\/panopoly-widgets.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_widgets\/panopoly-widgets-spotlight.css":1,"modules\/poll\/poll.css":1,"profiles\/panopoly\/modules\/contrib\/radix_layouts\/radix_layouts.css":1,"modules\/search\/search.css":1,"modules\/user\/user.css":1,"sites\/all\/modules\/contrib\/workflow\/workflow_admin_ui\/workflow_admin_ui.css":1,"profiles\/panopoly\/modules\/contrib\/views\/css\/views.css":1,"profiles\/panopoly\/modules\/contrib\/caption_filter\/caption-filter.css":1,"sites\/all\/modules\/contrib\/ckeditor\/css\/ckeditor.css":1,"profiles\/panopoly\/modules\/contrib\/media\/modules\/media_wysiwyg\/css\/media_wysiwyg.base.css":1,"profiles\/panopoly\/modules\/contrib\/ctools\/css\/ctools.css":1,"public:\/\/geshi\/geshifilter-languages.css":1,"sites\/all\/modules\/contrib\/geshifilter\/geshifilter.css":1,"sites\/all\/modules\/features\/os_common_components\/css\/os_common_components.css":1,"profiles\/panopoly\/modules\/contrib\/panels\/css\/panels.css":1,"sites\/all\/modules\/contrib\/rate\/rate.css":1,"sites\/all\/modules\/features\/os_common_components\/plugins\/layouts\/opensource_article\/opensource-article.css":1,"modules\/comment\/comment.css":1,"sites\/all\/modules\/contrib\/vote_up_down\/vud_comment\/vud_comment.css":1,"sites\/all\/modules\/features\/os_content_article\/plugins\/widgets\/up\/up.css":1,"sites\/all\/modules\/contrib\/rate\/templates\/thumbs-up\/thumbs-up.css":1,"sites\/all\/libraries\/superfish\/css\/superfish.css":1,"sites\/all\/themes\/opensource\/system.menus.css":1,"sites\/all\/themes\/opensource\/system.messages.css":1,"sites\/all\/themes\/opensource\/system.theme.css":1,"sites\/all\/themes\/opensource\/panels.css":1,"sites\/all\/themes\/opensource\/css\/styles.css":1,"sites\/all\/themes\/opensource\/css\/geshifilter.css":1,"sites\/all\/themes\/opensource\/fonts\/css\/fontello.css":1,"sites\/all\/themes\/opensource\/css\/cookie-banner.css":1,"sites\/all\/themes\/opensource\/calendar_multiday.css":1,"sites\/all\/themes\/opensource\/date_views.css":1,"sites\/all\/themes\/opensource\/quicktabs.css":1,"profiles\/panopoly\/modules\/panopoly\/panopoly_images\/panopoly-images.css":1}},"loginlogout":{"urls":{"\/user\/login":"\/user\/login?destination=node\/41906","\/user":"\/user?destination=node\/41906"}},"CToolsModal":{"modalSize":{"type":"scale","width":".9","height":".9","addWidth":0,"addHeight":0,"contentRight":25,"contentBottom":75},"modalOptions":{"opacity":".55","background-color":"#FFF"},"animationSpeed":"fast","modalTheme":"CToolsModalDialog","throbberTheme":"CToolsModalThrobber"},"panopoly_magic":{"pane_add_preview_mode":"automatic"},"rate":{"basePath":"\/rate\/vote\/js","destination":"node\/41906"},"googleanalytics":{"trackOutbound":1,"trackMailto":1,"trackDownload":1,"trackDownloadExtensions":"7z|aac|arc|arj|asf|asx|avi|bin|csv|doc(x|m)?|dot(x|m)?|exe|flv|gif|gz|gzip|hqx|jar|jpe?g|js|mp(2|3|4|e?g)|mov(ie)?|msi|msp|pdf|phps|png|ppt(x|m)?|pot(x|m)?|pps(x|m)?|ppam|sld(x|m)?|thmx|qtm?|ra(m|r)?|sea|sit|tar|tgz|torrent|txt|wav|wma|wmv|wpd|xls(x|m|b)?|xlt(x|m)|xlam|xml|z|zip","trackDomainMode":1},"urlIsAjaxTrusted":{"\/article\/18\/1\/step-step-guide-git":true},"superfish":{"1":{"id":"1","sf":{"delay":"0","animation":{"opacity":"show","height":"show"},"speed":"\u0027fast\u0027","autoArrows":false,"dropShadows":false,"disableHI":false},"plugins":{"touchscreen":{"mode":"window_width","breakpoint":1070},"supposition":true,"bgiframe":false,"supersubs":{"minWidth":"12","maxWidth":"27","extraWidth":1}}}}});</script>
      <!--[if lt IE 9]>
    <script src="/sites/all/themes/zen/js/html5-respond.js"></script>
    <![endif]-->
  </head>
<body class="html not-front not-logged-in no-sidebars page-node page-node- page-node-41906 node-type-article region-content section-article page-panels" >
      <p id="skip-link">
      <a href="#main-menu" class="element-invisible element-focusable">Jump to navigation</a>
    </p>
      
<header class="header" id="header" role="banner">

    
    <div class="header-banner">
      <div class="header-banner__inner">
                  <div class="header__name-and-slogan" id="name-and-slogan">
                          <div class="header__site-name" id="site-name">
                <a href="/" title="Home" class="header__site-link" rel="home"><img alt="Opensource.com" src="/sites/all/themes/opensource/logo.svg" onerror="this.src='/sites/all/themes/opensource/logo.png';this.onerror=null;" /></a>
                <a href="https://www.redhat.com/en?intcmp=701600000011l7VAAQ" title="Home" class="header__sponsor-link" rel="home"><img alt="RedHat" src="/sites/all/themes/opensource/images/redhat-logo.svg" onerror="this.src='/sites/all/themes/opensource/images/redhat-logo.png';this.onerror=null;"/></a>
              </div>
            
                      </div>
                <nav class="desktop-user-links">
            <div class="header__region region region-header">
    <div id="block-menu-block-1" class="block block-menu-block first last odd" role="navigation">

      
  <div class="menu-block-wrapper menu-block-1 menu-name-user-menu parent-mlid-0 menu-level-1">
  <ul class="menu"><li class="menu__item is-leaf first leaf menu-mlid-195"><a href="/user/login" class="menu__link">Log in</a></li>
<li class="menu__item is-leaf last leaf menu-mlid-1179"><a href="/user/register" title="Sign Up" class="menu__link">Sign Up</a></li>
</ul></div>

</div>
  </div>
        </nav>
      </div>
    </div>

    <div class="sf-nav">
      <div class="sf-nav__inner">
          <div class="js-mobile-header-buttons region region-navigation-top">
    <div id="block-os-solr-search-form" class="block block-os-solr-search first odd">

      
  <form action="/article/18/1/step-step-guide-git" method="post" id="os-search-block-form" accept-charset="UTF-8"><div><div class="container-inline">
      <h2 class="element-invisible">Search form</h2>
    <div class="form-item form-type-textfield form-item-search">
  <label class="element-invisible" for="edit-search">Search </label>
 <input title="Enter the terms you wish to search for." placeholder="Search opensource.com" type="text" id="edit-search" name="search" value="" size="15" maxlength="128" class="form-text" />
</div>
<div class="form-actions form-wrapper" id="edit-actions"><input type="submit" id="edit-submit" name="op" value="GO" class="form-submit" /></div><input type="hidden" name="form_build_id" value="form-HUErIVyxCRgZrIID8swwzuyXQ4q01IMae4N88SQK3mA" />
<input type="hidden" name="form_id" value="os_search_block_form" />
</div>
</div></form>
</div>
<div id="block-superfish-1" class="block block-superfish even">

        <h2 class="block__title block-title">Main menu</h2>
    
  <ul id="superfish-1" class="menu sf-menu sf-main-menu sf-horizontal sf-style-default sf-total-items-5 sf-parent-items-5 sf-single-items-0"><li id="menu-1906-1" class="first odd sf-item-1 sf-depth-1 sf-total-children-10 sf-parent-children-3 sf-single-children-7 menuparent"><a href="/" title="" class="sf-depth-1 menuparent">Articles</a><ul><li id="menu-12341-1" class="first odd sf-item-1 sf-depth-2 sf-no-children"><a href="/tags/containers" title="" class="sf-depth-2">Containers</a></li><li id="menu-12416-1" class="middle even sf-item-2 sf-depth-2 sf-no-children"><a href="/tags/devops" title="" class="sf-depth-2">DevOps</a></li><li id="menu-12346-1" class="middle odd sf-item-3 sf-depth-2 sf-no-children"><a href="/tags/gaming" title="" class="sf-depth-2">Gaming</a></li><li id="menu-17776-1" class="middle even sf-item-4 sf-depth-2 sf-no-children"><a href="/tags/government" title="" class="sf-depth-2">Government</a></li><li id="menu-12351-1" class="middle odd sf-item-5 sf-depth-2 sf-total-children-3 sf-parent-children-0 sf-single-children-3 menuparent"><a href="/tags/hardware" title="" class="sf-depth-2 menuparent">Hardware</a><ul><li id="menu-12376-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/tags/3d-printing" title="" class="sf-depth-3">3D printing</a></li><li id="menu-12386-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/tags/arduino" title="" class="sf-depth-3">Arduino</a></li><li id="menu-12381-1" class="last odd sf-item-3 sf-depth-3 sf-no-children"><a href="/tags/raspberry-pi" title="" class="sf-depth-3">Raspberry Pi</a></li></ul></li><li id="menu-1946-1" class="middle even sf-item-6 sf-depth-2 sf-total-children-2 sf-parent-children-0 sf-single-children-2 menuparent"><a href="/tags/law" title="" class="sf-depth-2 menuparent">Law</a><ul><li id="menu-12391-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/tags/licensing" title="" class="sf-depth-3">Licensing</a></li><li id="menu-12396-1" class="last even sf-item-2 sf-depth-3 sf-no-children"><a href="/tags/patents" title="" class="sf-depth-3">Patents</a></li></ul></li><li id="menu-12356-1" class="middle odd sf-item-7 sf-depth-2 sf-no-children"><a href="/tags/linux" title="" class="sf-depth-2">Linux</a></li><li id="menu-12361-1" class="middle even sf-item-8 sf-depth-2 sf-no-children"><a href="/tags/openstack" title="" class="sf-depth-2">OpenStack</a></li><li id="menu-12366-1" class="middle odd sf-item-9 sf-depth-2 sf-total-children-3 sf-parent-children-0 sf-single-children-3 menuparent"><a href="/tags/programming" title="" class="sf-depth-2 menuparent">Programming</a><ul><li id="menu-17771-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/tags/go" title="" class="sf-depth-3">Go</a></li><li id="menu-12411-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/tags/javascript" title="" class="sf-depth-3">JavaScript</a></li><li id="menu-12406-1" class="last odd sf-item-3 sf-depth-3 sf-no-children"><a href="/tags/python" title="" class="sf-depth-3">Python</a></li></ul></li><li id="menu-12371-1" class="last even sf-item-10 sf-depth-2 sf-no-children"><a href="/tags/sysadmin" title="" class="sf-depth-2">SysAdmin</a></li></ul></li><li id="menu-1921-1" class="middle even sf-item-2 sf-depth-1 sf-total-children-5 sf-parent-children-2 sf-single-children-3 menuparent"><a href="/resources" title="" class="sf-depth-1 menuparent">Resources</a><ul><li id="menu-2016-1" class="first odd sf-item-1 sf-depth-2 sf-no-children"><a href="/resources/projects-and-applications" title="" class="sf-depth-2">Projects and applications</a></li><li id="menu-2021-1" class="middle even sf-item-2 sf-depth-2 sf-no-children"><a href="/resources/organizations" title="" class="sf-depth-2">Organizations</a></li><li id="menu-1991-1" class="middle odd sf-item-3 sf-depth-2 sf-no-children"><a href="/open-source-way" class="sf-depth-2">The open source way</a></li><li id="menu-5556-1" class="middle even sf-item-4 sf-depth-2 sf-total-children-9 sf-parent-children-0 sf-single-children-9 menuparent"><a href="/resources/cloud" title="" class="sf-depth-2 menuparent">Cloud technology</a><ul><li id="menu-5576-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/resources/big-data" title="" class="sf-depth-3">Big data</a></li><li id="menu-5566-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/resources/what-docker" title="" class="sf-depth-3">Docker</a></li><li id="menu-5591-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/resources/internet-of-things" title="" class="sf-depth-3">Internet of things</a></li><li id="menu-5596-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/resources/what-is-kubernetes" title="" class="sf-depth-3">Kubernetes</a></li><li id="menu-5571-1" class="middle odd sf-item-5 sf-depth-3 sf-no-children"><a href="/resources/what-are-linux-containers" title="" class="sf-depth-3">Linux containers</a></li><li id="menu-5586-1" class="middle even sf-item-6 sf-depth-3 sf-no-children"><a href="/resources/what-are-microservices" title="" class="sf-depth-3">Microservices</a></li><li id="menu-5561-1" class="middle odd sf-item-7 sf-depth-3 sf-no-children"><a href="/resources/what-is-openstack" title="" class="sf-depth-3">OpenStack</a></li><li id="menu-5581-1" class="middle even sf-item-8 sf-depth-3 sf-no-children"><a href="/resources/what-is-software-defined-networking" title="" class="sf-depth-3">Software defined networking</a></li><li id="menu-12601-1" class="last odd sf-item-9 sf-depth-3 sf-no-children"><a href="/resources/virtualization" title="" class="sf-depth-3">Virtualization</a></li></ul></li><li id="menu-2036-1" class="last odd sf-item-5 sf-depth-2 sf-total-children-11 sf-parent-children-0 sf-single-children-11 menuparent"><a href="/alternatives" title="" class="sf-depth-2 menuparent">Open source alternatives</a><ul><li id="menu-4646-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/alternatives/adobe-acrobat" class="sf-depth-3">Alternatives to Acrobat</a></li><li id="menu-4656-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/alternatives/autocad" class="sf-depth-3">Alternatives to AutoCAD</a></li><li id="menu-4636-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/alternatives/dreamweaver" class="sf-depth-3">Alternatives to Dreamweaver</a></li><li id="menu-5506-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/alternatives/gmail" class="sf-depth-3">Alternatives to Gmail</a></li><li id="menu-5551-1" class="middle odd sf-item-5 sf-depth-3 sf-no-children"><a href="/alternatives/matlab" class="sf-depth-3">Alternatives to MATLAB</a></li><li id="menu-5501-1" class="middle even sf-item-6 sf-depth-3 sf-no-children"><a href="/alternatives/minecraft" class="sf-depth-3">Alternatives to Minecraft</a></li><li id="menu-4651-1" class="middle odd sf-item-7 sf-depth-3 sf-no-children"><a href="/alternatives/picasa" class="sf-depth-3">Alternatives to Picasa</a></li><li id="menu-4661-1" class="middle even sf-item-8 sf-depth-3 sf-no-children"><a href="/alternatives/microsoft-publisher" class="sf-depth-3">Alternatives to Publisher</a></li><li id="menu-5511-1" class="middle odd sf-item-9 sf-depth-3 sf-no-children"><a href="/alternatives/slack" class="sf-depth-3">Alternatives to Slack</a></li><li id="menu-4641-1" class="middle even sf-item-10 sf-depth-3 sf-no-children"><a href="/alternatives/trello" class="sf-depth-3">Alternatives to Trello</a></li><li id="menu-5546-1" class="last odd sf-item-11 sf-depth-3 sf-no-children"><a href="/alternatives" title="" class="sf-depth-3">More...</a></li></ul></li></ul></li><li id="menu-19666-1" class="middle odd sf-item-3 sf-depth-1 sf-total-children-9 sf-parent-children-2 sf-single-children-7 menuparent"><a href="/downloads/cheat-sheets" title="" class="sf-depth-1 menuparent">Downloads</a><ul><li id="menu-19406-1" class="first odd sf-item-1 sf-depth-2 sf-total-children-16 sf-parent-children-0 sf-single-children-16 menuparent"><a href="/downloads/cheat-sheets" title="" class="sf-depth-2 menuparent">Cheat sheets</a><ul><li id="menu-19651-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/downloads/cheat-sheet-awk-features" class="sf-depth-3">AWK cheat sheet</a></li><li id="menu-18641-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/downloads/blender-hotkey-cheat-sheet" class="sf-depth-3">Blender cheat sheet</a></li><li id="menu-18856-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/downloads/freedos-commands-cheat-sheet" class="sf-depth-3">FreeDOS cheat sheet</a></li><li id="menu-19721-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/content/cheat-sheet-gimp" class="sf-depth-3">GIMP cheat sheet</a></li><li id="menu-19696-1" class="middle odd sf-item-5 sf-depth-3 sf-no-children"><a href="/downloads/cheat-sheet-gnome-3" class="sf-depth-3">GNOME cheat sheet</a></li><li id="menu-18661-1" class="middle even sf-item-6 sf-depth-3 sf-no-children"><a href="/downloads/groff-macros-cheat-sheet" class="sf-depth-3">Groff macros cheat sheet</a></li><li id="menu-19731-1" class="middle odd sf-item-7 sf-depth-3 sf-no-children"><a href="/downloads/go-cheat-sheet" class="sf-depth-3">Go cheat sheet</a></li><li id="menu-19716-1" class="middle even sf-item-8 sf-depth-3 sf-no-children"><a href="/downloads/cheat-sheet-i3-window-manager-keybinding" class="sf-depth-3">i3 window manager cheat sheet</a></li><li id="menu-19781-1" class="middle odd sf-item-9 sf-depth-3 sf-no-children"><a href="/downloads/inkscape-cheat-sheet" class="sf-depth-3">Inkscape Cheat Sheet</a></li><li id="menu-16886-1" class="middle even sf-item-10 sf-depth-3 sf-no-children"><a href="/irc-cheat-sheet" class="sf-depth-3">IRC cheat sheet</a></li><li id="menu-19301-1" class="middle odd sf-item-11 sf-depth-3 sf-no-children"><a href="/downloads/cheat-sheet-networking" class="sf-depth-3">Networking cheat sheet</a></li><li id="menu-18636-1" class="middle even sf-item-12 sf-depth-3 sf-no-children"><a href="/downloads/pandoc-cheat-sheet" class="sf-depth-3">Pandoc cheat sheet</a></li><li id="menu-19711-1" class="middle odd sf-item-13 sf-depth-3 sf-no-children"><a href="/downloads/cheat-sheet-python-37-beginners" class="sf-depth-3">Python 3.7 cheat sheet</a></li><li id="menu-19726-1" class="middle even sf-item-14 sf-depth-3 sf-no-children"><a href="/downloads/getting-started-raspberry-pi-cheat-sheet" class="sf-depth-3">Raspberry Pi cheat sheet</a></li><li id="menu-19691-1" class="middle odd sf-item-15 sf-depth-3 sf-no-children"><a href="/downloads/cheat-sheet-selinux" class="sf-depth-3">SELinux cheat sheet</a></li><li id="menu-18591-1" class="last even sf-item-16 sf-depth-3 sf-no-children"><a href="/downloads/advanced-ssh-cheat-sheet" class="sf-depth-3">SSH cheat sheet</a></li></ul></li><li id="menu-12466-1" class="middle even sf-item-2 sf-depth-2 sf-total-children-4 sf-parent-children-0 sf-single-children-4 menuparent"><a href="/yearbook/2017" title="" class="sf-depth-2 menuparent">Open Source Yearbook</a><ul><li id="menu-19681-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/yearbook/2015" title="" class="sf-depth-3">2015</a></li><li id="menu-19676-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/yearbook/2016" title="" class="sf-depth-3">2016</a></li><li id="menu-19671-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/yearbook/2017" title="" class="sf-depth-3">2017</a></li><li id="menu-19786-1" class="last even sf-item-4 sf-depth-3 sf-no-children"><a href="/yearbook/2018" title="" class="sf-depth-3">2018</a></li></ul></li><li id="menu-19801-1" class="middle odd sf-item-3 sf-depth-2 sf-no-children"><a href="https://opensource.com/downloads/ansible-quickstart" title="" class="sf-depth-2">Ansible Automation for Sysadmins</a></li><li id="menu-19706-1" class="middle even sf-item-4 sf-depth-2 sf-no-children"><a href="/downloads/containers-primer" class="sf-depth-2">Containers primer</a></li><li id="menu-19686-1" class="middle odd sf-item-5 sf-depth-2 sf-no-children"><a href="/downloads/devops-hiring-guide" class="sf-depth-2">DevOps hiring guide</a></li><li id="menu-19701-1" class="middle even sf-item-6 sf-depth-2 sf-no-children"><a href="/downloads/devops-monitoring-guide" class="sf-depth-2">DevOps monitoring tools guide</a></li><li id="menu-19771-1" class="middle odd sf-item-7 sf-depth-2 sf-no-children"><a href="/downloads/devsecops" title="" class="sf-depth-2">Getting started with DevSecOps</a></li><li id="menu-19776-1" class="middle even sf-item-8 sf-depth-2 sf-no-children"><a href="/downloads/small-scale-scrum" class="sf-depth-2">Introduction to Small Scale Scrum</a></li><li id="menu-19806-1" class="last odd sf-item-9 sf-depth-2 sf-no-children"><a href="/downloads/devops-transformation" title="" class="sf-depth-2">Starting a DevOps transformation</a></li></ul></li><li id="menu-4691-1" class="middle even sf-item-4 sf-depth-1 sf-total-children-5 sf-parent-children-2 sf-single-children-3 menuparent"><a href="/about" class="sf-depth-1 menuparent">About</a><ul><li id="menu-12516-1" class="first odd sf-item-1 sf-depth-2 sf-total-children-7 sf-parent-children-0 sf-single-children-7 menuparent"><a href="/participate" class="sf-depth-2 menuparent">Our community</a><ul><li id="menu-12521-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/user/register" title="" class="sf-depth-3">Register</a></li><li id="menu-12526-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/rules-comments-and-discussions" class="sf-depth-3">Rules for comments and discussions</a></li><li id="menu-17781-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/devops-team" class="sf-depth-3">Contribute to DevOps resources</a></li><li id="menu-12531-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/community-moderator-program" class="sf-depth-3">Community Moderator program</a></li><li id="menu-12581-1" class="middle odd sf-item-5 sf-depth-3 sf-no-children"><a href="/resources/contributor-club" title="" class="sf-depth-3">Contributor Club</a></li><li id="menu-12541-1" class="middle even sf-item-6 sf-depth-3 sf-no-children"><a href="/points-and-badges" class="sf-depth-3">Points and badges</a></li><li id="menu-17766-1" class="last odd sf-item-7 sf-depth-3 sf-no-children"><a href="/delete-account" title="" class="sf-depth-3">Delete your account</a></li></ul></li><li id="menu-1966-1" class="middle even sf-item-2 sf-depth-2 sf-total-children-6 sf-parent-children-0 sf-single-children-6 menuparent"><a href="/writers" title="" class="sf-depth-2 menuparent">For writers</a><ul><li id="menu-17761-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/how-submit-article" class="sf-depth-3">Write for us</a></li><li id="menu-12546-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/resources/editorial-calendar" title="" class="sf-depth-3">Editorial calendar</a></li><li id="menu-12586-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/article/19/1/write-for-us" title="" class="sf-depth-3">Writing topics</a></li><li id="menu-2041-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/submission-style-guide" class="sf-depth-3">Article submission and style guide</a></li><li id="menu-4616-1" class="middle odd sf-item-5 sf-depth-3 sf-no-children"><a href="/promoting-articles" class="sf-depth-3">Tips for promoting your Opensource.com article</a></li><li id="menu-12556-1" class="last even sf-item-6 sf-depth-3 sf-no-children"><a href="/writer-testimonials" class="sf-depth-3">Writer testimonials</a></li></ul></li><li id="menu-1971-1" class="middle odd sf-item-3 sf-depth-2 sf-no-children"><a href="/opensourcecom-team" class="sf-depth-2">Meet the team</a></li><li id="menu-2006-1" class="middle even sf-item-4 sf-depth-2 sf-no-children"><a href="/press-kit" class="sf-depth-2">Press kit</a></li><li id="menu-2001-1" class="last odd sf-item-5 sf-depth-2 sf-no-children"><a href="/contact" title="" class="sf-depth-2">Contact</a></li></ul></li><li id="menu-2136-1" class="last odd sf-item-5 sf-depth-1 sf-total-children-5 sf-parent-children-3 sf-single-children-2 menuparent"><a href="/open-organization" title="" class="sf-depth-1 menuparent">The Open Org</a><ul><li id="menu-12471-1" class="first odd sf-item-1 sf-depth-2 sf-no-children"><a href="/open-organization/resources/open-org-definition" title="What is an open organization?" class="sf-depth-2">What is an open organization?</a></li><li id="menu-15056-1" class="middle even sf-item-2 sf-depth-2 sf-no-children"><a href="/open-organization/resources/open-org-maturity-model" title="" class="sf-depth-2">How open is your organization?</a></li><li id="menu-15051-1" class="middle odd sf-item-3 sf-depth-2 sf-total-children-5 sf-parent-children-0 sf-single-children-5 menuparent"><a href="/open-organization/resources/book-series" title="" class="sf-depth-2 menuparent">Book series</a><ul><li id="menu-18656-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/open-organization/resources/organize-innovation" class="sf-depth-3">Organize for Innovation download</a></li><li id="menu-17796-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/open-organization/resources/workbook" class="sf-depth-3">Open Organization Workbook download</a></li><li id="menu-16896-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/open-organization/resources/culture-change" class="sf-depth-3">Guide to IT Culture Change download</a></li><li id="menu-16891-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/open-organization/resources/leaders-manual" class="sf-depth-3">Leaders Manual download</a></li><li id="menu-16906-1" class="last odd sf-item-5 sf-depth-3 sf-no-children"><a href="/open-organization/resources/field-guide" class="sf-depth-3">Field guide download</a></li></ul></li><li id="menu-2146-1" class="middle even sf-item-4 sf-depth-2 sf-total-children-8 sf-parent-children-0 sf-single-children-8 menuparent"><a href="/open-organization/resources" title="" class="sf-depth-2 menuparent">Resources</a><ul><li id="menu-2181-1" class="first odd sf-item-1 sf-depth-3 sf-no-children"><a href="/open-organization/resources/what-open-organization" title="" class="sf-depth-3">What is The Open Organization?</a></li><li id="menu-12421-1" class="middle even sf-item-2 sf-depth-3 sf-no-children"><a href="/open-organization/resources/open-decision-framework" title="" class="sf-depth-3">What is the Open Decision Framework?</a></li><li id="menu-2151-1" class="middle odd sf-item-3 sf-depth-3 sf-no-children"><a href="/open-organization/resources/guides" title="" class="sf-depth-3">Discussion guide download</a></li><li id="menu-17821-1" class="middle even sf-item-4 sf-depth-3 sf-no-children"><a href="/open-organization/resources/newsletter" class="sf-depth-3">Newsletter sign-up</a></li><li id="menu-2246-1" class="middle odd sf-item-5 sf-depth-3 sf-no-children"><a href="/open-organization/resources/faq" title="" class="sf-depth-3">Open Org FAQs</a></li><li id="menu-4606-1" class="middle even sf-item-6 sf-depth-3 sf-no-children"><a href="/open-organization/resources/twitter-chats" title="" class="sf-depth-3">Twitter chats</a></li><li id="menu-3201-1" class="middle odd sf-item-7 sf-depth-3 sf-no-children"><a href="/open-organization/resources/reading-list" title="" class="sf-depth-3">Reading list</a></li><li id="menu-2256-1" class="last even sf-item-8 sf-depth-3 sf-no-children"><a href="/open-organization/resources/2015-book-club" title="" class="sf-depth-3">Book club</a></li></ul></li><li id="menu-3166-1" class="last odd sf-item-5 sf-depth-2 sf-total-children-1 sf-parent-children-0 sf-single-children-1 menuparent"><a href="/open-organization/resources/ambassadors-program" title="" class="sf-depth-2 menuparent">Ambassadors program</a><ul><li id="menu-2691-1" class="firstandlast odd sf-item-1 sf-depth-3 sf-no-children"><a href="/open-organization/resources/meet-ambassadors" title="" class="sf-depth-3">Meet the ambassadors</a></li></ul></li></ul></li></ul>
</div>
<div id="block-system-user-menu" class="block block-system block-menu odd" role="navigation">

      
  <ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/user/login" class="menu__link">Log in</a></li>
<li class="menu__item is-leaf last leaf"><a href="/user/register" title="Sign Up" class="menu__link">Sign Up</a></li>
</ul>
</div>
<div id="block-menu-block-2" class="block block-menu-block last even" role="navigation">

      
  <div class="menu-block-wrapper menu-block-2 menu-name-menu-social-links parent-mlid-0 menu-level-1">
  <ul class="menu"><li class="menu__item is-leaf first leaf menu-mlid-13171"><a href="http://twitter.com/opensourceway" title="twitter" class="menu__link">Twitter</a></li>
<li class="menu__item is-leaf leaf menu-mlid-13176"><a href="https://www.facebook.com/opensourceway" title="facebook" class="menu__link">Facebook</a></li>
<li class="menu__item is-leaf last leaf menu-mlid-13166"><a href="/feed" title="feed" class="menu__link">Feed</a></li>
</ul></div>

</div>
  </div>

        <div class="mobile--menu-region">
            <div class="region region-navigation">
    <div id="block-system-main-menu" class="block block-system block-menu first last odd" role="navigation">

        <h2 class="block__title block-title">Main menu</h2>
    
  <ul class="menu"><li class="menu__item is-expanded first expanded"><a href="/" title="" class="menu__link">Articles</a><ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/tags/containers" title="" class="menu__link">Containers</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/devops" title="" class="menu__link">DevOps</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/gaming" title="" class="menu__link">Gaming</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/government" title="" class="menu__link">Government</a></li>
<li class="menu__item is-expanded expanded"><a href="/tags/hardware" title="" class="menu__link">Hardware</a><ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/tags/3d-printing" title="" class="menu__link">3D printing</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/arduino" title="" class="menu__link">Arduino</a></li>
<li class="menu__item is-leaf last leaf"><a href="/tags/raspberry-pi" title="" class="menu__link">Raspberry Pi</a></li>
</ul></li>
<li class="menu__item is-collapsed collapsed"><a href="/tags/law" title="" class="menu__link">Law</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/linux" title="" class="menu__link">Linux</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/openstack" title="" class="menu__link">OpenStack</a></li>
<li class="menu__item is-expanded expanded"><a href="/tags/programming" title="" class="menu__link">Programming</a><ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/tags/go" title="" class="menu__link">Go</a></li>
<li class="menu__item is-leaf leaf"><a href="/tags/javascript" title="" class="menu__link">JavaScript</a></li>
<li class="menu__item is-leaf last leaf"><a href="/tags/python" title="" class="menu__link">Python</a></li>
</ul></li>
<li class="menu__item is-collapsed last collapsed"><a href="/tags/sysadmin" title="" class="menu__link">SysAdmin</a></li>
</ul></li>
<li class="menu__item is-expanded expanded"><a href="/resources" title="" class="menu__link">Resources</a><ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/resources/projects-and-applications" title="" class="menu__link">Projects and applications</a></li>
<li class="menu__item is-leaf leaf"><a href="/resources/organizations" title="" class="menu__link">Organizations</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-source-way" class="menu__link">The open source way</a></li>
<li class="menu__item is-collapsed collapsed"><a href="/resources/cloud" title="" class="menu__link">Cloud technology</a></li>
<li class="menu__item is-collapsed last collapsed"><a href="/alternatives" title="" class="menu__link">Open source alternatives</a></li>
</ul></li>
<li class="menu__item is-collapsed collapsed"><a href="/downloads/cheat-sheets" title="" class="menu__link">Downloads</a></li>
<li class="menu__item is-collapsed collapsed"><a href="/about" class="menu__link">About</a></li>
<li class="menu__item is-expanded last expanded"><a href="/open-organization" title="" class="menu__link">The Open Org</a><ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/open-organization/resources/open-org-definition" title="What is an open organization?" class="menu__link">What is an open organization?</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/open-org-maturity-model" title="" class="menu__link">How open is your organization?</a></li>
<li class="menu__item is-collapsed collapsed"><a href="/open-organization/resources/book-series" title="" class="menu__link">Book series</a></li>
<li class="menu__item is-expanded expanded"><a href="/open-organization/resources" title="" class="menu__link">Resources</a><ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/open-organization/resources/what-open-organization" title="" class="menu__link">What is The Open Organization?</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/open-decision-framework" title="" class="menu__link">What is the Open Decision Framework?</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/guides" title="" class="menu__link">Discussion guide download</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/newsletter" class="menu__link">Newsletter sign-up</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/faq" title="" class="menu__link">Open Org FAQs</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/twitter-chats" title="" class="menu__link">Twitter chats</a></li>
<li class="menu__item is-leaf leaf"><a href="/open-organization/resources/reading-list" title="" class="menu__link">Reading list</a></li>
<li class="menu__item is-leaf last leaf"><a href="/open-organization/resources/2015-book-club" title="" class="menu__link">Book club</a></li>
</ul></li>
<li class="menu__item is-collapsed last collapsed"><a href="/open-organization/resources/ambassadors-program" title="" class="menu__link">Ambassadors program</a></li>
</ul></li>
</ul>
</div>
  </div>
        </div>
      </div>
    </div>

</header>

<div id="page">

      <div id="main">
        <div class="pre-content">
                                                </div>
        <div id="content" class="column" role="main">
                              <a id="main-content"></a>
                                <h1 class="page__title title" id="page-title">A step-by-step guide to Git</h1>
                              



<div class="panel-display os-article clearfix os-article--with-image " id="article-template">

      <div class="os-article__top">
      <div class="os-article__top-inner">
        <div class="panel-pane pane-node-title"  >
  
      
  
  <h1>A step-by-step guide to Git</h1>

  
  </div>
<div class="panel-pane pane-entity-field pane-node-field-article-subhead"  >
  
      
  
  <div class="field field-name-field-article-subhead field-type-text-long field-label-hidden">
    <div class="field-items">
          <h2>Don&#039;t be nervous. This beginner&#039;s guide will quickly and easily get you started using Git.</h2>
      </div>
</div>

  
  </div>
<div class="panel-pane pane-os-content-article-byline"  >
  
      
  
  <div class="byline"><span class="byline__date">25 Jan 2018</span>
<span class="byline__author-name"><a href="/users/kkulkarn" title="View user profile." class="username" xml:lang="" about="/users/kkulkarn" typeof="sioc:UserAccount" property="foaf:name" datatype="">Kedar Vijay Kulkarni <span class="content-moderator">(Red Hat)</span></a>&nbsp;<span class="byline__feed"><a href="/user/131551/feed">Feed</a></span>
</span>
<span class="byline__social"><span class="byline__voting-widget"><div class="rate-widget-1 rate-widget clear-block rate-average rate-widget-thumbs_up rate-6d6462a02e12be872222b16941497821 rate-node-41906-1-1" id="rate-node-41906-1-1"><div class="rate-info">219</div><a class="rate-button rate-thumbs-up-btn-up" id="rate-button-1" rel="nofollow" href="/article/18/1/step-step-guide-git?rate=8cGXYANI_LNtNTXkWUp4Rpzk0Z2-tZv9Fqoxr4LtI-A" title="up">up</a></div></span>
</span>
<span class="byline__comment-count"><a href="#comments">10 comments</a></span>
</div>
  
  </div>
      </div>
    </div>
  
      <div class="os-article__image">
      <div class="panel-pane pane-entity-field pane-node-field-lead-image"  >
  
      
  
  <div class="field field-name-field-lead-image field-type-image field-label-hidden"><div class="field-items"><div class="field-item even" rel="schema:contentUrl" resource="https://opensource.com/sites/default/files/styles/image-full-size/public/lead-images/lightbulb-idea-think-yearbook-lead.png?itok=5ZpCm0Jh"><img class="image-full-size" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/image-full-size/public/lead-images/lightbulb-idea-think-yearbook-lead.png?itok=5ZpCm0Jh" width="520" height="292" alt="Lightbulb" title="Lightbulb" /></div></div></div>
  
  </div>
<div class="panel-pane pane-entity-field pane-file-field-file-image-caption"  >
  
      
  
  <div class="field field-name-field-file-image-caption field-type-text-long field-label-inline clearfix"><div class="field-label">Image by :&nbsp;</div><div class="field-items"><div class="field-item even"><p><a href="https://www.flickr.com/photos/internetarchivebookimages/14758810172/in/photolist-oubL5m-ocu2ck-odJwF4-oeq1na-odgZbe-odcugD-w7KHtd-owgcWd-oucGPe-oud585-rgBDNf-obLoQH-oePNvs-osVgEq-othPLM-obHcKo-wQR3KN-oumGqG-odnCyR-owgLg3-x2Zeyq-hMMxbq-oeRzu1-oeY49i-odumMM-xH4oJo-odrT31-oduJr8-odX8B3-obKG8S-of1hTN-ovhHWY-ow7Scj-ovfm7B-ouu1Hj-ods7Sg-qwgw5G-oeYz5D-oeXqFZ-orx8d5-hKPN4Q-ouNKch-our8E1-odvGSH-oweGTn-ouJNQQ-ormX8L-od9XZ1-roZJPJ-ot7Wf4" target="_blank">Internet Archive Book Images</a>. Modified by Opensource.com. CC BY-SA 4.0</p>
</div></div></div>
  
  </div>
    </div>
  
      <div class="os-article__left">
      <div class="panel-pane pane-block pane-bean-email-capture widget-block widget-block__left"  >
      <div class="target-band-never-show-button">x</div>
        <h2 class="pane-title">
      Get the newsletter    </h2>
    
  
  <div class="entity entity-bean bean-generic-block clearfix" about="/block/email-capture" typeof="">

  <div class="content">
    <div class="field field-name-field-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even"><p class="eloqua-email-capture-text">Join the 85,000 open source advocates who receive our giveaway alerts and article roundups.</p>

<p><iframe frameborder="0" height="100" id="fkfkx" scrolling="no" src="/eloqua-embedded-email-capture-block.html?offer_id=70160000000QzXNAA0" style="max-width:600px;margin:0 auto;" width="250"></iframe></p>
</div></div></div>  </div>
</div>

  
  </div>
    </div>
  
  
      <div class="os-article__middle">
      <div class="panel-pane pane-entity-field pane-node-body"  >
  
      
  
  <div class="field field-name-body field-type-text-with-summary field-label-hidden"><div class="field-items"><div class="field-item even" property="schema:articleBody content:encoded"><p>If you've never used <a href="https://opensource.com/resources/what-is-git" target="_blank">Git</a>, you may be nervous about it. There's nothing to worry about—just follow along with this step-by-step getting-started guide, and you will soon have a new Git repository hosted on <a href="https://opensource.com/life/15/11/short-introduction-github" target="_blank">GitHub</a>.</p>

<p>Before we dive in, let's clear up a common misconception: Git isn't the same thing as GitHub. Git is a version-control system (i.e., a piece of software) that helps you keep track of your computer programs and files and the changes that are made to them over time. It also allows you to collaborate with your peers on a program, code, or file. GitHub and similar services (including GitLab and BitBucket) are websites that host a Git server program to hold your code.</p>

<h2>Step 1: Create a GitHub account</h2>

<p>The easiest way to get started is to create an account on <a href="https://github.com/" target="_blank">GitHub.com</a> (it's free).</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384196" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384196">git_guide1.png</a></h2>
    
  
  <div class="content">
    <img alt="Create a GitHub account" title="Create a GitHub account" class="media-element file-default" data-delta="1" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide1.png" width="650" height="306" /></div>

  
</div>
</div>

<p>Pick a username (e.g., octocat123), enter your email address and a password, and click <strong>Sign up for GitHub</strong>. Once you are in, it will look something like this:</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384201" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384201">git_guide2.png</a></h2>
    
  
  <div class="content">
    <img alt="Signed in to GitHub" title="Signed in to GitHub" class="media-element file-default" data-delta="2" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide2.png" width="650" height="263" /></div>

  
</div>
</div>

<h2>Step 2: Create a new repository</h2>

<p>A repository is like a place or a container where something is stored; in this case we're creating a Git repository to store code. To create a new repository, select <strong>New Repository</strong> from the <code>+</code> sign dropdown menu (you can see I've selected it in the upper-right corner in the image above).</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384206" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384206">git_guide3.png</a></h2>
    
  
  <div class="content">
    <img alt="Create a new repository" title="Create a new repository" class="media-element file-default" data-delta="3" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide3.png" width="650" height="428" /></div>

  
</div>
</div>

<p>Enter a name for your repository (e.g, "Demo") and click <strong>Create Repository</strong>. Don't worry about changing any other options on this page.</p>

<p>Congratulations! You have set up your first repo on GitHub.com.</p>

<h2>Step 3: Create a file</h2>

<p>Once your repo is created, it will look like this:</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384211" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384211">git_guide4.png</a></h2>
    
  
  <div class="content">
    <img alt="New repo on GitHub" title="New repo on GitHub" class="media-element file-default" data-delta="4" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide4.png" width="650" height="505" /></div>

  
</div>
</div>

<p>Don't panic, it's simpler than it looks. Stay with me. Look at the section that starts "...or create a new repository on the command line," and ignore the rest for now.</p>

<p>Open the <em>Terminal</em> program on your computer.</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384216" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384216">git_guide5.png</a></h2>
    
  
  <div class="content">
    <img alt="Terminal" title="Terminal" class="media-element file-default" data-delta="5" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide5.png" width="650" height="442" /></div>

  
</div>
</div>

<p>Type <code>git</code> and hit <strong>Enter</strong>. If it says command <code>bash: git: command not found</code>, then <a href="https://www.linuxbabe.com/linux-server/install-git-verion-control-on-linux-debianubuntufedoraarchlinux#crt-2" target="_blank">install Git</a> with the command for your Linux operating system or distribution. Check the installation by typing <code>git</code> and hitting <strong>Enter</strong>; if it's installed, you should see a bunch of information about how you can use the command.</p>

<p>In the terminal, type:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">mkdir Demo</code></span></pre>

<p>This command will create a directory (or folder) named <em>Demo</em>.</p>

<p>Change your terminal to the <em>Demo</em> directory with the command:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">cd Demo</code></span></pre>

<p>Then enter:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">echo &quot;#Demo&quot; &gt;&gt; README.md</code></span></pre>

<p>This creates a file named <code>README.md</code> and writes <code>#Demo</code> in it. To check that the file was created successfully, enter:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">cat README.md</code></span></pre>

<p>This will show you what is inside the <code>README.md</code> file, if the file was created correctly. Your terminal will look like this:</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384221" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384221">git_guide7.png</a></h2>
    
  
  <div class="content">
    <img alt="Terminal" title="Terminal" class="media-element file-default" data-delta="6" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide7.png" width="650" height="442" /></div>

  
</div>
</div>

<p>To tell your computer that <em>Demo</em> is a directory managed by the Git program, enter:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">git init</code></span></pre>

<p>Then, to tell the Git program you care about this file and want to track any changes from this point forward, enter:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">git add README.md</code></span></pre>

<h2>Step 4: Make a commit</h2>

<p><div id="programming-and-development" class="embedded-callout-menu callout-float-right"><div class="view view-related-content-callout view-id-related_content_callout view-display-id-article_block view-dom-id-099485cfbc8bd3693bd7cb7d1e1e9dab">
            <div class="view-header">
      Programming and development    </div>
  
  
  
      <div class="view-content">
        <div class="views-row views-row-1 views-row-odd views-row-first views-row-last">      
  <div class="views-field views-field-field-related-content-link">        <div class="field-content"><div class="item-list"><ul><li class="first"><a href="https://opensource.com/tags/python?src=programming_resource_menu1">New Python content</a></li>
<li><a href="https://opensource.com/tags/javascript?src=programming_resource_menu2">Our latest JavaScript articles</a></li>
<li><a href="https://opensource.com/tags/perl?src=programming_resource_menu3">Recent Perl posts</a></li>
<li class="last"><a href="https://developers.redhat.com/?intcmp=7016000000127cYAAQ&amp;src=programming_resource_menu4">Red Hat Developers Blog</a></li>
</ul></div></div>  </div>  </div>    </div>
  
  
  
  
  
  
</div></div>So far you've created a file and told Git about it, and now it's time to create a <em>commit</em>. Commit can be thought of as a milestone. Every time you accomplish some work, you can write a Git commit to store that version of your file, so you can go back later and see what it looked like at that point in time. Whenever you make a change to your file, you create a new version of that file, different from the previous one.</p>

<p>To make a commit, enter:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">git commit -m &quot;first commit&quot;</code></span></pre>

<p>That's it! You just created a Git commit and included a message that says <em>first commit</em>. You must always write a message in commit; it not only helps you identify a commit, but it also enables you to understand what you did with the file at that point. So tomorrow, if you add a new piece of code in your file, you can write a commit message that says, <em>Added new code</em>, and when you come back in a month to look at your commit history or Git log (the list of commits), you will know what you changed in the files.</p>

<h2>Step 5: Connect your GitHub repo with your computer</h2>

<p>Now, it's time to connect your computer to GitHub with the command:</p>

<pre>
<span class="geshifilter"><code class="text geshifilter-text">git remote add origin https://github.com/&lt;your_username&gt;/Demo.git</code></span></pre>

<p>Let's look at this command step by step. We are telling Git to add a <code>remote</code> called <code>origin</code> with the address <code>https://github.com/&lt;your_username&gt;/Demo.git</code> (i.e., the URL of your Git repo on GitHub.com). This allows you to interact with your Git repository on GitHub.com by typing <code>origin</code> instead of the full URL and Git will know where to send your code. Why <code>origin</code>? Well, you can name it anything else if you'd like.</p>

<p>Now we have connected our local copy of the <em>Demo</em> repository to its remote counterpart on GitHub.com. Your terminal looks like this:</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384226" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384226">git_guide8.png</a></h2>
    
  
  <div class="content">
    <img alt="Terminal" title="Terminal" class="media-element file-default" data-delta="7" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide8.png" width="650" height="442" /></div>

  
</div>
</div>

<p>Now that we have added the remote, we can push our code (i.e., upload our <code>README.md</code> file) to GitHub.com.</p>

<p>Once you are done, your terminal will look like this:</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384231" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384231">git_guide9.png</a></h2>
    
  
  <div class="content">
    <img alt="Terminal" title="Terminal" class="media-element file-default" data-delta="8" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide9.png" width="650" height="390" /></div>

  
</div>
</div>

<p>And if you go to <code>https://github.com/&lt;your_username&gt;/Demo</code> you will see something like this:</p>

<p></p><div class="media media-element-container media-default media-wysiwyg-align-center"><div id="file-384236" class="file file-image file-image-png">

        <h2 class="element-invisible"><a href="/file/384236">git_guide10.png</a></h2>
    
  
  <div class="content">
    <img alt="Demo repo on GitHub" title="Demo repo on GitHub" class="media-element file-default" data-delta="9" typeof="foaf:Image" src="https://opensource.com/sites/default/files/u128651/git_guide10.png" width="650" height="345" /></div>

  
</div>
</div>

<p>That's it! You have created your first GitHub repo, connected it to your computer, and pushed (or uploaded) a file from your computer to your repository called <em>Demo</em> on GitHub.com. Next time, I will write about Git cloning (downloading your code from GitHub to your computer), adding new files, modifying existing files, and pushing (uploading) files to GitHub.</p>
</div></div></div>
  
  </div>
<div class="panel-pane pane-views-panes pane-listacles-panel-pane-1"  >
  
      
  
  <div class="view view-listacles view-id-listacles view-display-id-panel_pane_1 view-dom-id-f438d59d23719b8d5ddfc959276d4281">
        
  
  
      <div class="view-content">
              
  <div class="views-field views-field-field-listacles">        <div class="field-content"></div>  </div>      </div>
  
  
  
  
  
  
</div>
  
  </div>
<div class="panel-pane pane-entity-field pane-node-field-tags"  >
  
        <h2 class="pane-title">
      Topics    </h2>
    
  
  <div class="field field-name-field-tags field-type-taxonomy-term-reference field-label-hidden"><div class="field-items"><div class="field-item even" rel="schema:keywords"><a href="/tags/git" typeof="skos:Concept" property="rdfs:label skos:prefLabel" datatype="">Git</a></div><div class="field-item odd" rel="schema:keywords"><a href="/tags/programming" typeof="skos:Concept" property="rdfs:label skos:prefLabel" datatype="">Programming</a></div><div class="field-item even" rel="schema:keywords"><a href="/tags/how-tos-and-tutorials" typeof="skos:Concept" property="rdfs:label skos:prefLabel" datatype="">How-tos and tutorials</a></div></div></div>
  
  </div>
<div class="panel-pane pane-views-panes pane-author-info-panel-pane-1"  >
  
      
  
  <div class="view view-author-info view-id-author_info view-display-id-panel_pane_1 view-dom-id-a1899b946181bfce45617995980fa831">
        
  
  
      <div class="view-content">
              
  <div class="authorbio">        <h2 class="authorbio__pane-title pane-title">About the author</h2>
<div class="authorbio__thumbnail"><a href="/users/kkulkarn"><img class="profile-pictures" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/profile_pictures/public/pictures/whatsapp_image_2018-01-10_at_1.01.03_pm.jpeg?itok=vFfSkjdz" width="100" height="100" alt="" /></a></div>
<div class="authorbio__content">
  <span class="authorbio__name">Kedar Vijay Kulkarni</span> - <span class="authorbio__about">Kedar is a Software Quality Engineer at Red Hat working with CloudForms(upstream ManageIQ) project and primarily looking at integration of Ansible with CloudForms and Remote Consoles for various Cloud/Infrastructure Providers. In his free time he likes to Travel, watch interesting videos, learn about new technologies.
</span>
  <div class="authorbio__more-link"><a href="/users/kkulkarn">More about me</a></div>
</div>  </div>      </div>
  
  
  
  
  
  
</div>
  
  </div>
<div class="panel-pane pane-os-content-article-contributions"  >
  
      
  
  <div class="item-list"><ul><li class="first last"><a href="/participate">Learn how you can contribute</a></li>
</ul></div>
  
  </div>
<div class="panel-pane pane-block pane-bean-article-promo-block"  >
  
      
  
  <div class="entity entity-bean bean-generic-block clearfix" about="/block/article-promo-block" typeof="">

  <div class="content">
    <div class="field field-name-field-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even"></div></div></div>  </div>
</div>

  
  </div>
    </div>
  
      <div class="os-article__bottom">
      <div class="panel-pane pane-views-panes pane-related-articles-panel-pane-1"  >
  
        <h2 class="pane-title">
      Recommended reading    </h2>
    
  
  <div class="view view-related-articles view-id-related_articles view-display-id-panel_pane_1 related-content view-dom-id-a9db6e22a545e0b7cadbae14ef3edadb">
        
  
  
      <div id="related-content-footer" class="view-content">
        <div class="views-row views-row-1 views-row-odd views-row-first">      
  <div class="views-field views-field-title">        <span class="field-content"><a href="/article/19/5/primer-assemblers-compilers-interpreters"><img class="related-content-lead-thumbnail" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/related-content-lead-thumbnail/public/lead-images/programming_keyboard_coding.png?itok=PMb0eF7s" width="315" height="177" alt="keyboard with connected dots" title="keyboard with connected dots" /><br />
A short primer on assemblers, compilers, and interpreters</a></span>  </div>  </div>  <div class="views-row views-row-2 views-row-even">      
  <div class="views-field views-field-title">        <span class="field-content"><a href="/article/19/5/practical-learning-exercise-git"><img class="related-content-lead-thumbnail" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/related-content-lead-thumbnail/public/lead-images/todo_checklist_team_metrics_report.png?itok=6EH_6l5O" width="315" height="177" alt="Team checklist and to dos" title="Team checklist and to dos" /><br />
A practical learning exercise for Git</a></span>  </div>  </div>  <div class="views-row views-row-3 views-row-odd">      
  <div class="views-field views-field-title">        <span class="field-content"><a href="/article/19/5/how-write-good-c-main-function"><img class="related-content-lead-thumbnail" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/related-content-lead-thumbnail/public/lead-images/code_hand_draw.png?itok=chLrHOjF" width="315" height="177" alt="Hand drawing out the word &quot;code&quot;" title="Hand drawing out the word &quot;code&quot;" /><br />
How to write a good C main function</a></span>  </div>  </div>  <div class="views-row views-row-4 views-row-even">      
  <div class="views-field views-field-title">        <span class="field-content"><a href="/article/19/5/api-evolution-right-way"><img class="related-content-lead-thumbnail" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/related-content-lead-thumbnail/public/lead-images/browser_desktop_website_checklist_metrics.png?itok=udHRUIdt" width="315" height="177" alt="Browser of things" title="Browser of things" /><br />
API evolution the right way</a></span>  </div>  </div>  <div class="views-row views-row-5 views-row-odd">      
  <div class="views-field views-field-title">        <span class="field-content"><a href="/article/19/4/command-line-playgrounds-webassembly"><img class="related-content-lead-thumbnail" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/related-content-lead-thumbnail/public/lead-images/programming_language_c.png?itok=-zpQtkr_" width="315" height="177" alt="Various programming languages in use" title="Various programming languages in use" /><br />
Level up command-line playgrounds with WebAssembly</a></span>  </div>  </div>  <div class="views-row views-row-6 views-row-even views-row-last">      
  <div class="views-field views-field-title">        <span class="field-content"><a href="/article/19/4/what-do-you-love-about-git"><img class="related-content-lead-thumbnail" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/related-content-lead-thumbnail/public/lead-images/fail_progress_cycle_momentum_arrow.png?itok=ZB2_YnGY" width="315" height="177" alt="arrows cycle symbol for failing faster" title="arrows cycle symbol for failing faster" /><br />
Happy 14th anniversary Git: What do you love about Git?</a></span>  </div>  </div>    </div>
  
  
  
  
  
  
</div>
  
  </div>
    </div>
  
      <div class="os-article__footer">
      <div class="panel-pane pane-node-comments"  id="comments" >
  
        <h2 class="pane-title">
      10 Comments    </h2>
    
  
  <a id="comment-148976"></a>
<div class="comment first odd clearfix" about="/comment/148976#comment-148976" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/pictures/jm_0.jpeg?itok=b5SjxNL8" width="50" height="50" alt="JeffMacharyas" title="JeffMacharyas" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-25T09:47:19-05:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/jeffmacharyas" class="username">Jeff Macharyas</a> on 25 Jan 2018</span>    <a href="/comment/148976#comment-148976" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>Wow, this would have come in handy three years ago when I had to post a PostgreSQL test to GitHub and had no idea what Git or PostgreSQL even was. Thanks for the very clear instructions.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-148976">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">4</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-148996"></a>
<div class="comment comment-by-anonymous even clearfix" about="/comment/148996#comment-148996" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/osdc_default_avatar.png?itok=pk-4pxZV" width="50" height="50" alt="john379" title="john379" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-25T13:00:44-05:00" datatype="xsd:dateTime" rel="sioc:has_creator">john379 on 25 Jan 2018</span>    <a href="/comment/148996#comment-148996" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>I often see github used as personal pages and even blogs - maybe a little coverage on this aspect of it in your series:) Also, noticed the RSS link on top and have added it to my feeds. I like the presentation and style - very easy to follow!</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-148996">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">3</span>
  </div>

  </div>
  </div>
</div>

<div class="indented"><a id="comment-149006"></a>
<div class="comment comment-by-node-author odd clearfix" about="/comment/149006#comment-149006" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/pictures/whatsapp_image_2018-01-10_at_1.01.03_pm.jpeg?itok=X0Hx_YET" width="50" height="50" alt="kkulkarn" title="kkulkarn" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-25T15:10:07-05:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/kkulkarn" class="username">Kedar Vijay Kulkarni</a> on 25 Jan 2018</span>    <a href="/comment/149006#comment-149006" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><span rel="sioc:reply_of" resource="/comment/148996#comment-148996" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>Sure. Thanks for the feedback. I will definitely consider adding article on Personal Pages/Site using git repo. It is interesting and everyone should know it before they decide to go somewhere else for hosting their blog.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-149006">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">1</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-154086"></a>
<div class="comment even clearfix" about="/comment/154086#comment-154086" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/pictures/intothewild.jpg?itok=3v_a3h4d" width="50" height="50" alt="psachin" title="psachin" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-04-19T02:36:37-04:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/psachin" class="username">Sachin Patil</a> on 19 Apr 2018</span>    <a href="/comment/154086#comment-154086" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><span rel="sioc:reply_of" resource="/comment/148996#comment-148996" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>I think you are looking for <a href="https://pages.github.com/">https://pages.github.com/</a>. It covers steps to get you started.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-154086">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">0</span>
  </div>

  </div>
  </div>
</div>
</div><a id="comment-149036"></a>
<div class="comment odd clearfix" about="/comment/149036#comment-149036" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/pictures/snimok.jpg?itok=VQCxHNf5" width="50" height="50" alt="chrissymclennon" title="chrissymclennon" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-26T05:54:41-05:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/chrissymclennon" class="username">Chrissy McLennon</a> on 26 Jan 2018</span>    <a href="/comment/149036#comment-149036" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>Amazing guide! Really helpful for someone who's only starting!</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-149036">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">1</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-149061"></a>
<div class="comment comment-by-anonymous even clearfix" about="/comment/149061#comment-149061" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/osdc_default_avatar.png?itok=pk-4pxZV" width="50" height="50" alt="Catalin(ux) M. Boie" title="Catalin(ux) M. Boie" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-26T13:16:33-05:00" datatype="xsd:dateTime" rel="sioc:has_creator">Catalin(ux) M. Boie on 26 Jan 2018</span>    <a href="/comment/149061#comment-149061" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>Hello!</p>
<p>Nice article.</p>
<p>If you do not like a proprietary solution to host your projects, there are alternatives, easy to use online or install on your servers.</p>
<p>For example, <a href="https://rocketgit.com">https://rocketgit.com</a></p>
<p>It is the only AGPL product on the market, respecting contributors copyright and protecting their work.</p>
<p>Full disclosure: I am the author of the RocketGit project.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-149061">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">2</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-149076"></a>
<div class="comment odd clearfix" about="/comment/149076#comment-149076" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/pictures/my_famous_self_photo_2013.png?itok=9SmoYGrC" width="50" height="50" alt="Nikki F. Nelson" title="Nikki F. Nelson" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-26T14:20:05-05:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/nikki-f-nelson" class="username">Li&#039;lGet</a> on 26 Jan 2018</span>    <a href="/comment/149076#comment-149076" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>This*Helps*!* - I have been flirting with GitHub and more but? I have yet 2 flex my IT*Muscles. Much *Appreciated*!* Tyou ~*;p HavGr8*Techno*Day!<br />
*inspired-li'lGet</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-149076">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">1</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-149111"></a>
<div class="comment even clearfix" about="/comment/149111#comment-149111" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/pictures/wft1.png?itok=V88RfAtg" width="50" height="50" alt="Lhasadad" title="Lhasadad" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-01-27T21:42:45-05:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/lhasadad" class="username">Bill Trautman</a> on 27 Jan 2018</span>    <a href="/comment/149111#comment-149111" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>Nice and concise.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-149111">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">1</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-150096"></a>
<div class="comment odd clearfix" about="/comment/150096#comment-150096" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/osdc_default_avatar.png?itok=pk-4pxZV" width="50" height="50" alt="GaelleTjat" title="GaelleTjat" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-02-14T12:53:20-05:00" datatype="xsd:dateTime" rel="sioc:has_creator"><a href="/users/gaelletjat" class="username">Tomut</a> on 14 Feb 2018</span>    <a href="/comment/150096#comment-150096" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>Thank you Kedar.</p>
<p>Yesterday I was exactly struggling with git.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-150096">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">0</span>
  </div>

  </div>
  </div>
</div>
<a id="comment-150161"></a>
<div class="comment comment-by-anonymous last even clearfix" about="/comment/150161#comment-150161" typeof="sioc:Post sioct:Comment">

  <div class="user-picture-badges">
    <img class="comment-avatar" typeof="foaf:Image" src="https://opensource.com/sites/default/files/styles/comment_avatar/public/osdc_default_avatar.png?itok=pk-4pxZV" width="50" height="50" alt="dbmuse" title="dbmuse" />      </div>

  
  <div class="submitted">
    <span property="dc:date dc:created" content="2018-02-15T00:52:16-05:00" datatype="xsd:dateTime" rel="sioc:has_creator">dbmuse on 15 Feb 2018</span>    <a href="/comment/150161#comment-150161" class="permalink" rel="bookmark">Permalink</a>      </div>

  <div class="content">
    <span rel="sioc:reply_of" resource="/article/18/1/step-step-guide-git" class="rdf-meta element-hidden"></span><div class="field field-name-comment-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even" property="content:encoded"><p>seems like the upload file section would be step 6 following the format of previous steps.  I liked it.</p>
</div></div></div>      </div>

  <div class="comment__meta">
        <div class="vud-widget vud-widget-upanddown" id="widget-comment-150161">
  <div class="up-score clear-block">
                    <div class="up-active" title="Vote up!"></div>
          <div class="element-invisible">Vote up!</div>
              <span class="up-current-score">0</span>
  </div>

  </div>
  </div>
</div>

  
  </div>
<div class="panel-pane pane-entity-field pane-node-field-default-license"  >
  
      
  
  <div class="field field-name-field-default-license field-type-text field-label-hidden"><div class="field-items"><div class="field-item even" property="schema:license"><a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
        <img alt="Creative Commons License" style="border-width:0" src="/sites/all/themes/opensource/images/cc-by-sa-4.png" title="This work is licensed under a Creative Commons Attribution-Share Alike 4.0 International License." /></a></div></div></div>
  
  </div>
    </div>
  
</div>
                  </div>


        
        
      </div>

        <div class="region region-pre-footer">
    <div id="block-os-common-components-footer-call-to-action" class="block block-os-common-components first last odd">

      
  
<div class="fieldable-panels-pane cta cta--blue-on-gray cta--with-link">

  <div class="cta__content cta__content--with-link">
                <h2 class="cta__title">Join us on IRC</h2>
<div class="field field-name-field-cta-content field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even"><p>Connect with Opensource.com editors, community moderators, and writers on Freenode IRC in the #opensource.com channel.</p>
</div></div></div>  </div>

  <div class="cta__link">
    <div class="field field-name-field-cta-link field-type-link-field field-label-hidden"><div class="field-items"><div class="field-item even"><a href="https://opensource.com/life/16/6/irc-quickstart-guide?utm_source=intcta">Join us on IRC</a></div></div></div>  </div>
</div>


</div>
  </div>

        <div class="region region-footer-nav">
    <div id="block-bean-social-media" class="block block-bean first odd">

      
  <div class="entity entity-bean bean-generic-block clearfix" about="/block/social-media" typeof="">

  <div class="content">
    <div class="field field-name-field-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even"><p><span>Find us:</span> 
</p>
<ul>
<li><a class="footer-twitter" href="https://twitter.com/OpenSourceWay" title="Twitter">Twitter</a></li>
<li><a class="footer-facebook" href="https://www.facebook.com/opensourceway" title="Facebook">Facebook</a></li>
<li><a class="footer-instagram" href="https://www.instagram.com/opensourceway/" title="Instagram">Instagram</a></li>
<li><a class="footer-youtube" href="http://www.youtube.com/opensourceway" title="Youtube">Youtube</a></li>
<!-- <li><a class="footer-linkedin" href="https://www.linkedin.com/grps/Open-Source-Professionals-Advocates-2769297" title="LinkedIn">LinkedIn</a></li> --><li><a class="footer-irc" href="/join-us-irc" title="IRC">IRC</a></li>
<li><a class="footer-feed" href="/feed" title="RSS">RSS</a></li>
</ul>
</div></div></div>  </div>
</div>

</div>
<div id="block-menu-menu-footer" class="block block-menu last even" role="navigation">

        <h2 class="block__title block-title">Footer</h2>
    
  <ul class="menu"><li class="menu__item is-leaf first leaf"><a href="/privacy-policy" class="menu__link">Privacy Policy</a></li>
<li class="menu__item is-leaf leaf"><a href="/legal" class="menu__link">Terms of Use</a></li>
<li class="menu__item is-leaf leaf"><a href="/contact" class="menu__link">Contact</a></li>
<li class="menu__item is-leaf leaf"><a href="/opensourcecom-team" title="" class="menu__link">Meet the Team</a></li>
<li class="menu__item is-leaf last leaf"><a href="http://opensource.org/" title="" class="menu__link">Visit opensource.org</a></li>
</ul>
</div>
  </div>

        <footer id="footer" class="region region-footer">
    <div id="block-bean-copyrigt-block" class="block block-bean first odd">

      
  <div class="entity entity-bean bean-generic-block clearfix" about="/block/copyrigt-block" typeof="">

  <div class="content">
    <div class="field field-name-field-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even"><p>For more discussion on open source and the role of the CIO in the enterprise, join us at <a href="https://enterprisersproject.com">The EnterprisersProject.com</a>.</p>

<p>The opinions expressed on this website are those of each author, not of the author's employer or of Red Hat.</p>

<p>Opensource.com aspires to publish all content under a <a href="http://creativecommons.org/licenses/">Creative Commons license</a> but may not be able to do so in all cases. You are responsible for ensuring that you have the necessary permission to reuse any work on this site. Red Hat and the Red Hat logo are trademarks of Red Hat, Inc., registered in the United States and other countries.</p>

<p>Copyright ©2019 Red Hat, Inc.</p>
</div></div></div>  </div>
</div>

</div>
<div id="block-bean-footer-logo" class="block block-bean last even">

      
  <div class="entity entity-bean bean-generic-block clearfix" about="/block/footer-logo" typeof="">

  <div class="content">
    <div class="field field-name-field-body field-type-text-long field-label-hidden"><div class="field-items"><div class="field-item even"><p><img src="/sites/all/themes/opensource/images/footer_logo.svg" /></p>
</div></div></div>  </div>
</div>

</div>
  </footer>

    </div>

    
      <div class="region region-os-social">
    <div id="block-os-social-os-social-share" class="block block-os-social first last odd">

      
  <div class="a2a_kit a2a_kit_size_32 a2a_floating_style a2a_vertical_style" data-a2a-url="https://opensource.com/article/18/1/step-step-guide-git">
  <a class="a2a_button_twitter a2a_counter"></a>
  <a class="a2a_button_facebook a2a_counter"></a>
  <a class="a2a_button_linkedin a2a_counter"></a>
  <a class="a2a_button_reddit a2a_counter"></a>
  <a class="a2a_button_google_plus a2a_counter"></a>
  <a class="a2a_button_email a2a_counter"></a>
  <!--a class="a2a_dd" href="https://www.addtoany.com/share"></a-->
  </div><div class="a2a_kit a2a_kit_size_32 a2a_floating_style a2a_default_style">
  <a class="a2a_button_twitter a2a_counter"></a>
  <a class="a2a_button_facebook a2a_counter"></a>
  <a class="a2a_button_linkedin a2a_counter"></a>
  <a class="a2a_button_reddit a2a_counter"></a>
  <a class="a2a_button_google_plus a2a_counter"></a>
  <a class="a2a_button_email a2a_counter"></a>
  <!--a class="a2a_dd" href="https://www.addtoany.com/share"></a-->
  </div>
</div>
  </div>
    <div class="region region-page-bottom">
    <!-- begin Google Remarketing --><img height="1" width="1" style="border-style:none;display:block;" alt="" src="//googleads.g.doubleclick.net/pagead/viewthroughconversion/990030321/?value=0&amp;label=rxV4CN_35QQQ8dOK2AM&amp;guid=ON&amp;script=0" onerror="this.src='/sites/all/themes/opensource/images/1x1.png';this.onerror=null" /><!-- end Google Remarketing -->  </div>
<script src="https://opensource.com/sites/default/files/js/js_29qYXJz8NLGg8Aomg-RZPjJcj9yEdEst1BMZ9gZbs-4.js"></script>
<script>if (("undefined" !== typeof _satellite) && ("function" === typeof _satellite.pageBottom)) {_satellite.pageBottom();}</script>
<script>var a2a_config = a2a_config || {};
              a2a_config.callbacks = a2a_config.callbacks || [];
a2a_config.templates = {
    twitter: "A step-by-step guide to Git https://red.ht/2mrYzfE via @opensourceway"
};</script>
</body>
</html>


