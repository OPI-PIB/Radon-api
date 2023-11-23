<!DOCTYPE html>
<html class="" lang="en">
<head prefix="og: http://ogp.me/ns#">
<meta charset="utf-8">
<link as="style" href="https://gitlab.opi.org.pl/assets/application-2cb8d6d6d17f1b1b8492581de92356755b864cbb6e48347a65baa2771a10ae4f.css" rel="preload">
<link as="style" href="https://gitlab.opi.org.pl/assets/highlight/themes/white-23255bab077a3cc8d17b4b7004aa866e340b0009c7897b509b5d0086710b698f.css" rel="preload">

<meta content="IE=edge" http-equiv="X-UA-Compatible">

<meta content="object" property="og:type">
<meta content="GitLab" property="og:site_name">
<meta content="API RAD-on/readme.md · master · LBD / data science" property="og:title">
<meta content="GitLab Community Edition" property="og:description">
<meta content="https://gitlab.opi.org.pl/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="og:image">
<meta content="64" property="og:image:width">
<meta content="64" property="og:image:height">
<meta content="https://gitlab.opi.org.pl/lbd/data-science/-/blob/master/API%20RAD-on/readme.md" property="og:url">
<meta content="summary" property="twitter:card">
<meta content="API RAD-on/readme.md · master · LBD / data science" property="twitter:title">
<meta content="GitLab Community Edition" property="twitter:description">
<meta content="https://gitlab.opi.org.pl/assets/gitlab_logo-7ae504fe4f68fdebb3c2034e36621930cd36ea87924c11ff65dbcb8ed50dca58.png" property="twitter:image">

<title>API RAD-on/readme.md · master · LBD / data science · GitLab</title>
<meta content="GitLab Community Edition" name="description">
<link rel="prefetch" href="/assets/webpack/monaco.77ef6b58.chunk.js">
<link rel="shortcut icon" type="image/png" href="/assets/favicon-7901bd695fb93edb07975966062049829afb56cf11511236e61bcf425070e36e.png" id="favicon" data-original-href="/assets/favicon-7901bd695fb93edb07975966062049829afb56cf11511236e61bcf425070e36e.png" />
<style>
@keyframes blinking-dot{0%{opacity:1}25%{opacity:0.4}75%{opacity:0.4}100%{opacity:1}}@keyframes blinking-scroll-button{0%{opacity:0.2}50%{opacity:1}100%{opacity:0.2}}@keyframes gl-spinner-rotate{0%{transform:rotate(0)}100%{transform:rotate(360deg)}}body.ui-dark .navbar-gitlab{background-color:#303030}body.ui-dark .navbar-gitlab .navbar-collapse{color:#bfbfbf}body.ui-dark .navbar-gitlab .container-fluid .navbar-toggler{border-left:1px solid gray}body.ui-dark .navbar-gitlab .container-fluid .navbar-toggler svg{fill:#bfbfbf}body.ui-dark .navbar-gitlab .navbar-sub-nav>li>a:hover,body.ui-dark .navbar-gitlab .navbar-sub-nav>li>a:focus,body.ui-dark .navbar-gitlab .navbar-sub-nav>li>button:hover,body.ui-dark .navbar-gitlab .navbar-sub-nav>li>button:focus,body.ui-dark .navbar-gitlab .navbar-nav>li>a:hover,body.ui-dark .navbar-gitlab .navbar-nav>li>a:focus,body.ui-dark .navbar-gitlab .navbar-nav>li>button:hover,body.ui-dark .navbar-gitlab .navbar-nav>li>button:focus{background-color:rgba(191,191,191,0.2)}body.ui-dark .navbar-gitlab .navbar-sub-nav>li.active>a,body.ui-dark .navbar-gitlab .navbar-sub-nav>li.active>button,body.ui-dark .navbar-gitlab .navbar-sub-nav>li.dropdown.show>a,body.ui-dark .navbar-gitlab .navbar-sub-nav>li.dropdown.show>button,body.ui-dark .navbar-gitlab .navbar-nav>li.active>a,body.ui-dark .navbar-gitlab .navbar-nav>li.active>button,body.ui-dark .navbar-gitlab .navbar-nav>li.dropdown.show>a,body.ui-dark .navbar-gitlab .navbar-nav>li.dropdown.show>button{color:#303030;background-color:#fff}body.ui-dark .navbar-gitlab .navbar-sub-nav>li.line-separator,body.ui-dark .navbar-gitlab .navbar-nav>li.line-separator{border-left:1px solid rgba(191,191,191,0.2)}body.ui-dark .navbar-gitlab .navbar-sub-nav{color:#bfbfbf}body.ui-dark .navbar-gitlab .nav>li{color:#bfbfbf}body.ui-dark .navbar-gitlab .nav>li>a .notification-dot{border:2px solid #303030}body.ui-dark .navbar-gitlab .nav>li>a.header-help-dropdown-toggle .notification-dot{background-color:#bfbfbf}body.ui-dark .navbar-gitlab .nav>li>a.header-user-dropdown-toggle .header-user-avatar{border-color:#bfbfbf}@media (min-width: 576px){body.ui-dark .navbar-gitlab .nav>li>a:hover,body.ui-dark .navbar-gitlab .nav>li>a:focus{background-color:rgba(191,191,191,0.2)}}body.ui-dark .navbar-gitlab .nav>li>a:hover svg,body.ui-dark .navbar-gitlab .nav>li>a:focus svg{fill:currentColor}body.ui-dark .navbar-gitlab .nav>li>a:hover .notification-dot,body.ui-dark .navbar-gitlab .nav>li>a:focus .notification-dot{will-change:border-color, background-color;border-color:#515151}body.ui-dark .navbar-gitlab .nav>li>a:hover.header-help-dropdown-toggle .notification-dot,body.ui-dark .navbar-gitlab .nav>li>a:focus.header-help-dropdown-toggle .notification-dot{background-color:#fff}body.ui-dark .navbar-gitlab .nav>li.active>a,body.ui-dark .navbar-gitlab .nav>li.dropdown.show>a{color:#303030;background-color:#fff}body.ui-dark .navbar-gitlab .nav>li.active>a:hover svg,body.ui-dark .navbar-gitlab .nav>li.dropdown.show>a:hover svg{fill:#303030}body.ui-dark .navbar-gitlab .nav>li.active>a .notification-dot,body.ui-dark .navbar-gitlab .nav>li.dropdown.show>a .notification-dot{border-color:#fff}body.ui-dark .navbar-gitlab .nav>li.active>a.header-help-dropdown-toggle .notification-dot,body.ui-dark .navbar-gitlab .nav>li.dropdown.show>a.header-help-dropdown-toggle .notification-dot{background-color:#303030}body.ui-dark .navbar-gitlab .nav>li .impersonated-user svg,body.ui-dark .navbar-gitlab .nav>li .impersonated-user:hover svg{fill:#303030}body.ui-dark .navbar .title>a:hover,body.ui-dark .navbar .title>a:focus{background-color:rgba(191,191,191,0.2)}body.ui-dark .search form{background-color:rgba(191,191,191,0.2)}body.ui-dark .search form:hover{background-color:rgba(191,191,191,0.3)}body.ui-dark .search .search-input::-ms-input-placeholder{color:rgba(191,191,191,0.8)}body.ui-dark .search .search-input::placeholder{color:rgba(191,191,191,0.8)}body.ui-dark .search .search-input-wrap .search-icon,body.ui-dark .search .search-input-wrap .clear-icon{fill:rgba(191,191,191,0.8)}body.ui-dark .search.search-active form{background-color:#fff}body.ui-dark .search.search-active .search-input-wrap .search-icon{fill:rgba(191,191,191,0.8)}body.ui-dark .nav-sidebar li.active{box-shadow:inset 4px 0 0 #666}body.ui-dark .nav-sidebar li.active>a{color:#525252}body.ui-dark .nav-sidebar li.active .nav-icon-container svg{fill:#525252}body.ui-dark .sidebar-top-level-items>li.active .badge.badge-pill{color:#525252}body.ui-dark .nav-links li.active a,body.ui-dark .nav-links li.md-header-tab.active button,body.ui-dark .nav-links li a.active{border-bottom:2px solid #999}body.ui-dark .nav-links li.active a .badge.badge-pill,body.ui-dark .nav-links li.md-header-tab.active button .badge.badge-pill,body.ui-dark .nav-links li a.active .badge.badge-pill{font-weight:600}body.ui-dark .emoji-picker-category-active{border-bottom-color:#999}body.ui-dark .branch-header-title{color:#666}body.ui-dark .ide-sidebar-link.active{color:#666;box-shadow:inset 3px 0 #666}body.ui-dark .ide-sidebar-link.active.is-right{box-shadow:inset -3px 0 #666}

*,*::before,*::after{box-sizing:border-box}html{font-family:sans-serif;line-height:1.15}header,nav,section{display:block}body{margin:0;font-family:-apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, "Noto Sans", Ubuntu, Cantarell, "Helvetica Neue", sans-serif, "Apple Color Emoji", "Segoe UI Emoji", "Segoe UI Symbol", "Noto Color Emoji";font-size:1rem;font-weight:400;line-height:1.5;color:#303030;text-align:left;background-color:#fff}h1,h2,h3{margin-top:0;margin-bottom:0.25rem}p{margin-top:0;margin-bottom:1rem}ul{margin-top:0;margin-bottom:1rem}ul ul{margin-bottom:0}strong{font-weight:bolder}sub{position:relative;font-size:75%;line-height:0;vertical-align:baseline}sub{bottom:-.25em}a{color:#007bff;text-decoration:none;background-color:transparent}a:not([href]){color:inherit;text-decoration:none}pre,code{font-family:"Menlo", "DejaVu Sans Mono", "Liberation Mono", "Consolas", "Ubuntu Mono", "Courier New", "andale mono", "lucida console", monospace;font-size:1em}pre{margin-top:0;margin-bottom:1rem;overflow:auto}img{vertical-align:middle;border-style:none}svg{overflow:hidden;vertical-align:middle}table{border-collapse:collapse}th{text-align:inherit}button{border-radius:0}input,button,textarea{margin:0;font-family:inherit;font-size:inherit;line-height:inherit}button,input{overflow:visible}button{text-transform:none}button:not(:disabled),[type="button"]:not(:disabled),[type="reset"]:not(:disabled){cursor:pointer}button::-moz-focus-inner,[type="button"]::-moz-focus-inner,[type="reset"]::-moz-focus-inner{padding:0;border-style:none}textarea{overflow:auto;resize:vertical}[type="search"]{outline-offset:-2px}summary{display:list-item;cursor:pointer}template{display:none}[hidden]{display:none !important}h1,h2,h3,.h1,.h2,.h3{margin-bottom:0.25rem;font-weight:600;line-height:1.2;color:#303030}h1,.h1{font-size:2.1875rem}h2,.h2{font-size:1.75rem}h3,.h3{font-size:1.53125rem}.list-unstyled{padding-left:0;list-style:none}code{font-size:90%;color:#1f1f1f;word-wrap:break-word}a>code{color:inherit}pre{display:block;font-size:90%;color:#303030}pre code{font-size:inherit;color:inherit;word-break:normal}.container{width:100%;padding-right:15px;padding-left:15px;margin-right:auto;margin-left:auto}@media (min-width: 576px){.container{max-width:540px}}@media (min-width: 768px){.container{max-width:720px}}@media (min-width: 992px){.container{max-width:960px}}@media (min-width: 1200px){.container{max-width:1140px}}.container-fluid{width:100%;padding-right:15px;padding-left:15px;margin-right:auto;margin-left:auto}@media (min-width: 576px){.container{max-width:540px}}@media (min-width: 768px){.container{max-width:720px}}@media (min-width: 992px){.container{max-width:960px}}@media (min-width: 1200px){.container{max-width:1140px}}.row{display:flex;flex-wrap:wrap;margin-right:-15px;margin-left:-15px}.table{width:100%;margin-bottom:0.5rem;color:#303030}.table th,.table td{padding:0.75rem;vertical-align:top;border-top:1px solid #dbdbdb}.search form{display:block;width:100%;height:34px;padding:0.375rem 0.75rem;font-size:0.875rem;font-weight:400;line-height:1.5;color:#303030;background-color:#fff;background-clip:padding-box;border:1px solid #dbdbdb;border-radius:0.25rem}.search form:-moz-focusring{color:transparent;text-shadow:0 0 0 #303030}.search form::-ms-input-placeholder{color:#5e5e5e;opacity:1}.search form::placeholder{color:#5e5e5e;opacity:1}.search form:disabled{background-color:#fafafa;opacity:1}.form-inline{display:flex;flex-flow:row wrap;align-items:center}@media (min-width: 576px){.form-inline .search form,.search .form-inline form{display:inline-block;width:auto;vertical-align:middle}}.btn{display:inline-block;font-weight:400;color:#303030;text-align:center;vertical-align:middle;cursor:pointer;-webkit-user-select:none;-moz-user-select:none;-ms-user-select:none;user-select:none;background-color:transparent;border:1px solid transparent;padding:0.375rem 0.75rem;font-size:1rem;line-height:20px;border-radius:0.25rem}.btn.disabled,.btn:disabled{opacity:0.65}a.btn.disabled{pointer-events:none}.collapse:not(.show){display:none}.dropdown{position:relative}.dropdown-menu-toggle{white-space:nowrap}.dropdown-menu-toggle::after{display:inline-block;margin-left:0.255em;vertical-align:0.255em;content:"";border-top:0.3em solid;border-right:0.3em solid transparent;border-bottom:0;border-left:0.3em solid transparent}.dropdown-menu-toggle:empty::after{margin-left:0}.dropdown-menu{position:absolute;top:100%;left:0;z-index:1000;display:none;float:left;min-width:10rem;padding:0.5rem 0;margin:0.125rem 0 0;font-size:1rem;color:#303030;text-align:left;list-style:none;background-color:#fff;background-clip:padding-box;border:1px solid rgba(0,0,0,0.15);border-radius:0.25rem}.dropdown-menu-right{right:0;left:auto}.divider{height:0;margin:4px 0;overflow:hidden;border-top:1px solid #dbdbdb}.dropdown-menu.show{display:block}.nav{display:flex;flex-wrap:wrap;padding-left:0;margin-bottom:0;list-style:none}.navbar{position:relative;display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between;padding:0.25rem 0.5rem}.navbar .container,.navbar .container-fluid{display:flex;flex-wrap:wrap;align-items:center;justify-content:space-between}.navbar-nav{display:flex;flex-direction:column;padding-left:0;margin-bottom:0;list-style:none}.navbar-nav .dropdown-menu{position:static;float:none}.navbar-collapse{flex-basis:100%;flex-grow:1;align-items:center}.navbar-toggler{padding:0.25rem 0.75rem;font-size:1.25rem;line-height:1;background-color:transparent;border:1px solid transparent;border-radius:0.25rem}@media (max-width: 575.98px){.navbar-expand-sm>.container,.navbar-expand-sm>.container-fluid{padding-right:0;padding-left:0}}@media (min-width: 576px){.navbar-expand-sm{flex-flow:row nowrap;justify-content:flex-start}.navbar-expand-sm .navbar-nav{flex-direction:row}.navbar-expand-sm .navbar-nav .dropdown-menu{position:absolute}.navbar-expand-sm>.container,.navbar-expand-sm>.container-fluid{flex-wrap:nowrap}.navbar-expand-sm .navbar-collapse{display:flex !important;flex-basis:auto}.navbar-expand-sm .navbar-toggler{display:none}}.card{position:relative;display:flex;flex-direction:column;min-width:0;word-wrap:break-word;background-color:#fff;background-clip:border-box;border:1px solid #dbdbdb;border-radius:0.25rem}.badge{display:inline-block;padding:0.25em 0.4em;font-size:75%;font-weight:600;line-height:1;text-align:center;white-space:nowrap;vertical-align:baseline;border-radius:0.25rem}.badge:empty{display:none}.btn .badge{position:relative;top:-1px}.badge-pill{padding-right:0.6em;padding-left:0.6em;border-radius:10rem}.media{display:flex;align-items:flex-start}.close{float:right;font-size:1.5rem;font-weight:600;line-height:1;color:#000;text-shadow:0 1px 0 #fff;opacity:.5}button.close{padding:0;background-color:transparent;border:0;-webkit-appearance:none;-moz-appearance:none;appearance:none}a.close.disabled{pointer-events:none}.modal-dialog{position:relative;width:auto;margin:0.5rem;pointer-events:none}@media (min-width: 576px){.modal-dialog{max-width:500px;margin:1.75rem auto}}.bg-transparent{background-color:transparent !important}.border{border:1px solid #dbdbdb !important}.border-top{border-top:1px solid #dbdbdb !important}.border-right{border-right:1px solid #dbdbdb !important}.border-bottom{border-bottom:1px solid #dbdbdb !important}.border-left{border-left:1px solid #dbdbdb !important}.rounded{border-radius:0.25rem !important}.clearfix::after{display:block;clear:both;content:""}.d-none{display:none !important}.d-inline-block{display:inline-block !important}.d-block{display:block !important}@media (min-width: 576px){.d-sm-none{display:none !important}}@media (min-width: 768px){.d-md-block{display:block !important}}@media (min-width: 992px){.d-lg-none{display:none !important}.d-lg-block{display:block !important}}@media (min-width: 1200px){.d-xl-block{display:block !important}}.flex-wrap{flex-wrap:wrap !important}.float-right{float:right !important}.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0, 0, 0, 0);white-space:nowrap;border:0}.m-auto{margin:auto !important}.text-nowrap{white-space:nowrap !important}.visible{visibility:visible !important}.search form.focus{color:#303030;background-color:#fff;border-color:#80bdff;outline:0;box-shadow:0 0 0 0.2rem rgba(0,123,255,0.25)}.gl-badge{display:inline-flex;align-items:center;font-size:0.75rem;font-weight:400;line-height:1rem;padding-top:0.25rem;padding-bottom:0.25rem;padding-left:0.5rem;padding-right:0.5rem;outline:none}body,.search form,.search form{font-size:0.875rem}button,html [type='button'],[type='reset'],[role='button']{cursor:pointer}h1,.h1,h2,.h2,h3,.h3{margin-top:20px;margin-bottom:10px}input[type='file']{line-height:1}strong{font-weight:bold}a{color:#1068bf}code{padding:2px 4px;color:#1f1f1f;background-color:#f0f0f0;border-radius:4px}.code>code{background-color:inherit;padding:unset}table{border-spacing:0}.hidden{display:none !important;visibility:hidden !important}.hide{display:none}.dropdown-menu-toggle::after{display:none}.badge:not(.gl-badge){padding:4px 5px;font-size:12px;font-style:normal;font-weight:400;display:inline-block}pre code{white-space:pre-wrap}.toggle-sidebar-button .collapse-text,.toggle-sidebar-button .icon-chevron-double-lg-left,.toggle-sidebar-button .icon-chevron-double-lg-right{color:#666}svg{vertical-align:baseline}html{overflow-y:scroll}body{-webkit-text-decoration-skip:ink;text-decoration-skip:ink}.content-wrapper{margin-top:40px;padding-bottom:100px}.container{padding-top:0;z-index:5}.container .content{margin:0}@media (max-width: 575.98px){.container .content{margin-top:20px}}@media (max-width: 575.98px){.container .container .title{padding-left:15px !important}}.btn{border-radius:4px;font-size:0.875rem;font-weight:400;padding:6px 10px;background-color:#fff;border-color:#dbdbdb;color:#303030;color:#303030;white-space:nowrap}.btn:active,.btn.active{background-color:#eaeaea;border-color:#e3e3e3;color:#303030}.btn svg{height:15px;width:15px}.btn svg:not(:last-child),.btn .fa:not(:last-child){margin-right:5px}.badge.badge-pill:not(.gl-badge){font-weight:400;background-color:rgba(0,0,0,0.07);color:#525252;vertical-align:baseline}.hint{font-style:italic;color:#bfbfbf}.bold{font-weight:600}pre.wrap{word-break:break-word;white-space:pre-wrap}table a code{position:relative;top:-2px;margin-right:3px}.loading{margin:20px auto;height:40px;color:#525252;font-size:32px;text-align:center}.highlight{text-shadow:none}.chart{overflow:hidden;height:220px}.break-word{word-wrap:break-word}.center{text-align:center}.block{display:block}.flex{display:flex}.flex-grow{flex-grow:1}.dropdown{position:relative}.show.dropdown .dropdown-menu{transform:translateY(0);display:block;min-height:40px;max-height:312px;overflow-y:auto}@media (max-width: 575.98px){.show.dropdown .dropdown-menu{width:100%}}.show.dropdown .dropdown-menu-toggle,.show.dropdown .dropdown-menu-toggle{border-color:#c4c4c4}.show.dropdown [data-toggle='dropdown']{outline:0}.search-input-container .dropdown-menu{margin-top:11px}.dropdown-menu-toggle{padding:6px 8px 6px 10px;background-color:#fff;color:#303030;font-size:14px;text-align:left;border:1px solid #dbdbdb;border-radius:0.25rem;white-space:nowrap}.no-outline.dropdown-menu-toggle{outline:0}.dropdown-menu-toggle .fa{color:#c4c4c4}.dropdown-menu-toggle{padding-right:25px;position:relative;width:160px;text-overflow:ellipsis;overflow:hidden}.dropdown-menu-toggle .fa{position:absolute}.dropdown-menu{display:none;position:absolute;width:auto;top:100%;z-index:300;min-width:240px;max-width:500px;margin-top:4px;margin-bottom:24px;font-size:14px;font-weight:400;padding:8px 0;background-color:#fff;border:1px solid #dbdbdb;border-radius:0.25rem;box-shadow:0 2px 4px rgba(0,0,0,0.1)}.dropdown-menu ul{margin:0;padding:0}.dropdown-menu li{display:block;text-align:left;list-style:none;padding:0 1px}.dropdown-menu li>a,.dropdown-menu li button{background:transparent;border:0;border-radius:0;box-shadow:none;display:block;font-weight:400;position:relative;padding:8px 12px;color:#303030;line-height:16px;white-space:normal;overflow:hidden;text-align:left;width:100%}.dropdown-menu .divider{height:1px;margin:0.25rem 0;padding:0;background-color:#dbdbdb}.dropdown-menu .badge.badge-pill+span:not(.badge):not(.badge-pill){margin-right:40px}.dropdown-select{width:300px}@media (max-width: 767.98px){.dropdown-select{width:100%}}.dropdown-content{max-height:252px;overflow-y:auto}.dropdown-loading{position:absolute;top:0;right:0;bottom:0;left:0;display:none;z-index:9;background-color:rgba(255,255,255,0.6);font-size:28px}.dropdown-loading .fa{position:absolute;top:50%;left:50%;margin-top:-14px;margin-left:-14px}@media (max-width: 575.98px){.navbar-gitlab li.dropdown{position:static}header.navbar-gitlab .dropdown .dropdown-menu{width:100%;min-width:100%}}@media (max-width: 767.98px){.dropdown-menu-toggle{width:100%}}textarea{resize:vertical}input{border-radius:0.25rem;color:#303030;background-color:#fff}.search form{border-radius:4px;padding:6px 10px}.search form::-ms-input-placeholder{color:#868686}.search form::placeholder{color:#868686}.navbar-gitlab{padding:0 16px;z-index:1000;margin-bottom:0;min-height:40px;border:0;border-bottom:1px solid #dbdbdb;position:fixed;top:0;left:0;right:0;border-radius:0}.navbar-gitlab .logo-text{line-height:initial}.navbar-gitlab .logo-text svg{width:55px;height:14px;margin:0;fill:#fff}.navbar-gitlab .close-icon{display:none}.navbar-gitlab .header-content{width:100%;display:flex;justify-content:space-between;position:relative;min-height:40px;padding-left:0}.navbar-gitlab .header-content .title-container{display:flex;align-items:stretch;flex:1 1 auto;padding-top:0;overflow:visible}.navbar-gitlab .header-content .title{padding-right:0;color:currentColor;display:flex;position:relative;margin:0;font-size:18px;vertical-align:top;white-space:nowrap}.navbar-gitlab .header-content .title img{height:28px}.navbar-gitlab .header-content .title img+.logo-text{margin-left:8px}.navbar-gitlab .header-content .title.wrap{white-space:normal}.navbar-gitlab .header-content .title a{display:flex;align-items:center;padding:2px 8px;margin:5px 2px 5px -8px;border-radius:4px}.navbar-gitlab .header-content .dropdown.open>a{border-bottom-color:#fff}.navbar-gitlab .header-content .navbar-collapse>ul.nav>li:not(.d-none){margin:0 2px}.navbar-gitlab .navbar-collapse{flex:0 0 auto;border-top:0;padding:0}@media (max-width: 575.98px){.navbar-gitlab .navbar-collapse{flex:1 1 auto}}.navbar-gitlab .navbar-collapse .nav{flex-wrap:nowrap}@media (max-width: 575.98px){.navbar-gitlab .navbar-collapse .nav>li:not(.d-none) a{margin-left:0}}.navbar-gitlab .container-fluid{padding:0}.navbar-gitlab .container-fluid .user-counter svg{margin-right:3px}.navbar-gitlab .container-fluid .navbar-toggler{position:relative;right:-10px;border-radius:0;min-width:45px;padding:0;margin:8px -7px 8px 0;font-size:14px;text-align:center;color:currentColor}@media (max-width: 575.98px){.navbar-gitlab .container-fluid .navbar-nav{display:flex;padding-right:10px;flex-direction:row}}.navbar-gitlab .container-fluid .navbar-nav li .badge.badge-pill{box-shadow:none;font-weight:600}@media (max-width: 575.98px){.navbar-gitlab .container-fluid .nav>li.header-user{padding-left:10px}}.navbar-gitlab .container-fluid .nav>li>a{will-change:color;margin:4px 0;padding:6px 8px;height:32px}@media (max-width: 575.98px){.navbar-gitlab .container-fluid .nav>li>a{padding:0}}.navbar-gitlab .container-fluid .nav>li>a.header-user-dropdown-toggle{margin-left:2px}.navbar-gitlab .container-fluid .nav>li>a.header-user-dropdown-toggle .header-user-avatar{margin-right:0}.navbar-gitlab .container-fluid .nav>li .header-new-dropdown-toggle{margin-right:0}.navbar-sub-nav>li>a,.navbar-sub-nav>li>button,.navbar-nav>li>a,.navbar-nav>li>button{display:flex;align-items:center;justify-content:center;padding:6px 8px;margin:4px 2px;font-size:12px;color:currentColor;border-radius:4px;height:32px;font-weight:600}.navbar-sub-nav>li>button,.navbar-nav>li>button{background:transparent;border:0}.navbar-sub-nav .dropdown-menu,.navbar-nav .dropdown-menu{position:absolute}.navbar-sub-nav{display:flex;margin:0 0 0 6px}.caret-down,.btn .caret-down{top:0;height:11px;width:11px;margin-left:4px;fill:currentColor}.header-user .dropdown-menu,.header-new .dropdown-menu{margin-top:4px}.btn-sign-in{background-color:#ebebfa;color:#292961;font-weight:600;line-height:18px;margin:4px 0 4px 2px}.title-container .badge.badge-pill:not(.merge-request-badge),.navbar-nav .badge.badge-pill:not(.merge-request-badge){position:inherit;font-weight:400;margin-left:-6px;font-size:11px;color:#fff;padding:0 5px;line-height:12px;border-radius:7px;box-shadow:0 1px 0 rgba(76,78,84,0.2)}.title-container .badge.badge-pill.green-badge,.navbar-nav .badge.badge-pill.green-badge{background-color:#108548}.title-container .badge.badge-pill.merge-requests-count,.navbar-nav .badge.badge-pill.merge-requests-count{background-color:#de7e00}.title-container .badge.badge-pill.todos-count,.navbar-nav .badge.badge-pill.todos-count{background-color:#1f75cb}.title-container .canary-badge .badge,.navbar-nav .canary-badge .badge{font-size:12px;line-height:16px;padding:0 0.5rem}@media (max-width: 575.98px){.navbar-gitlab .container-fluid{font-size:18px}.navbar-gitlab .container-fluid .navbar-nav{table-layout:fixed;width:100%;margin:0;text-align:right}.navbar-gitlab .container-fluid .navbar-collapse{margin-left:-8px;margin-right:-10px}.navbar-gitlab .container-fluid .navbar-collapse .nav>li:not(.d-none){flex:1}.header-user-dropdown-toggle{text-align:center}.header-user-avatar{float:none}}.header-user.show .dropdown-menu{margin-top:4px;color:#303030;left:auto;max-height:445px}.header-user.show .dropdown-menu svg{vertical-align:text-top}.header-user-avatar{float:left;margin-right:5px;border-radius:50%;border:1px solid #f5f5f5}.media{display:flex;align-items:flex-start}.card{margin-bottom:16px}.content-wrapper{width:100%}.content-wrapper .container-fluid{padding:0 16px}@media (min-width: 768px){.page-with-contextual-sidebar{padding-left:50px}}@media (min-width: 1200px){.page-with-contextual-sidebar{padding-left:220px}}.context-header{position:relative;margin-right:2px;width:220px}.context-header>a,.context-header>button{font-weight:600;display:flex;width:100%;align-items:center;padding:10px 16px 10px 10px;color:#303030;background-color:transparent;border:0;text-align:left}.context-header .avatar-container{flex:0 0 40px;background-color:#fff}.context-header .sidebar-context-title{overflow:hidden;text-overflow:ellipsis}.context-header .sidebar-context-title.text-secondary{font-weight:normal;font-size:0.8em}.nav-sidebar{position:fixed;z-index:600;width:220px;top:40px;bottom:0;left:0;background-color:#fafafa;box-shadow:inset -1px 0 0 #dbdbdb;transform:translate3d(0, 0, 0)}@media (min-width: 576px) and (max-width: 576px){.nav-sidebar:not(.sidebar-collapsed-desktop){box-shadow:inset -1px 0 0 #dbdbdb,2px 1px 3px rgba(0,0,0,0.1)}}.nav-sidebar.sidebar-collapsed-desktop{width:50px}.nav-sidebar.sidebar-collapsed-desktop .nav-sidebar-inner-scroll{overflow-x:hidden}.nav-sidebar.sidebar-collapsed-desktop .badge.badge-pill:not(.fly-out-badge),.nav-sidebar.sidebar-collapsed-desktop .sidebar-context-title,.nav-sidebar.sidebar-collapsed-desktop .nav-item-name{border:0;clip:rect(0, 0, 0, 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;white-space:nowrap;width:1px}.nav-sidebar.sidebar-collapsed-desktop .sidebar-top-level-items>li>a{min-height:45px}.nav-sidebar.sidebar-collapsed-desktop .fly-out-top-item{display:block}.nav-sidebar.sidebar-collapsed-desktop .avatar-container{margin:0 auto}.nav-sidebar.sidebar-expanded-mobile{left:0}.nav-sidebar a{text-decoration:none}.nav-sidebar ul{padding-left:0;list-style:none}.nav-sidebar li{white-space:nowrap}.nav-sidebar li a{display:flex;align-items:center;padding:12px 16px;color:#666}.nav-sidebar li .nav-item-name{flex:1}.nav-sidebar li.active>a{font-weight:600}@media (max-width: 767.98px){.nav-sidebar{left:-220px}}.nav-sidebar .nav-icon-container{display:flex;margin-right:8px}.nav-sidebar .fly-out-top-item{display:none}.nav-sidebar svg{height:16px;width:16px}@media (min-width: 768px) and (max-width: 1199px){.nav-sidebar:not(.sidebar-expanded-mobile){width:50px}.nav-sidebar:not(.sidebar-expanded-mobile) .nav-sidebar-inner-scroll{overflow-x:hidden}.nav-sidebar:not(.sidebar-expanded-mobile) .badge.badge-pill:not(.fly-out-badge),.nav-sidebar:not(.sidebar-expanded-mobile) .sidebar-context-title,.nav-sidebar:not(.sidebar-expanded-mobile) .nav-item-name{border:0;clip:rect(0, 0, 0, 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;white-space:nowrap;width:1px}.nav-sidebar:not(.sidebar-expanded-mobile) .sidebar-top-level-items>li>a{min-height:45px}.nav-sidebar:not(.sidebar-expanded-mobile) .fly-out-top-item{display:block}.nav-sidebar:not(.sidebar-expanded-mobile) .avatar-container{margin:0 auto}.nav-sidebar:not(.sidebar-expanded-mobile) .context-header{height:60px;width:50px}.nav-sidebar:not(.sidebar-expanded-mobile) .context-header a{padding:10px 4px}.nav-sidebar:not(.sidebar-expanded-mobile) .sidebar-top-level-items>li .sidebar-sub-level-items:not(.flyout-list){display:none}.nav-sidebar:not(.sidebar-expanded-mobile) .nav-icon-container{margin-right:0}.nav-sidebar:not(.sidebar-expanded-mobile) .toggle-sidebar-button{padding:16px;width:49px}.nav-sidebar:not(.sidebar-expanded-mobile) .toggle-sidebar-button .collapse-text,.nav-sidebar:not(.sidebar-expanded-mobile) .toggle-sidebar-button .icon-chevron-double-lg-left{display:none}.nav-sidebar:not(.sidebar-expanded-mobile) .toggle-sidebar-button .icon-chevron-double-lg-right{display:block;margin:0}}.nav-sidebar-inner-scroll{height:100%;width:100%;overflow:auto}.sidebar-sub-level-items{display:none;padding-bottom:8px}.sidebar-sub-level-items>li a{padding:8px 16px 8px 40px}.sidebar-top-level-items{margin-bottom:60px}@media (min-width: 576px){.sidebar-top-level-items>li>a{margin-right:1px}}.sidebar-top-level-items>li .badge.badge-pill{background-color:rgba(0,0,0,0.08);color:#666}.sidebar-top-level-items>li.active{background:rgba(0,0,0,0.04)}.sidebar-top-level-items>li.active>a{margin-left:4px;padding-left:12px}.sidebar-top-level-items>li.active .badge.badge-pill{font-weight:600}.sidebar-top-level-items>li.active .sidebar-sub-level-items:not(.is-fly-out-only){display:block}.toggle-sidebar-button,.close-nav-button{width:219px;position:fixed;height:48px;bottom:0;padding:0 16px;background-color:#fafafa;border:0;border-top:1px solid #dbdbdb;color:#666;display:flex;align-items:center}.toggle-sidebar-button svg,.close-nav-button svg{margin-right:8px}.toggle-sidebar-button .icon-chevron-double-lg-right,.close-nav-button .icon-chevron-double-lg-right{display:none}.collapse-text{white-space:nowrap;overflow:hidden}.sidebar-collapsed-desktop .context-header{height:60px;width:50px}.sidebar-collapsed-desktop .context-header a{padding:10px 4px}.sidebar-collapsed-desktop .sidebar-top-level-items>li .sidebar-sub-level-items:not(.flyout-list){display:none}.sidebar-collapsed-desktop .nav-icon-container{margin-right:0}.sidebar-collapsed-desktop .toggle-sidebar-button{padding:16px;width:49px}.sidebar-collapsed-desktop .toggle-sidebar-button .collapse-text,.sidebar-collapsed-desktop .toggle-sidebar-button .icon-chevron-double-lg-left{display:none}.sidebar-collapsed-desktop .toggle-sidebar-button .icon-chevron-double-lg-right{display:block;margin:0}.fly-out-top-item>a{display:flex}.fly-out-top-item .fly-out-badge{margin-left:8px}.fly-out-top-item-name{flex:1}.close-nav-button{display:none}@media (max-width: 767.98px){.close-nav-button{display:flex}.toggle-sidebar-button{display:none}}table.table{margin-bottom:16px}table.table .dropdown-menu a{text-decoration:none}table.table .success,table.table .info{color:#fff}table.table .success a:not(.btn),table.table .info a:not(.btn){text-decoration:underline;color:#fff}pre{font-family:"Menlo", "DejaVu Sans Mono", "Liberation Mono", "Consolas", "Ubuntu Mono", "Courier New", "andale mono", "lucida console", monospace;display:block;padding:8px 12px;margin:0 0 8px;font-size:13px;word-break:break-all;word-wrap:break-word;color:#303030;background-color:#fafafa;border:1px solid #dbdbdb;border-radius:2px}.monospace{font-family:"Menlo", "DejaVu Sans Mono", "Liberation Mono", "Consolas", "Ubuntu Mono", "Courier New", "andale mono", "lucida console", monospace}input::-moz-placeholder,textarea::-moz-placeholder{color:#868686;opacity:1}input::-ms-input-placeholder,textarea::-ms-input-placeholder{color:#868686}input:-ms-input-placeholder,textarea:-ms-input-placeholder{color:#868686}svg{fill:currentColor}svg.s12{width:12px;height:12px}svg.s16{width:16px;height:16px}svg.s18{width:18px;height:18px}svg.s12{vertical-align:-1px}svg.s16{vertical-align:-3px}.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0, 0, 0, 0);border:0}table.code{width:100%;font-family:"Menlo", "DejaVu Sans Mono", "Liberation Mono", "Consolas", "Ubuntu Mono", "Courier New", "andale mono", "lucida console", monospace;border:0;border-collapse:separate;margin:0;padding:0;table-layout:fixed;border-radius:0 0 4px 4px}.frame .badge.badge-pill{position:absolute;background-color:#428fdc;color:#fff;border:#fff 1px solid;min-height:16px;padding:5px 8px;border-radius:12px}.frame .badge.badge-pill{transform:translate(-50%, -50%)}.color-label{padding:0 0.5rem;line-height:16px;border-radius:100px;color:#fff}.label-link{display:inline-flex;vertical-align:text-bottom}.milestones{padding:8px;margin-top:8px;border-radius:4px;background-color:#dbdbdb}.search{margin:0 8px}.search form{margin:0;padding:4px;width:200px;line-height:24px;height:32px;border:0;border-radius:4px}@media (min-width: 1200px){.search form{width:320px}}.search .search-input{border:0;font-size:14px;padding:0 20px 0 0;margin-left:5px;line-height:25px;width:98%;color:#fff;background:none}.search .search-input-container{display:flex;position:relative}.search .search-input-wrap{width:100%}.search .search-input-wrap .search-icon,.search .search-input-wrap .clear-icon{position:absolute;right:5px;top:4px}.search .search-input-wrap .search-icon{-moz-user-select:none;-webkit-user-select:none;-ms-user-select:none;user-select:none}.search .search-input-wrap .clear-icon{display:none}.search .search-input-wrap .dropdown{position:static}.search .search-input-wrap .dropdown-menu{left:-5px;max-height:400px;overflow:auto}@media (min-width: 1200px){.search .search-input-wrap .dropdown-menu{width:320px}}.search .search-input-wrap .dropdown-content{max-height:382px}.settings{border-top:1px solid #dbdbdb}.settings:first-of-type{margin-top:10px;border:0}.settings+div .settings:first-of-type{margin-top:0;border-top:1px solid #dbdbdb}.avatar,.avatar-container{float:left;margin-right:16px;border-radius:50%;border:1px solid #f5f5f5}.s16.avatar,.s16.avatar-container{width:16px;height:16px;margin-right:8px}.s18.avatar,.s18.avatar-container{width:18px;height:18px;margin-right:8px}.s40.avatar,.s40.avatar-container{width:40px;height:40px;margin-right:8px}.avatar{transition-property:none;width:40px;height:40px;padding:0;background:#fdfdfd;overflow:hidden;border-color:rgba(0,0,0,0.1)}.avatar.center{font-size:14px;line-height:1.8em;text-align:center}.avatar.avatar-tile{border-radius:0;border:0}.avatar-container{overflow:hidden;display:flex}.avatar-container a{width:100%;height:100%;display:flex;text-decoration:none}.avatar-container .avatar{border-radius:0;border:0;height:auto;width:100%;margin:0;align-self:center}.avatar-container.s40{min-width:40px;min-height:40px}.rect-avatar{border-radius:2px}.rect-avatar.s16{border-radius:2px}.rect-avatar.s18{border-radius:2px}.rect-avatar.s40{border-radius:4px}.tab-width-8{-moz-tab-size:8;tab-size:8}.gl-sr-only{border:0;clip:rect(0, 0, 0, 0);height:1px;margin:-1px;overflow:hidden;padding:0;position:absolute;white-space:nowrap;width:1px}.gl-ml-3{margin-left:0.5rem}.content-wrapper>.alert-wrapper,#content-body,.modal-dialog{display:block}.content-wrapper>.alert-wrapper,#content-body,.modal-dialog{display:none}

</style>

<link rel="stylesheet" media="print" href="/assets/application-2cb8d6d6d17f1b1b8492581de92356755b864cbb6e48347a65baa2771a10ae4f.css" />

<link rel="stylesheet" media="print" href="/assets/application_utilities-347ed6255ee2886ac1af88a725fccf5a9211e7a193e52c747967e31ccfd7427c.css" />


<link rel="stylesheet" media="print" href="/assets/highlight/themes/white-23255bab077a3cc8d17b4b7004aa866e340b0009c7897b509b5d0086710b698f.css" />
<script>
//<![CDATA[
document.querySelectorAll('link[media="print"]').forEach(linkTag => {
  linkTag.setAttribute('data-startupcss', 'loading');
  const startupLinkLoadedEvent = new CustomEvent('CSSStartupLinkLoaded');
  linkTag.addEventListener('load',function(){this.media='all';this.setAttribute('data-startupcss', 'loaded');document.dispatchEvent(startupLinkLoadedEvent);},{once: true});
})

//]]>
</script>


<script>
//<![CDATA[
window.gon={};gon.features={"refactorBlobViewer":false};
//]]>
</script>




<script src="/assets/webpack/runtime.dcb36a00.bundle.js" defer="defer"></script>
<script src="/assets/webpack/main.d5b0c547.chunk.js" defer="defer"></script>
<script src="/assets/webpack/graphql.0a3cd4b9.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-pages.admin-pages.admin.abuse_reports-pages.admin.application_settings-pages.admin.applicati-d39c1ef8.f2888661.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-globalSearch-pages.admin.abuse_reports-pages.admin.groups.show-pages.admin.projects-pages.ad-788b4c23.9a46f5e0.chunk.js" defer="defer"></script>
<script src="/assets/webpack/shortcutsBundle.8a6706c0.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-pages.groups.boards-pages.groups.details-pages.groups.show-pages.projects-pages.projects.act-502b3622.351a82ca.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-pages.groups.milestones.edit-pages.groups.milestones.new-pages.projects.blame.show-pages.pro-77e8c306.bd3afbe1.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-pages.projects.blame.show-pages.projects.blob.edit-pages.projects.blob.new-pages.projects.bl-c6edf1dd.a58ff68b.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-pages.projects.blob.show-pages.projects.show-pages.projects.snippets.show-pages.projects.tre-c684fcf6.e288dcb7.chunk.js" defer="defer"></script>
<script src="/assets/webpack/commons-pages.projects.blob.show-pages.projects.show-pages.projects.tree.show.83922491.chunk.js" defer="defer"></script>
<script src="/assets/webpack/pages.projects.blob.show.82f9c0d4.chunk.js" defer="defer"></script>
<script>
//<![CDATA[
window.uploads_path = "/lbd/data-science/uploads";



//]]>
</script>
<meta name="csrf-param" content="authenticity_token" />
<meta name="csrf-token" content="oOwXM47Lsgc+qH5STnY53RuL6F5nV7mSfAIGJ2koCoM1vYyjHiUcOtkNlX9Uimq4eUhoMr7wqEtKE+SIb4PHpw==" />
<meta name="csp-nonce" />
<meta name="action-cable-url" content="/-/cable" />
<meta content="width=device-width, initial-scale=1, maximum-scale=1" name="viewport">
<meta content="#474D57" name="theme-color">
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-5a9cee0e8a51212e70b90c87c12f382c428870c0ff67d1eb034d884b78d2dae7.png" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-a6eec6aeb9da138e507593b464fdac213047e49d3093fc30e90d9a995df83ba3.png" sizes="76x76" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-iphone-retina-72e2aadf86513a56e050e7f0f2355deaa19cc17ed97bbe5147847f2748e5a3e3.png" sizes="120x120" />
<link rel="apple-touch-icon" type="image/x-icon" href="/assets/touch-icon-ipad-retina-8ebe416f5313483d9c1bc772b5bbe03ecad52a54eba443e5215a22caed2a16a2.png" sizes="152x152" />
<link color="rgb(226, 67, 41)" href="/assets/logo-d36b5212042cebc89b96df4bf6ac24e43db316143e89926c0db839ff694d2de4.svg" rel="mask-icon">
<link href="/search/opensearch.xml" rel="search" title="Search GitLab" type="application/opensearchdescription+xml">
<meta content="/assets/msapplication-tile-1196ec67452f618d39cdd85e2e3a542f76574c071051ae7effbfde01710eb17d.png" name="msapplication-TileImage">
<meta content="#30353E" name="msapplication-TileColor">




</head>

<body class="ui-dark tab-width-8  gl-browser-firefox gl-platform-windows" data-find-file="/lbd/data-science/-/find_file/master" data-group="lbd" data-namespace-id="388" data-page="projects:blob:show" data-page-type-id="master/API RAD-on/readme.md" data-project="data-science" data-project-id="429">

<script>
//<![CDATA[
gl = window.gl || {};
gl.client = {"isFirefox":true,"isWindows":true};


//]]>
</script>


<header class="navbar navbar-gitlab navbar-expand-sm js-navbar" data-qa-selector="navbar">
<a class="gl-sr-only gl-accessibility" href="#content-body">Skip to content</a>
<div class="container-fluid">
<div class="header-content">
<div class="title-container">
<h1 class="title">
<span class="gl-sr-only">GitLab</span>
<a title="Dashboard" id="logo" href="/"><svg width="24" height="24" class="tanuki-logo" viewBox="0 0 36 36">
  <path class="tanuki-shape tanuki-left-ear" fill="#e24329" d="M2 14l9.38 9v-9l-4-12.28c-.205-.632-1.176-.632-1.38 0z"/>
  <path class="tanuki-shape tanuki-right-ear" fill="#e24329" d="M34 14l-9.38 9v-9l4-12.28c.205-.632 1.176-.632 1.38 0z"/>
  <path class="tanuki-shape tanuki-nose" fill="#e24329" d="M18,34.38 3,14 33,14 Z"/>
  <path class="tanuki-shape tanuki-left-eye" fill="#fc6d26" d="M18,34.38 11.38,14 2,14 6,25Z"/>
  <path class="tanuki-shape tanuki-right-eye" fill="#fc6d26" d="M18,34.38 24.62,14 34,14 30,25Z"/>
  <path class="tanuki-shape tanuki-left-cheek" fill="#fca326" d="M2 14L.1 20.16c-.18.565 0 1.2.5 1.56l17.42 12.66z"/>
  <path class="tanuki-shape tanuki-right-cheek" fill="#fca326" d="M34 14l1.9 6.16c.18.565 0 1.2-.5 1.56L18 34.38z"/>
</svg>

<span class="logo-text d-none d-lg-block gl-ml-3">
<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 617 169"><path d="M315.26 2.97h-21.8l.1 162.5h88.3v-20.1h-66.5l-.1-142.4M465.89 136.95c-5.5 5.7-14.6 11.4-27 11.4-16.6 0-23.3-8.2-23.3-18.9 0-16.1 11.2-23.8 35-23.8 4.5 0 11.7.5 15.4 1.2v30.1h-.1m-22.6-98.5c-17.6 0-33.8 6.2-46.4 16.7l7.7 13.4c8.9-5.2 19.8-10.4 35.5-10.4 17.9 0 25.8 9.2 25.8 24.6v7.9c-3.5-.7-10.7-1.2-15.1-1.2-38.2 0-57.6 13.4-57.6 41.4 0 25.1 15.4 37.7 38.7 37.7 15.7 0 30.8-7.2 36-18.9l4 15.9h15.4v-83.2c-.1-26.3-11.5-43.9-44-43.9M557.63 149.1c-8.2 0-15.4-1-20.8-3.5V70.5c7.4-6.2 16.6-10.7 28.3-10.7 21.1 0 29.2 14.9 29.2 39 0 34.2-13.1 50.3-36.7 50.3m9.2-110.6c-19.5 0-30 13.3-30 13.3v-21l-.1-27.8h-21.3l.1 158.5c10.7 4.5 25.3 6.9 41.2 6.9 40.7 0 60.3-26 60.3-70.9-.1-35.5-18.2-59-50.2-59M77.9 20.6c19.3 0 31.8 6.4 39.9 12.9l9.4-16.3C114.5 6 97.3 0 78.9 0 32.5 0 0 28.3 0 85.4c0 59.8 35.1 83.1 75.2 83.1 20.1 0 37.2-4.7 48.4-9.4l-.5-63.9V75.1H63.6v20.1h38l.5 48.5c-5 2.5-13.6 4.5-25.3 4.5-32.2 0-53.8-20.3-53.8-63-.1-43.5 22.2-64.6 54.9-64.6M231.43 2.95h-21.3l.1 27.3v94.3c0 26.3 11.4 43.9 43.9 43.9 4.5 0 8.9-.4 13.1-1.2v-19.1c-3.1.5-6.4.7-9.9.7-17.9 0-25.8-9.2-25.8-24.6v-65h35.7v-17.8h-35.7l-.1-38.5M155.96 165.47h21.3v-124h-21.3v124M155.96 24.37h21.3V3.07h-21.3v21.3"/></svg>

</span>
</a></h1>
<ul class="list-unstyled navbar-sub-nav">
<li id="nav-projects-dropdown" class="home dropdown header-projects qa-projects-dropdown" data-track-label="projects_dropdown" data-track-event="click_dropdown" data-track-experiment="new_repo"><button data-toggle="dropdown" type="button">
Projects
<svg class="s16 caret-down" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</button>
<div class="dropdown-menu frequent-items-dropdown-menu">
<div class="frequent-items-dropdown-container with-deprecated-styles">
<div class="frequent-items-dropdown-sidebar qa-projects-dropdown-sidebar">
<ul>
<li class=""><a class="qa-your-projects-link" data-track-label="projects_dropdown_your_projects" data-track-event="click_link" href="/dashboard/projects">Your projects
</a></li><li class=""><a data-track-label="projects_dropdown_starred_projects" data-track-event="click_link" href="/dashboard/projects/starred">Starred projects
</a></li><li class=""><a data-track-label="projects_dropdown_explore_projects" data-track-event="click_link" href="/explore">Explore projects
</a></li><li class="gl-border-0 gl-border-t-1 gl-border-solid gl-border-gray-100"><a data-track-label="projects_dropdown_blank_project" data-track-event="click_link" data-track-experiment="new_repo" href="/projects/new#blank_project">Create blank project
</a></li><li class=""><a data-track-label="projects_dropdown_import_project" data-track-event="click_link" data-track-experiment="new_repo" href="/projects/new#import_project">Import project
</a></li><li class=""><a data-track-label="projects_dropdown_create_from_template" data-track-event="click_link" href="/projects/new#create_from_template">Create from template
</a></li></ul>
</div>
<div class="frequent-items-dropdown-content">
<div data-project-id="429" data-project-name="data science" data-project-namespace="LBD / data science" data-project-web-url="/lbd/data-science" data-user-name="kpyrtek" id="js-projects-dropdown"></div>
</div>
</div>

</div>
</li><li id="nav-groups-dropdown" class="d-none d-md-block home dropdown header-groups qa-groups-dropdown" data-track-label="groups_dropdown" data-track-event="click_dropdown"><button data-toggle="dropdown" type="button">
Groups
<svg class="s16 caret-down" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</button>
<div class="dropdown-menu frequent-items-dropdown-menu">
<div class="frequent-items-dropdown-container with-deprecated-styles">
<div class="frequent-items-dropdown-sidebar qa-groups-dropdown-sidebar">
<ul>
<li class=""><a class="qa-your-groups-link" data-track-label="groups_dropdown_your_groups" data-track-event="click_link" href="/dashboard/groups">Your groups
</a></li><li class=""><a data-track-label="groups_dropdown_explore_groups" data-track-event="click_link" href="/explore/groups">Explore groups
</a></li><li class="gl-border-0 gl-border-t-1 gl-border-solid gl-border-gray-100"><a data-track-label="groups_dropdown_create_group" data-track-event="click_link" data-qa-selector="create_group_link" href="/groups/new#create-group-pane">Create group
</a></li><li class=""><a data-track-label="groups_dropdown_import_group" data-track-event="click_link" data-qa-selector="import_group_link" href="/groups/new#import-group-pane">Import group
</a></li></ul>
</div>
<div class="frequent-items-dropdown-content">
<div data-user-name="kpyrtek" id="js-groups-dropdown"></div>
</div>
</div>

</div>
</li><li id="nav-more-dropdown" class="header-more dropdown" data-track-label="more_dropdown" data-track-event="click_more_link"><a data-qa-selector="more_dropdown" data-toggle="dropdown" href="#">
More
<svg class="s16 caret-down" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</a>
<div class="dropdown-menu">
<ul>
<li class="d-md-none">
<a class="dashboard-shortcuts-groups" data-qa-selector="groups_link" href="/dashboard/groups">Groups
</a></li>
<li class=""><a class="dashboard-shortcuts-activity" data-qa-selector="activity_link" href="/dashboard/activity">Activity
</a></li><li class=""><a class="dashboard-shortcuts-milestones" data-qa-selector="milestones_link" href="/dashboard/milestones">Milestones
</a></li><li class=""><a class="dashboard-shortcuts-snippets" data-qa-selector="snippets_link" href="/dashboard/snippets">Snippets
</a></li><li class="dropdown">

</li>
</ul>
</div>
</li><li class="hidden">
<a class="dashboard-shortcuts-projects" href="/dashboard/projects">Projects
</a></li>

</ul>

</div>
<div class="navbar-collapse collapse">
<ul class="nav navbar-nav">
<li class="header-new dropdown" data-track-event="click_dropdown" data-track-experiment="new_repo" data-track-label="new_dropdown">
<a class="header-new-dropdown-toggle has-tooltip qa-new-menu-toggle" id="js-onboarding-new-project-link" title="New..." ref="tooltip" aria-label="New..." data-toggle="dropdown" data-placement="bottom" data-container="body" data-display="static" href="/projects/new"><svg class="s16" data-testid="plus-square-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#plus-square"></use></svg>
<svg class="s16 caret-down" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right dropdown-extended-height">
<ul>
<li class="dropdown-bold-header">
This project
</li>
<li><a data-track-event="click_link_new_mr" data-track-label="plus_menu_dropdown" href="/lbd/data-science/-/merge_requests/new">New merge request</a></li>
<li><a data-track-event="click_link_new_snippet_project" data-track-label="plus_menu_dropdown" href="/lbd/data-science/-/snippets/new">New snippet</a></li>

<li class="divider"></li>
<li class="dropdown-bold-header">GitLab</li>
<li><a class="qa-global-new-project-link" data-track-experiment="new_repo" data-track-event="click_link_new_project" data-track-label="plus_menu_dropdown" href="/projects/new">New project
</a></li>
<li><a data-track-event="click_link_new_group" data-track-label="plus_menu_dropdown" href="/groups/new">New group</a></li>
<li><a data-track-event="click_link_new_snippet_parent" data-track-label="plus_menu_dropdown" class="qa-global-new-snippet-link" href="/-/snippets/new">New snippet</a></li>
</ul>
</div>
</li>

<li class="nav-item d-none d-lg-block m-auto">
<div class="search search-form" data-track-event="activate_form_input" data-track-label="navbar_search" data-track-value="">
<form class="form-inline" action="/search" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><div class="search-input-container">
<div class="search-input-wrap">
<div class="dropdown" data-url="/search/autocomplete">
<input type="search" name="search" id="search" placeholder="Search or jump to…" class="search-input dropdown-menu-toggle no-outline js-search-dashboard-options" spellcheck="false" autocomplete="off" data-issues-path="/dashboard/issues" data-mr-path="/dashboard/merge_requests" data-qa-selector="search_term_field" aria-label="Search or jump to…" />
<button class="hidden js-dropdown-search-toggle" data-toggle="dropdown" type="button"></button>
<div class="dropdown-menu dropdown-select" data-testid="dashboard-search-options">
<div class="dropdown-content"><ul>
<li class="dropdown-menu-empty-item">
<a>
Loading...
</a>
</li>
</ul>
</div><div class="dropdown-loading"><div class="gl-spinner-container"><span class="gl-spinner gl-spinner-orange gl-spinner-md gl-mt-7" aria-label="Loading"></span></div></div>
</div>
<svg class="s16 search-icon" data-testid="search-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#search"></use></svg>
<svg class="s16 clear-icon js-clear-input" data-testid="close-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#close"></use></svg>
</div>
</div>
</div>
<input type="hidden" name="group_id" id="group_id" value="388" class="js-search-group-options" data-group-path="lbd" data-name="LBD" data-issues-path="/groups/lbd/-/issues" data-mr-path="/groups/lbd/-/merge_requests" />
<input type="hidden" name="project_id" id="search_project_id" value="429" class="js-search-project-options" data-project-path="data-science" data-name="data science" data-issues-path="/lbd/data-science/-/issues" data-mr-path="/lbd/data-science/-/merge_requests" data-issues-disabled="true" />
<input type="hidden" name="scope" id="scope" />
<input type="hidden" name="search_code" id="search_code" value="true" />
<input type="hidden" name="snippets" id="snippets" value="false" />
<input type="hidden" name="repository_ref" id="repository_ref" value="master" />
<input type="hidden" name="nav_source" id="nav_source" value="navbar" />
<div class="search-autocomplete-opts hide" data-autocomplete-path="/search/autocomplete" data-autocomplete-project-id="429" data-autocomplete-project-ref="master"></div>
</form></div>

</li>
<li class="nav-item d-inline-block d-lg-none">
<a title="Search" aria-label="Search" data-toggle="tooltip" data-placement="bottom" data-container="body" href="/search?project_id=429"><svg class="s16" data-testid="search-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#search"></use></svg>
</a></li>
<li class="user-counter"><a title="Issues" class="dashboard-shortcuts-issues" aria-label="Issues" data-qa-selector="issues_shortcut_button" data-toggle="tooltip" data-placement="bottom" data-track-label="main_navigation" data-track-event="click_issues_link" data-track-property="navigation" data-container="body" href="/dashboard/issues?assignee_username=kpyrtek"><svg class="s16" data-testid="issues-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#issues"></use></svg>
<span class="badge badge-pill issues-count green-badge hidden">
0
</span>
</a></li><li class="user-counter dropdown"><a class="dashboard-shortcuts-merge_requests" title="Merge requests" aria-label="Merge requests" data-qa-selector="merge_requests_shortcut_button" data-toggle="dropdown" data-placement="bottom" data-track-label="main_navigation" data-track-event="click_merge_link" data-track-property="navigation" data-container="body" href="/dashboard/merge_requests?assignee_username=kpyrtek"><svg class="s16" data-testid="git-merge-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#git-merge"></use></svg>
<span class="badge badge-pill merge-requests-count js-merge-requests-count hidden">
0
</span>
<svg class="s16 caret-down gl-mx-0!" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right">
<ul>
<li class="dropdown-header">
Merge requests
</li>
<li>
<a class="gl-display-flex! gl-align-items-center" href="/dashboard/merge_requests?assignee_username=kpyrtek">Assigned to you
<span class="badge gl-badge badge-pill badge-muted merge-request-badge gl-ml-auto js-assigned-mr-count">
0
</span>
</a></li>
<li>
<a class="gl-display-flex! gl-align-items-center" href="/dashboard/merge_requests?reviewer_username=kpyrtek">Review requests for you
<span class="badge gl-badge badge-pill badge-muted merge-request-badge gl-ml-auto js-reviewer-mr-count">
0
</span>
</a></li>
</ul>
</div>
</li><li class="user-counter"><a title="To-Do List" aria-label="To-Do List" class="shortcuts-todos" data-qa-selector="todos_shortcut_button" data-toggle="tooltip" data-placement="bottom" data-track-label="main_navigation" data-track-event="click_to_do_link" data-track-property="navigation" data-container="body" href="/dashboard/todos"><svg class="s16" data-testid="todo-done-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#todo-done"></use></svg>
<span class="badge badge-pill todos-count js-todos-count hidden">
0
</span>
</a></li><li class="nav-item header-help dropdown d-none d-md-block">
<a class="header-help-dropdown-toggle" data-toggle="dropdown" href="/help"><span class="gl-sr-only">
Help
</span>
<svg class="s16" data-testid="question-o-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#question-o"></use></svg>
<span class="notification-dot rounded-circle gl-absolute"></span>
<svg class="s16 caret-down" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right">
<ul>
<li>
<button class="gl-justify-content-space-between gl-align-items-center js-whats-new-trigger gl-display-flex!" type="button">
What&#39;s new
<span class="js-whats-new-notification-count gl-badge badge sm badge-dark badge-pill">
10
</span>
</button>
</li>

<li>
<a href="/help">Help</a>
</li>
<li>
<a href="https://about.gitlab.com/getting-help/">Support</a>
</li>
<li>
<a target="_blank" class="text-nowrap" rel="noopener noreferrer" data-track-event="click_forum" data-track-property="question_menu" href="https://forum.gitlab.com/">Community forum</a>

</li>
<li>
<button class="js-shortcuts-modal-trigger" type="button">
Keyboard shortcuts
<span aria-hidden class="text-secondary float-right">?</span>
</button>
</li>
<li class="divider"></li>
<li>
<a href="https://about.gitlab.com/submit-feedback">Submit feedback</a>
</li>
<li>
<a target="_blank" class="text-nowrap" href="https://about.gitlab.com/contributing">Contribute to GitLab
</a>
</li>

</ul>

</div>
</li>
<li class="nav-item header-user js-nav-user-dropdown dropdown" data-qa-selector="user_menu" data-track-event="click_dropdown" data-track-label="profile_dropdown" data-track-value="">
<a class="header-user-dropdown-toggle" data-toggle="dropdown" href="/kpyrtek"><img width="23" height="23" class="header-user-avatar qa-user-avatar lazy" alt="Katarzyna Pyrtek" data-src="/assets/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==" />

<svg class="s16 caret-down" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg>
</a><div class="dropdown-menu dropdown-menu-right">
<ul>
<li class="current-user">
<a class="gl-line-height-20!" data-user="kpyrtek" data-testid="user-profile-link" data-qa-selector="user_profile_link" href="/kpyrtek"><div class="gl-font-weight-bold">
Katarzyna Pyrtek
</div>
@kpyrtek

</a></li>
<li class="divider"></li>
<li>
<button class="gl-button btn btn-link menu-item js-set-status-modal-trigger" type="button">
Set status
</button>
</li>
<li>
<a data-qa-selector="edit_profile_link" href="/-/profile">Edit profile</a>
</li>
<li>
<a href="/-/profile/preferences">Preferences</a>
</li>


<li class="divider d-md-none"></li>
<li class="d-md-none">
<a href="/help">Help</a>
</li>
<li class="d-md-none">
<a href="https://about.gitlab.com/getting-help/">Support</a>
</li>
<li class="d-md-none">
<a target="_blank" class="text-nowrap" rel="noopener noreferrer" data-track-event="click_forum" data-track-property="question_menu" href="https://forum.gitlab.com/">Community forum</a>

</li>
<li class="d-md-none">
<a href="https://about.gitlab.com/submit-feedback">Submit feedback</a>
</li>
<li class="d-md-none">
<a target="_blank" class="text-nowrap" href="https://about.gitlab.com/contributing">Contribute to GitLab
</a>
</li>

<li class="divider"></li>
<li>
<a class="sign-out-link" data-qa-selector="sign_out_link" rel="nofollow" data-method="post" href="/users/sign_out">Sign out</a>
</li>
</ul>

</div>
</li>
</ul>
</div>
<button class="navbar-toggler d-block d-sm-none" type="button">
<span class="sr-only">Toggle navigation</span>
<svg class="s12 more-icon js-navbar-toggle-right" data-testid="ellipsis_h-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#ellipsis_h"></use></svg>
<svg class="s12 close-icon js-navbar-toggle-left" data-testid="close-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#close"></use></svg>
</button>
</div>
</div>
</header>
<div data-version-digest="4128f3e88e472d96e13a2a072a164aa1b1af6accc4efebf979025e310d1e1f4a" id="whats-new-app"></div>
<div class="js-set-status-modal-wrapper" data-current-emoji="" data-current-message="" data-default-emoji="speech_balloon"></div>

<div class="layout-page page-with-contextual-sidebar">
<aside aria-label="Project navigation" class="nav-sidebar">
<div class="nav-sidebar-inner-scroll">
<div class="context-header">
<a aria-label="data science" href="/lbd/data-science"><span class="avatar-container rect-avatar s40 project-avatar">
<span class="avatar s40 avatar-tile identicon bg3">D</span>
</span>
<span class="sidebar-context-title">
data science
</span>
</a></div>

<ul class="sidebar-top-level-items qa-project-sidebar">
<li class="home"><a aria-label="Project overview" class="shortcuts-project rspec-project-link" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Project overview" href="/lbd/data-science"><span class="nav-icon-container">
<svg class="s16" data-testid="home-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#home"></use></svg>
</span>
<span class="nav-item-name">
Project overview
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a aria-label="Project overview" href="/lbd/data-science"><strong class="fly-out-top-item-name">
Project overview
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a aria-label="Project details" class="shortcuts-project" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Details" href="/lbd/data-science"><span>
Details
</span>
</a></li><li class=""><a aria-label="Activity" class="shortcuts-project-activity" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Activity" href="/lbd/data-science/activity"><span>
Activity
</span>
</a></li><li class=""><a aria-label="Releases" class="shortcuts-project-releases" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Releases" href="/lbd/data-science/-/releases"><span>
Releases
</span>
</a></li>
</ul>
</li><li class="active"><a aria-label="Repository" class="shortcuts-tree" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Repository" href="/lbd/data-science/-/tree/master"><span class="nav-icon-container">
<svg class="s16" data-testid="doc-text-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#doc-text"></use></svg>
</span>
<span class="nav-item-name" id="js-onboarding-repo-link">
Repository
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item active"><a aria-label="Repository" href="/lbd/data-science/-/tree/master"><strong class="fly-out-top-item-name">
Repository
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class="active"><a aria-label="Files" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Files" href="/lbd/data-science/-/tree/master"><span>
Files
</span>
</a></li><li class=""><a aria-label="Commits" id="js-onboarding-commits-link" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Commits" href="/lbd/data-science/-/commits/master"><span>
Commits
</span>
</a></li><li class=""><a aria-label="Branches" id="js-onboarding-branches-link" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Branches" href="/lbd/data-science/-/branches"><span>
Branches
</span>
</a></li><li class=""><a aria-label="Tags" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Tags" href="/lbd/data-science/-/tags"><span>
Tags
</span>
</a></li><li class=""><a aria-label="Contributors" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Contributors" href="/lbd/data-science/-/graphs/master"><span>
Contributors
</span>
</a></li><li class=""><a aria-label="Graph" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Graph" href="/lbd/data-science/-/network/master"><span>
Graph
</span>
</a></li><li class=""><a aria-label="Compare" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Compare" href="/lbd/data-science/-/compare?from=master&amp;to=master"><span>
Compare
</span>
</a></li>
</ul>
</li><li class=""><a aria-label="Labels" class="shortcuts-labels" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Labels" href="/lbd/data-science/-/labels"><span class="nav-icon-container">
<svg class="s16" data-testid="label-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#label"></use></svg>
</span>
<span class="nav-item-name" id="js-onboarding-labels-link">
Labels
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a aria-label="Labels" href="/lbd/data-science/-/labels"><strong class="fly-out-top-item-name">
Labels
</strong>
</a></li></ul>
</li><li class=""><a aria-label="Merge requests" class="shortcuts-merge_requests" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Merge requests" href="/lbd/data-science/-/merge_requests"><span class="nav-icon-container">
<svg class="s16" data-testid="git-merge-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#git-merge"></use></svg>
</span>
<span class="nav-item-name" id="js-onboarding-mr-link">
Merge requests
</span>
<span class="badge badge-pill count merge_counter js-merge-counter">
3
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a aria-label="Merge requests" href="/lbd/data-science/-/merge_requests"><strong class="fly-out-top-item-name">
Merge requests
</strong>
<span class="badge badge-pill count fly-out-badge merge_counter js-merge-counter">
3
</span>
</a></li></ul>
</li><li class=""><a aria-label="Security &amp; Compliance" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Security &amp; Compliance" href="/lbd/data-science/-/security/configuration"><span class="nav-icon-container">
<svg class="s16" data-testid="shield-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#shield"></use></svg>
</span>
<span class="nav-item-name">
Security &amp; Compliance
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a aria-label="Security &amp; Compliance" href="/lbd/data-science/-/security/configuration"><strong class="fly-out-top-item-name">
Security &amp; Compliance
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a aria-label="Configuration" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Configuration" href="/lbd/data-science/-/security/configuration"><span>
Configuration
</span>
</a></li>
</ul>
</li><li class=""><a aria-label="Operations" class="shortcuts-operations" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Operations" href="/lbd/data-science/-/feature_flags"><span class="nav-icon-container">
<svg class="s16" data-testid="cloud-gear-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#cloud-gear"></use></svg>
</span>
<span class="nav-item-name">
Operations
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a aria-label="Operations" href="/lbd/data-science/-/feature_flags"><strong class="fly-out-top-item-name">
Operations
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a aria-label="Metrics" class="shortcuts-metrics" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Metrics" href="/lbd/data-science/-/metrics"><span>
Metrics
</span>
</a></li><li class=""><a aria-label="Error Tracking" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Error Tracking" href="/lbd/data-science/-/error_tracking"><span>
Error Tracking
</span>
</a></li><li class=""><a aria-label="Alerts" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Alerts" href="/lbd/data-science/-/alert_management"><span>
Alerts
</span>
</a></li><li class=""><a aria-label="Terraform" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Terraform" href="/lbd/data-science/-/terraform"><span>
Terraform
</span>
</a></li><li class=""><a aria-label="Feature Flags" class="shortcuts-feature-flags" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Feature Flags" href="/lbd/data-science/-/feature_flags"><span>
Feature Flags
</span>
</a></li>
</ul>
</li><li class=""><a aria-label="Packages &amp; Registries" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Packages &amp; Registries" href="/lbd/data-science/-/packages"><span class="nav-icon-container">
<svg class="s16" data-testid="package-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#package"></use></svg>
</span>
<span class="nav-item-name">
Packages &amp; Registries
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a aria-label="Packages &amp; Registries" href="/lbd/data-science/-/packages"><strong class="fly-out-top-item-name">
Packages &amp; Registries
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a aria-label="Package Registry" class="shortcuts-container-registry" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Package Registry" href="/lbd/data-science/-/packages"><span>
Package Registry
</span>
</a></li>
</ul>
</li><li class=""><a aria-label="Analytics" class="shortcuts-analytics" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Analytics" href="/lbd/data-science/-/value_stream_analytics"><span class="nav-icon-container">
<svg class="s16" data-testid="chart-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chart"></use></svg>
</span>
<span class="nav-item-name">
Analytics
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a aria-label="Analytics" href="/lbd/data-science/-/value_stream_analytics"><strong class="fly-out-top-item-name">
Analytics
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a aria-label="Repository" class="shortcuts-repository-charts" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Repository" href="/lbd/data-science/-/graphs/master/charts"><span>
Repository
</span>
</a></li><li class=""><a aria-label="Value Stream" class="shortcuts-project-cycle-analytics" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Value Stream" href="/lbd/data-science/-/value_stream_analytics"><span>
Value Stream
</span>
</a></li>
</ul>
</li><li class=""><a aria-label="Wiki" class="shortcuts-wiki" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Wiki" href="/lbd/data-science/-/wikis/home"><span class="nav-icon-container">
<svg class="s16" data-testid="book-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#book"></use></svg>
</span>
<span class="nav-item-name">
Wiki
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a aria-label="Wiki" href="/lbd/data-science/-/wikis/home"><strong class="fly-out-top-item-name">
Wiki
</strong>
</a></li></ul>
</li><li class=""><a aria-label="Snippets" class="shortcuts-snippets" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Snippets" href="/lbd/data-science/-/snippets"><span class="nav-icon-container">
<svg class="s16" data-testid="snippet-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#snippet"></use></svg>
</span>
<span class="nav-item-name">
Snippets
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a aria-label="Snippets" href="/lbd/data-science/-/snippets"><strong class="fly-out-top-item-name">
Snippets
</strong>
</a></li></ul>
</li><li class=""><a aria-label="Members" id="js-onboarding-members-link" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Members" href="/lbd/data-science/-/project_members"><span class="nav-icon-container">
<svg class="s16" data-testid="users-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#users"></use></svg>
</span>
<span class="nav-item-name">
Members
</span>
</a><ul class="sidebar-sub-level-items is-fly-out-only">
<li class="fly-out-top-item"><a aria-label="Members" href="/lbd/data-science/-/project_members"><strong class="fly-out-top-item-name">
Members
</strong>
</a></li></ul>
</li><li class=""><a aria-label="Settings" data-qa-selector="sidebar_menu_link" data-qa-menu-item="Settings" href="/lbd/data-science/edit"><span class="nav-icon-container">
<svg class="s16" data-testid="settings-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#settings"></use></svg>
</span>
<span class="nav-item-name" id="js-onboarding-settings-link">
Settings
</span>
</a><ul class="sidebar-sub-level-items">
<li class="fly-out-top-item"><a aria-label="Settings" href="/lbd/data-science/edit"><strong class="fly-out-top-item-name">
Settings
</strong>
</a></li><li class="divider fly-out-top-item"></li>
<li class=""><a aria-label="General" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="General" href="/lbd/data-science/edit"><span>
General
</span>
</a></li><li class=""><a aria-label="Integrations" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Integrations" href="/lbd/data-science/-/settings/integrations"><span>
Integrations
</span>
</a></li><li class=""><a aria-label="Webhooks" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Webhooks" href="/lbd/data-science/-/hooks"><span>
Webhooks
</span>
</a></li><li class=""><a aria-label="Access Tokens" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Access Tokens" href="/lbd/data-science/-/settings/access_tokens"><span>
Access Tokens
</span>
</a></li><li class=""><a aria-label="Repository" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Repository" href="/lbd/data-science/-/settings/repository"><span>
Repository
</span>
</a></li><li class=""><a aria-label="Operations" data-qa-selector="sidebar_menu_item_link" data-qa-menu-item="Operations" href="/lbd/data-science/-/settings/operations"><span>
Operations
</span>
</a></li>
</ul>
</li>
<li class="hidden">
<a aria-label="Activity" class="shortcuts-project-activity" href="/lbd/data-science/activity">Activity
</a></li>
<li class="hidden">
<a aria-label="Graph" class="shortcuts-network" href="/lbd/data-science/-/network/master">Graph
</a></li>
<li class="hidden">
<a aria-label="Commits" class="shortcuts-commits" href="/lbd/data-science/-/commits/master">Commits
</a></li>

</ul>
<a class="toggle-sidebar-button js-toggle-sidebar qa-toggle-sidebar rspec-toggle-sidebar" role="button" title="Toggle sidebar" type="button">
<svg class="s16 icon-chevron-double-lg-left" data-testid="chevron-double-lg-left-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-double-lg-left"></use></svg>
<svg class="s16 icon-chevron-double-lg-right" data-testid="chevron-double-lg-right-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-double-lg-right"></use></svg>
<span class="collapse-text">Collapse sidebar</span>
</a>
<button name="button" type="button" class="close-nav-button"><svg class="s16" data-testid="close-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#close"></use></svg>
<span class="collapse-text">Close sidebar</span>
</button>
</div>
</aside>


<div class="content-wrapper">
<div class="mobile-overlay"></div>

<div class="alert-wrapper gl-force-block-formatting-context">
















<nav aria-label="Breadcrumbs" class="breadcrumbs container-fluid container-limited">
<div class="breadcrumbs-container">
<button name="button" type="button" class="toggle-mobile-nav"><span class="sr-only">Open sidebar</span>
<svg class="s18" data-testid="hamburger-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#hamburger"></use></svg>
</button><div class="breadcrumbs-links" data-qa-selector="breadcrumb_links_content" data-testid="breadcrumb-links">
<ul class="list-unstyled breadcrumbs-list js-breadcrumbs-list">
<li><a class="group-path breadcrumb-item-text js-breadcrumb-item-text " href="/lbd">LBD</a><svg class="s8 breadcrumbs-list-angle" data-testid="angle-right-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#angle-right"></use></svg></li> <li><a href="/lbd/data-science"><span class="breadcrumb-item-text js-breadcrumb-item-text">data science</span></a><svg class="s8 breadcrumbs-list-angle" data-testid="angle-right-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#angle-right"></use></svg></li>

<li>
<h2 class="breadcrumbs-sub-title">
<a href="/lbd/data-science/-/blob/master/API%20RAD-on/readme.md">Repository</a>
</h2>
</li>
</ul>
</div>
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"BreadcrumbList","itemListElement":[{"@type":"ListItem","position":1,"name":"LBD","item":"https://gitlab.opi.org.pl/lbd"},{"@type":"ListItem","position":2,"name":"data science","item":"https://gitlab.opi.org.pl/lbd/data-science"},{"@type":"ListItem","position":3,"name":"Repository","item":"https://gitlab.opi.org.pl/lbd/data-science/-/blob/master/API%20RAD-on/readme.md"}]}

</script>

</div>
</nav>

</div>
<div class="container-fluid container-limited ">
<main class="content" id="content-body" itemscope itemtype="http://schema.org/SoftwareSourceCode">
<div class="flash-container flash-container-page sticky" data-qa-selector="flash_container">
</div>


<div class="js-signature-container" data-signatures-path="/lbd/data-science/-/commits/318e36746fbf6f490c4bdc26fd644f631690b6c6/signatures?limit=1"></div>

<div class="tree-holder" id="tree-holder">
<div class="nav-block">
<div class="tree-ref-container">
<div class="tree-ref-holder">
<form class="project-refs-form" action="/lbd/data-science/-/refs/switch" accept-charset="UTF-8" method="get"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="destination" id="destination" value="blob" />
<input type="hidden" name="path" id="path" value="API RAD-on/readme.md" />
<div class="dropdown">
<button class="dropdown-menu-toggle js-project-refs-dropdown qa-branches-select" type="button" data-toggle="dropdown" data-selected="master" data-ref="master" data-refs-url="/lbd/data-science/refs?sort=updated_desc" data-field-name="ref" data-submit-form-on-click="true" data-visit="true"><span class="dropdown-toggle-text ">master</span><svg class="s16 dropdown-menu-toggle-icon gl-top-3" data-testid="chevron-down-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#chevron-down"></use></svg></button>
<div class="dropdown-menu dropdown-menu-selectable git-revision-dropdown dropdown-menu-paging qa-branches-dropdown">
<div class="dropdown-page-one">
<div class="dropdown-title gl-display-flex"><span class="gl-ml-auto">Switch branch/tag</span><button class="dropdown-title-button dropdown-menu-close gl-ml-auto" aria-label="Close" type="button"><svg class="s16 dropdown-menu-close-icon" data-testid="close-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#close"></use></svg></button></div>
<div class="dropdown-input"><input type="search" id="" data-qa-selector="dropdown_input_field" class="dropdown-input-field" placeholder="Search branches and tags" autocomplete="off" /><svg class="s16 dropdown-input-search" data-testid="search-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#search"></use></svg><svg class="s16 dropdown-input-clear js-dropdown-input-clear" data-testid="close-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#close"></use></svg></div>
<div class="dropdown-content"></div>
<div class="dropdown-loading"><div class="gl-spinner-container"><span class="gl-spinner gl-spinner-orange gl-spinner-md gl-mt-7" aria-label="Loading"></span></div></div>
</div>
</div>
</div>
</form>
</div>
<ul class="breadcrumb repo-breadcrumb">
<li class="breadcrumb-item">
<a href="/lbd/data-science/-/tree/master">data-science
</a></li>
<li class="breadcrumb-item">
<a href="/lbd/data-science/-/tree/master/API%20RAD-on">API RAD-on</a>
</li>
<li class="breadcrumb-item">
<a href="/lbd/data-science/-/blob/master/API%20RAD-on/readme.md"><strong>readme.md</strong>
</a></li>
</ul>
</div>
<div class="tree-controls gl-children-ml-sm-3"><a class="gl-button btn btn-default shortcuts-find-file" rel="nofollow" href="/lbd/data-science/-/find_file/master">Find file
</a><a class="gl-button btn btn-default js-blob-blame-link" href="/lbd/data-science/-/blame/master/API%20RAD-on/readme.md">Blame</a><a class="gl-button btn btn-default" href="/lbd/data-science/-/commits/master/API%20RAD-on/readme.md">History</a><a class="gl-button btn btn-default js-data-file-blob-permalink-url" href="/lbd/data-science/-/blob/a02a72da95dfb69aac6a7ad6ca4b9d6f6e408878/API%20RAD-on/readme.md">Permalink</a></div>
</div>

<div class="info-well d-none d-sm-block">
<div class="well-segment">
<ul class="blob-commit-info">
<li class="commit flex-row js-toggle-container" id="commit-318e3674">
<div class="avatar-cell d-none d-sm-block">
<a href="/kpyrtek"><img alt="Katarzyna Pyrtek&#39;s avatar" src="/assets/no_avatar-849f9c04a3a0d0cea2424ae97b27447dc64a7dbfae83c036c45b403392f0e8ba.png" class="avatar s40 d-none d-sm-inline-block" title="Katarzyna Pyrtek" /></a>
</div>
<div class="commit-detail flex-list">
<div class="commit-content" data-qa-selector="commit_content">
<a class="commit-row-message item-title js-onboarding-commit-item " href="/lbd/data-science/-/commit/318e36746fbf6f490c4bdc26fd644f631690b6c6">Update readme.md</a>
<span class="commit-row-message d-inline d-sm-none">
&middot;
318e3674
</span>
<div class="committer">
<a class="commit-author-link js-user-link" data-user-id="176" href="/kpyrtek">Katarzyna Pyrtek</a> authored <time class="js-timeago" title="Nov 22, 2023 1:25pm" datetime="2023-11-22T12:25:12Z" data-toggle="tooltip" data-placement="bottom" data-container="body">Nov 22, 2023</time>
</div>

</div>
<div class="commit-actions flex-row">

<div class="js-commit-pipeline-status" data-endpoint="/lbd/data-science/-/commit/318e36746fbf6f490c4bdc26fd644f631690b6c6/pipelines?ref=master"></div>
<div class="commit-sha-group btn-group d-none d-sm-flex">
<div class="label label-monospace monospace">
318e3674
</div>
<button class="btn gl-button btn btn-default btn-icon" data-toggle="tooltip" data-placement="bottom" data-container="body" data-title="Copy commit SHA" data-class="gl-button btn btn-default btn-icon" data-clipboard-text="318e36746fbf6f490c4bdc26fd644f631690b6c6" type="button" title="Copy commit SHA" aria-label="Copy commit SHA"><svg class="s16" data-testid="copy-to-clipboard-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#copy-to-clipboard"></use></svg></button>

</div>
</div>
</div>
</li>

</ul>
</div>


</div>
<div class="blob-content-holder" id="blob-content-holder">
<article class="file-holder">
<div class="js-file-title file-title-flex-parent">
<div class="file-header-content">
<svg class="s16" data-testid="doc-text-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#doc-text"></use></svg>
<strong class="file-title-name gl-word-break-all" data-qa-selector="file_name_content">
readme.md
</strong>
<button class="btn gl-button btn btn-default-tertiary btn-icon btn-sm" data-toggle="tooltip" data-placement="bottom" data-container="body" data-class="gl-button btn btn-default-tertiary btn-icon btn-sm" data-title="Copy file path" data-clipboard-text="{&quot;text&quot;:&quot;API RAD-on/readme.md&quot;,&quot;gfm&quot;:&quot;`API RAD-on/readme.md`&quot;}" type="button" title="Copy file path" aria-label="Copy file path"><svg class="s16" data-testid="copy-to-clipboard-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#copy-to-clipboard"></use></svg></button>
<small class="mr-1">
1.42 KB
</small>
</div>

<div class="file-actions gl-display-flex gl-align-items-center gl-flex-wrap gl-md-justify-content-end"><div class="btn-group js-blob-viewer-switcher gl-ml-3" role="group">
<button aria-label="Display source" class="btn gl-button btn-default btn-icon js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="simple" title="Display source">
<svg class="s16" data-testid="code-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#code"></use></svg>
</button><button aria-label="Display rendered file" class="btn gl-button btn-default btn-icon js-blob-viewer-switch-btn has-tooltip" data-container="body" data-viewer="rich" title="Display rendered file">
<svg class="s16" data-testid="doc-text-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#doc-text"></use></svg>
</button></div><a class="btn gl-button btn-confirm js-edit-blob gl-ml-3 " data-track-event="click_edit" data-track-label="Edit" href="/lbd/data-science/-/edit/master/API%20RAD-on/readme.md">Edit</a><a class="btn gl-button btn-confirm ide-edit-button gl-ml-3 btn-inverted" data-track-event="click_edit_ide" data-track-label="Web IDE" data-track-property="secondary" href="/-/ide/project/lbd/data-science/edit/master/-/API%20RAD-on/readme.md">Web IDE</a><div class="btn-group gl-ml-3" role="group">

<button name="button" type="submit" class="btn gl-button btn-default btn-default" data-target="#modal-upload-blob" data-toggle="modal">Replace</button>
<button name="button" type="submit" class="btn gl-button btn-default btn-default" data-target="#modal-remove-blob" data-toggle="modal">Delete</button>
</div><div class="btn-group gl-ml-3" role="group">
<span class="btn-group has-tooltip js-copy-blob-source-btn-tooltip"><button class="btn btn gl-button btn-default btn-icon js-copy-blob-source-btn" data-class="btn gl-button btn-default btn-icon js-copy-blob-source-btn" data-hide-tooltip="true" data-clipboard-target=".blob-content[data-blob-id=&#39;fcfa7197250d6bb0a369aac6b4d5a48b027d2442&#39;] &gt; pre" type="button" title="Copy" aria-label="Copy"><svg class="s16" data-testid="copy-to-clipboard-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#copy-to-clipboard"></use></svg></button></span>
<a class="btn gl-button btn-default btn-icon has-tooltip" target="_blank" rel="noopener noreferrer" aria-label="Open raw" title="Open raw" data-container="body" href="/lbd/data-science/-/raw/master/API%20RAD-on/readme.md"><svg class="s16" data-testid="doc-code-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#doc-code"></use></svg></a>
<a download="API RAD-on/readme.md" class="btn gl-button btn-default btn-icon has-tooltip" target="_blank" rel="noopener noreferrer" aria-label="Download" title="Download" data-container="body" href="/lbd/data-science/-/raw/master/API%20RAD-on/readme.md?inline=false"><svg class="s16" data-testid="download-icon"><use xlink:href="/assets/icons-6d7d4be41eac996c72b30eac2f28399ac8c6eda840a6fe8762fc1b84b30d5a2d.svg#download"></use></svg></a>

</div></div>
</div>
<div class="js-file-fork-suggestion-section file-fork-suggestion hidden">
<span class="file-fork-suggestion-note">You can’t <span class="js-file-fork-suggestion-section-action">edit</span> files directly in this project. Fork this project and submit a merge request with your changes.</span>
<a class="js-fork-suggestion-button gl-button btn btn-grouped btn-confirm-secondary" rel="nofollow" data-method="post" href="/lbd/data-science/-/blob/master/API%20RAD-on/readme.md">Fork</a>
<button class="js-cancel-fork-suggestion-button gl-button btn btn-grouped" type="button">
Cancel
</button>
</div>



<div class="blob-viewer hidden" data-path="API RAD-on/readme.md" data-type="simple" data-url="/lbd/data-science/-/blob/master/API%20RAD-on/readme.md?format=json&amp;viewer=simple">
<div class="text-center gl-mt-4 gl-mb-3">
<span class="gl-spinner gl-spinner-orange gl-spinner-md qa-spinner" aria-label="Loading"></span>
</div>

</div>

<div class="blob-viewer" data-path="API RAD-on/readme.md" data-rich-type="markup" data-type="rich" data-url="/lbd/data-science/-/blob/master/API%20RAD-on/readme.md?format=json&amp;viewer=rich">
<div class="text-center gl-mt-4 gl-mb-3">
<span class="gl-spinner gl-spinner-orange gl-spinner-md qa-spinner" aria-label="Loading"></span>
</div>

</div>


</article>
</div>

<div class="modal" id="modal-remove-blob">
<div class="modal-dialog">
<div class="modal-content">
<div class="modal-header">
<h3 class="page-title">Delete readme.md</h3>
<button aria-label="Close" class="close" data-dismiss="modal" type="button">
<span aria-hidden>&times;</span>
</button>
</div>
<div class="modal-body">
<form class="js-delete-blob-form js-quick-submit js-requires-input" action="/lbd/data-science/-/blob/master/API%20RAD-on/readme.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="delete" /><input type="hidden" name="authenticity_token" value="a9HWLhKEkARInJfNCBbQ0xioFIs/HBQSacwT1uiKkmb+gE2+gmo+Oa85fOAS6oO2emuU5+a7Bctf3fF57iFfQg==" /><div class="form-group row commit_message-group">
<label class="col-form-label col-sm-2" for="commit_message-55f2182517a2a536af0d62e86519e6d1">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-55f2182517a2a536af0d62e86519e6d1" class="form-control gl-form-input js-commit-message" placeholder="Delete readme.md" data-qa-selector="commit_message_field" required="required" rows="3">
Delete readme.md</textarea>
</div>
</div>
</div>

<div class="form-group row branch">
<label class="col-form-label col-sm-2" for="branch_name">Target Branch</label>
<div class="col-sm-10">
<input type="text" name="branch_name" id="branch_name" value="master" required="required" class="form-control gl-form-input js-branch-name ref-name" />
<div class="js-create-merge-request-container">
<div class="form-check gl-mt-3">
<input type="checkbox" name="create_merge_request" id="create_merge_request-78a4f87f364e99789394103357f4ffc3" value="1" class="js-create-merge-request form-check-input" checked="checked" />
<label class="form-check-label" for="create_merge_request-78a4f87f364e99789394103357f4ffc3">Start a <strong>new merge request</strong> with these changes
</label></div>

</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-group row">
<div class="offset-sm-2 col-sm-10">
<button name="button" type="submit" class="btn gl-button btn-danger btn-remove-file">Delete file</button>
<a class="btn gl-button btn-cancel" data-dismiss="modal" href="#">Cancel</a>
</div>
</div>
</form></div>
</div>
</div>
</div>

<div class="modal" id="modal-upload-blob">
<div class="modal-dialog modal-lg">
<div class="modal-content">
<div class="modal-header">
<h3 class="page-title">Replace readme.md</h3>
<button aria-label="Close" class="close" data-dismiss="modal" type="button">
<span aria-hidden>&times;</span>
</button>
</div>
<div class="modal-body">
<form class="js-quick-submit js-upload-blob-form" data-method="put" action="/lbd/data-science/-/update/master/API%20RAD-on/readme.md" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="_method" value="put" /><input type="hidden" name="authenticity_token" value="FaEzeAyljnaOs6ZJxgozYUGskKh5NptuZRfKnY82ui6A8KjonEsgS2kWTWTc9mAEI28QxKCRirdTBigyiZ13Cg==" /><div class="dropzone">
<div class="dropzone-previews blob-upload-dropzone-previews">
<p class="dz-message light">
Attach a file by drag &amp; drop or <a class="markdown-selector" href="#">click to upload</a>
</p>
</div>
</div>
<br>
<div class="dropzone-alerts gl-alert gl-alert-danger gl-mb-5 data" style="display:none"></div>
<div class="form-group row commit_message-group">
<label class="col-form-label col-sm-2" for="commit_message-7dc5b35f7e85cb03f4b5a56ecb842b44">Commit message
</label><div class="col-sm-10">
<div class="commit-message-container">
<div class="max-width-marker"></div>
<textarea name="commit_message" id="commit_message-7dc5b35f7e85cb03f4b5a56ecb842b44" class="form-control gl-form-input js-commit-message" placeholder="Replace readme.md" data-qa-selector="commit_message_field" required="required" rows="3">
Replace readme.md</textarea>
</div>
</div>
</div>

<div class="form-group row branch">
<label class="col-form-label col-sm-2" for="branch_name">Target Branch</label>
<div class="col-sm-10">
<input type="text" name="branch_name" id="branch_name" value="master" required="required" class="form-control gl-form-input js-branch-name ref-name" />
<div class="js-create-merge-request-container">
<div class="form-check gl-mt-3">
<input type="checkbox" name="create_merge_request" id="create_merge_request-46555bb218d9475ecee853d5a1c5101e" value="1" class="js-create-merge-request form-check-input" checked="checked" />
<label class="form-check-label" for="create_merge_request-46555bb218d9475ecee853d5a1c5101e">Start a <strong>new merge request</strong> with these changes
</label></div>

</div>
</div>
</div>
<input type="hidden" name="original_branch" id="original_branch" value="master" class="js-original-branch" />

<div class="form-actions">
<button name="button" type="button" class="btn gl-button btn-confirm btn-upload-file" id="submit-all"><div class="gl-spinner gl-mr-2 js-loading-icon hidden"></div>
Replace file
</button><a class="btn gl-button btn-default btn-cancel" data-dismiss="modal" href="#">Cancel</a>

</div>
</form></div>
</div>
</div>
</div>

</div>


</main>
</div>
</div>
</div>


<script>
//<![CDATA[
if ('loading' in HTMLImageElement.prototype) {
  document.querySelectorAll('img.lazy').forEach(img => {
    img.loading = 'lazy';
    let imgUrl = img.dataset.src;
    // Only adding width + height for avatars for now
    if (imgUrl.indexOf('/avatar/') > -1 && imgUrl.indexOf('?') === -1) {
      const targetWidth = img.getAttribute('width') || img.width;
      imgUrl += `?width=${targetWidth}`;
    }
    img.src = imgUrl;
    img.removeAttribute('data-src');
    img.classList.remove('lazy');
    img.classList.add('js-lazy-loaded', 'qa-js-lazy-loaded');
  });
}

//]]>
</script>

</body>
</html>

