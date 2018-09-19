# Josephmakar.github.io
<!DOCTYPE html>
<html class="scripts-not-loaded" dir="ltr"   lang="en">
<head>
  <meta charset="utf-8">
  <title>Slope, Midpoint, and Distance Drag and Drop</title>
  <!--[if lte IE 9]> <meta http-equiv=refresh content="0; URL=/ie-9-is-not-supported.html" /> <![endif]-->
  <link rel="preload" href="https://du11hjcvx0uqb.cloudfront.net/dist/fonts/lato/latin/LatoLatin-Regular-3cd3657802.woff2" as="font" type="font/woff2" crossorigin>
  <link rel="shortcut icon" type="image/x-icon" href="https://instructure-uploads.s3.amazonaws.com/account_131270000000000001/attachments/198/codervalogo.png" />
  <link rel="apple-touch-icon" href="https://du11hjcvx0uqb.cloudfront.net/dist/images/apple-touch-icon-585e5d997d.png" />
  
  <link rel="stylesheet" media="all" href="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/eb0cfef7c2eb514efe770dbeded10898/variables-750d72b9d3e5d522f965bf904110c132.css" />
  <link rel="stylesheet" media="all" href="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_normal_contrast/bundles/common-2ddc5689a4.css" />
  <script>
//<![CDATA[

!function(){
  function get(u){document.write('<scr'+'ipt src="'+ u +'"></sc'+'ript>')}
  var o,s,v;
  if (!(window.Promise && Object.assign && Object.values && [].find && [].includes && (o={},s=Symbol(),v={},o[s]=v,o[s]===v) && (function f(){}).bind().name==='bound f')) {
    get("https://du11hjcvx0uqb.cloudfront.net/dist/ie11-polyfill-9f640d24ea.js");
  }
  window.fetch || get("https://cdnjs.cloudflare.com/ajax/libs/fetch/2.0.4/fetch.min.js");
}();
      
//]]>
</script>
  <script src="https://du11hjcvx0uqb.cloudfront.net/dist/lato-fontfaceobserver-ed903d58c4.js" async="async"></script>
  
  <meta name="apple-itunes-app" content="app-id=480883488" />
<link rel="manifest" href="/web-app-manifest/manifest.json" />
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#008EE2">
  <link rel="stylesheet" media="all" href="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_normal_contrast/bundles/assignments-0e191b779e.css" />
<link rel="stylesheet" media="all" href="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_normal_contrast/bundles/tinymce-cfde159ef1.css" />
<link rel="stylesheet" media="all" href="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_normal_contrast/bundles/learning_outcomes-7cf8ca4f6c.css" />
<link rel="stylesheet" media="all" href="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_normal_contrast/bundles/new_user_tutorials-ee46c92215.css" />
  
  
  <script>
    function _earlyClick(e){
      var c = e.target
      while (c && c.ownerDocument) {
        if (c.getAttribute('href') == '#' || c.getAttribute('data-method')) {
          e.preventDefault()
          (_earlyClick.clicks = _earlyClick.clicks || []).push(c)
          break
        }
        c = c.parentNode
      }
    }
    document.addEventListener('click', _earlyClick)
  </script>
  <script src="https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/eb0cfef7c2eb514efe770dbeded10898/variables-750d72b9d3e5d522f965bf904110c132.js" defer="defer"></script>
  <script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/vendor.bundle-0d87e131da.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/timezone/America/New_York-c3226761e3.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/timezone/en_US-80a0ce259b.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/appBootstrap.bundle-56f81dd4c0.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/common.bundle-1f006d4d0b.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/assignment_show.bundle-d9c22137c3.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/submit_assignment.bundle-7c27dd5686.js" defer="defer"></script>
<script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/edit_rubric.bundle-1da8cdad5c.js" defer="defer"></script>
</head>

<body class="with-left-side course-menu-expanded with-right-side assignments primary-nav-expanded full-width context-course_104 lato-font-not-loaded-yet">

<noscript>
  <div role="alert" class="ic-flash-static ic-flash-error">
    <div class="ic-flash__icon" aria-hidden="true">
      <i class="icon-warning"></i>
    </div>
    <h1>You need to have JavaScript enabled in order to access this site.</h1>
  </div>
</noscript>





<ul id="flash_message_holder"></ul>
<div id="flash_screenreader_holder"></div>

<div id="application" class="ic-app">
  
  <header id="header" class="ic-app-header no-print ">
    <a href="#content" id="skip_navigation_link">Skip To Content</a>
      <div role="region" class="ic-app-header__main-navigation" aria-label="Global Navigation">
        <div class="ic-app-header__logomark-container">
          <a href="https://coderva.instructure.com/" class="ic-app-header__logomark">
            <span class="screenreader-only">Dashboard</span>
          </a>
        </div>
        <ul id="menu" class="ic-app-header__menu-list">
            <li class="menu-item ic-app-header__menu-list-item ">
              <a id="global_nav_profile_link" href="/profile" class="ic-app-header__menu-list-link">
                <div class="menu-item-icon-container" aria-hidden="true">
                  <div class="ic-avatar ">
                    <img src="https://coderva.instructure.com/images/messages/avatar-50.png" alt="Joseph Voda" />
                  </div>
                </div>
                <div class="menu-item__text">
                  Account
                </div>
              </a>
            </li>
          <li class="ic-app-header__menu-list-item ">
            <a id="global_nav_dashboard_link" href="https://coderva.instructure.com/" class="ic-app-header__menu-list-link">
              <div class="menu-item-icon-container" aria-hidden="true">
                  <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg ic-icon-svg--dashboard" version="1.1" x="0" y="0" viewBox="0 0 280 200" enable-background="new 0 0 280 200" xml:space="preserve"><path d="M273.09,180.75H197.47V164.47h62.62A122.16,122.16,0,1,0,17.85,142a124,124,0,0,0,2,22.51H90.18v16.29H6.89l-1.5-6.22A138.51,138.51,0,0,1,1.57,142C1.57,65.64,63.67,3.53,140,3.53S278.43,65.64,278.43,142a137.67,137.67,0,0,1-3.84,32.57ZM66.49,87.63,50.24,71.38,61.75,59.86,78,76.12Zm147,0L202,76.12l16.25-16.25,11.51,11.51ZM131.85,53.82v-23h16.29v23Zm15.63,142.3a31.71,31.71,0,0,1-28-16.81c-6.4-12.08-15.73-72.29-17.54-84.25a8.15,8.15,0,0,1,13.58-7.2c8.88,8.21,53.48,49.72,59.88,61.81a31.61,31.61,0,0,1-27.9,46.45ZM121.81,116.2c4.17,24.56,9.23,50.21,12,55.49A15.35,15.35,0,1,0,161,157.3C158.18,152,139.79,133.44,121.81,116.2Z" /></svg>

              </div>
              <div class="menu-item__text">Dashboard</div>
            </a>
          </li>
          <li class="menu-item ic-app-header__menu-list-item ic-app-header__menu-list-item--active">
            <a id="global_nav_courses_link" href="/courses" class="ic-app-header__menu-list-link">
              <div class="menu-item-icon-container" aria-hidden="true">
                <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg ic-icon-svg--courses" version="1.1" x="0" y="0" viewBox="0 0 280 259" enable-background="new 0 0 280 259" xml:space="preserve"><path d="M73.31,198c-11.93,0-22.22,8-24,18.73a26.67,26.67,0,0,0-.3,3.63v.3a22,22,0,0,0,5.44,14.65,22.47,22.47,0,0,0,17.22,8H200V228.19h-134V213.08H200V198Zm21-105.74h90.64V62H94.3ZM79.19,107.34V46.92H200v60.42Zm7.55,30.21V122.45H192.49v15.11ZM71.65,16.71A22.72,22.72,0,0,0,49,39.36V190.88a41.12,41.12,0,0,1,24.32-8h157V16.71ZM33.88,39.36A37.78,37.78,0,0,1,71.65,1.6H245.36V198H215.15v45.32h22.66V258.4H71.65a37.85,37.85,0,0,1-37.76-37.76Z"/></svg>

              </div>
              <div class="menu-item__text">
                Courses
              </div>
            </a>
          </li>
            <li class="menu-item ic-app-header__menu-list-item ">
              <a id="global_nav_groups_link" href="/groups" class="ic-app-header__menu-list-link">
                <div class="menu-item-icon-container" aria-hidden="true">
                  <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg ic-icon-svg--groups" viewBox="0 0 200 135"><path d="M134.5 129.4c0-1.1 0-19.8-6.2-31.1-4.5-8.5-16.4-12.4-35-19.2-1.7-.6-3.4-1.1-5.1-1.7v-8.5c5.6-5.1 8.5-12.4 8.5-20.3V29.4C96.6 13 83.6 0 67.2 0S37.9 13 37.9 29.4v19.2c0 7.3 3.4 14.7 8.5 20.3v8.5c-1.7.6-3.4 1.1-5.1 1.7-18.6 6.2-30.5 10.7-35 19.2C0 109.6 0 128.8 0 129.4c0 3.4 2.3 5.6 5.6 5.6h123.7c3.5 0 5.7-2.3 5.2-5.6zm-123.2-5.7c.6-5.6 1.7-14.7 3.4-19.8C17 98.8 30 94.3 43.5 89.8c2.8-1.1 5.6-2.3 9-3.4 2.3-.6 4-2.8 4-5.1V66.7c0-1.7-.6-3.4-1.7-4.5-4-3.4-6.2-8.5-6.2-13.6V29.4c0-10.2 7.9-18.1 18.1-18.1s18.1 7.9 18.1 18.1v19.2c0 5.1-2.3 10.2-6.2 13.6-1.1 1.1-1.7 2.8-1.7 4.5v14.7c0 2.3 1.7 4.5 4 5.1 2.8 1.1 6.2 2.3 9 3.4 13.6 5.1 26.6 9.6 28.8 14.1 2.8 5.1 4 13.6 4.5 19.8H11.3zM196 79.1c-2.8-6.2-11.3-9.6-22.6-13.6l-1.7-.6v-3.4c4.5-4 6.8-9.6 6.8-15.8V35c0-12.4-9.6-22-22-22s-22 10.2-22 22v10.7c0 6.2 2.3 11.9 6.8 15.8V65l-1.7.6c-7.3 2.8-13 4.5-16.9 7.3-1.7 1.1-2.3 2.8-2.3 5.1.6 1.7 1.7 3.4 3.4 4.5 7.9 4 12.4 7.3 14.1 10.7 2.3 4.5 4 10.2 5.1 18.1.6 2.3 2.8 4.5 5.6 4.5h45.8c3.4 0 5.6-2.8 5.6-5.1 0-3.9 0-24.3-4-31.6zm-42.9 25.4c-1.1-6.8-2.8-12.4-5.1-16.9-1.7-4-5.1-6.8-9.6-10.2 1.7-1.1 3.4-1.7 5.1-2.3l5.6-2.3c1.7-.6 3.4-2.8 3.4-5.1v-9.6c0-1.7-.6-3.4-2.3-4.5-2.8-1.7-4.5-5.1-4.5-8.5V34.5c0-6.2 4.5-10.7 10.7-10.7s10.7 5.1 10.7 10.7v10.7c0 3.4-1.7 6.2-4.5 8.5-1.1 1.1-2.3 2.8-2.3 4.5v10.2c0 2.3 1.1 4.5 3.4 5.1l5.6 2.3c6.8 2.3 15.3 5.6 16.4 7.9 1.7 2.8 2.8 12.4 2.8 20.9h-35.4z"/></svg>

                </div>
                <div class="menu-item__text">
                  Groups
                </div>
              </a>
            </li>
          <li class="menu-item ic-app-header__menu-list-item ">
            <a id="global_nav_calendar_link" href="/calendar" class="ic-app-header__menu-list-link">
              <div class="menu-item-icon-container" aria-hidden="true">
                <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg ic-icon-svg--calendar" version="1.1" x="0" y="0" viewBox="0 0 280 280" enable-background="new 0 0 280 280" xml:space="preserve"><path d="M197.07,213.38h16.31V197.07H197.07Zm-16.31,16.31V180.76h48.92v48.92Zm-48.92-16.31h16.31V197.07H131.85Zm-16.31,16.31V180.76h48.92v48.92ZM66.62,213.38H82.93V197.07H66.62ZM50.32,229.68V180.76H99.24v48.92Zm146.75-81.53h16.31V131.85H197.07Zm-16.31,16.31V115.54h48.92v48.92Zm-48.92-16.31h16.31V131.85H131.85Zm-16.31,16.31V115.54h48.92v48.92ZM66.62,148.15H82.93V131.85H66.62ZM50.32,164.46V115.54H99.24v48.92ZM34,262.29H246V82.93H34ZM246,66.62V42.16A8.17,8.17,0,0,0,237.84,34H213.38v8.15a8.15,8.15,0,1,1-16.31,0V34H82.93v8.15a8.15,8.15,0,0,1-16.31,0V34H42.16A8.17,8.17,0,0,0,34,42.16V66.62Zm-8.15-48.92a24.49,24.49,0,0,1,24.46,24.46V278.6H17.71V42.16A24.49,24.49,0,0,1,42.16,17.71H66.62V9.55a8.15,8.15,0,0,1,16.31,0v8.15H197.07V9.55a8.15,8.15,0,1,1,16.31,0v8.15Z"/></svg>

              </div>
              <div class="menu-item__text">
                Calendar
              </div>
            </a>
          </li>
          <li class="menu-item ic-app-header__menu-list-item ">
            <a id="global_nav_conversations_link" href="/conversations" class="ic-app-header__menu-list-link">
              <div class="menu-item-icon-container" aria-hidden="true">
                <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg ic-icon-svg--inbox" version="1.1" x="0" y="0" viewBox="0 0 280 280" enable-background="new 0 0 280 280" xml:space="preserve"><path d="M91.72,120.75h96.56V104.65H91.72Zm0,48.28h80.47V152.94H91.72Zm0-96.56h80.47V56.37H91.72Zm160.94,34.88H228.52V10.78h-177v96.56H27.34A24.17,24.17,0,0,0,3.2,131.48V244.14a24.17,24.17,0,0,0,24.14,24.14H252.66a24.17,24.17,0,0,0,24.14-24.14V131.48A24.17,24.17,0,0,0,252.66,107.34Zm0,16.09a8.06,8.06,0,0,1,8,8v51.77l-32.19,19.31V123.44ZM67.58,203.91v-177H212.42v177ZM27.34,123.44H51.48v79.13L19.29,183.26V131.48A8.06,8.06,0,0,1,27.34,123.44ZM252.66,252.19H27.34a8.06,8.06,0,0,1-8-8V202l30,18H230.75l30-18v42.12A8.06,8.06,0,0,1,252.66,252.19Z"/></svg>

                <span class="menu-item__badge" style="display: none">0</span>
              </div>
              <div class="menu-item__text">
                Inbox
              </div>
            </a>
          </li>
            


          <li class="ic-app-header__menu-list-item">
           <a id="global_nav_help_link" class="ic-app-header__menu-list-link" data-track-category="help system" data-track-label="help button" href="http://help.instructure.com/">
              <div class="menu-item-icon-container" role="presentation">
                <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg menu-item__icon svg-icon-help" version="1.1" x="0" y="0" viewBox="0 0 200 200" enable-background="new 0 0 200 200" xml:space="preserve" fill="currentColor"><path d="M100,127.88A11.15,11.15,0,1,0,111.16,139,11.16,11.16,0,0,0,100,127.88Zm8.82-88.08a33.19,33.19,0,0,1,23.5,23.5,33.54,33.54,0,0,1-24,41.23,3.4,3.4,0,0,0-2.74,3.15v9.06H94.42v-9.06a14.57,14.57,0,0,1,11.13-14,22.43,22.43,0,0,0,13.66-10.27,22.73,22.73,0,0,0,2.31-17.37A21.92,21.92,0,0,0,106,50.59a22.67,22.67,0,0,0-19.68,3.88,22.18,22.18,0,0,0-8.65,17.64H66.54a33.25,33.25,0,0,1,13-26.47A33.72,33.72,0,0,1,108.82,39.8ZM100,5.2A94.8,94.8,0,1,0,194.8,100,94.91,94.91,0,0,0,100,5.2m0,178.45A83.65,83.65,0,1,1,183.65,100,83.73,83.73,0,0,1,100,183.65" transform="translate(-5.2 -5.2)"/></svg>

              </div>
              <div class="menu-item__text">
                Help
              </div>
</a>          </li>
        </ul>
      </div>
      <div class="ic-app-header__secondary-navigation">
        <ul class="ic-app-header__menu-list">
          <li class="menu-item ic-app-header__menu-list-item">
            <button
              id="primaryNavToggle"
              class="ic-app-header__menu-list-link ic-app-header__menu-list-link--nav-toggle"
              aria-label="Minimize global navigation"
              title="Minimize global navigation"
            >
              <div class="menu-item-icon-container" aria-hidden="true">
                <svg xmlns="http://www.w3.org/2000/svg" class="ic-icon-svg ic-icon-svg--navtoggle" version="1.1" x="0" y="0" width="40" height="32" viewBox="0 0 40 32" xml:space="preserve">
  <path d="M39.5,30.28V2.48H37.18v27.8Zm-4.93-13.9L22.17,4,20.53,5.61l9.61,9.61H.5v2.31H30.14l-9.61,9.61,1.64,1.64Z"/>
</svg>

              </div>
            </button>
          </li>
        </ul>
      </div>
    <div id="global_nav_tray_container"></div>
  </header>


  <div id="instructure_ajax_error_box">
    <div style="text-align: right; background-color: #fff;"><a href="#" class="close_instructure_ajax_error_box_link">Close</a></div>
    <iframe id="instructure_ajax_error_result" src="about:blank" style="border: 0;" title="Error"></iframe>
  </div>

  

  <div id="wrapper" class="ic-Layout-wrapper">
      <div class="ic-app-nav-toggle-and-crumbs no-print">
          <button type="button" id="courseMenuToggle" class="Button Button--link ic-app-course-nav-toggle" aria-live="polite" aria-label="Hide Courses Navigation Menu" title="Hide Courses Navigation Menu">
            <i class="icon-hamburger" aria-hidden="true"></i>
          </button>
          <div class="ic-app-crumbs">
        <nav id="breadcrumbs" role="navigation" aria-label="breadcrumbs"><ul><li class="home"><a href="/"><span class="ellipsible">      <i class="icon-home"
         title="My Dashboard">
        <span class="screenreader-only">My Dashboard</span>
      </i>
</span></a></li><li><a href="/courses/104"><span class="ellipsible">Geometry - Cooper</span></a></li><li><a href="/courses/104/assignments"><span class="ellipsible">Assignments</span></a></li><li><a href="https://coderva.instructure.com/courses/104/assignments/1117"><span class="ellipsible">Slope, Midpoint, and Distance Drag and Drop</span></a></li></ul></nav>
        </div>
          <div class="TutorialToggleHolder"></div>
      </div>
    <div id="main" class="ic-Layout-columns">
        <div class="ic-Layout-watermark"></div>
        <div id="left-side"
          class="ic-app-course-menu list-view"
          style="display: block"
          >
              <span id="section-tabs-header-subtitle" class="ellipsis">2018/2019 - CodeRVA Regional High School - 2018-2019</span>
            <nav role="navigation" aria-label="Courses Navigation Menu"><ul id="section-tabs"><li class="section"><a href="/courses/104" title="Home" class="home">Home</a></li><li class="section"><a href="/courses/104/announcements" title="Announcements" class="announcements">Announcements</a></li><li class="section"><a href="/courses/104/assignments" title="Assignments" class="assignments active">Assignments</a></li><li class="section"><a href="/courses/104/discussion_topics" title="Discussions" class="discussions">Discussions</a></li><li class="section"><a href="/courses/104/grades" title="Grades" class="grades">Grades</a></li><li class="section"><a href="/courses/104/users" title="People" class="people">People</a></li><li class="section"><a href="/courses/104/wiki" title="Pages" class="pages">Pages</a></li><li class="section"><a href="/courses/104/assignments/syllabus" title="Syllabus" class="syllabus">Syllabus</a></li><li class="section"><a href="/courses/104/quizzes" title="Quizzes" class="quizzes">Quizzes</a></li><li class="section"><a href="/courses/104/modules" title="Modules" class="modules">Modules</a></li><li class="section"><a href="/courses/104/lti_collaborations" title="Collaborations" class="collaborations">Collaborations</a></li><li class="section"><a href="/courses/104/external_tools/1" title="Google Drive" class="context_external_tool_1">Google Drive</a></li><li class="section"><a href="/courses/104/external_tools/7" title="Badges" class="context_external_tool_7">Badges</a></li><li class="section"><a href="/courses/104/external_tools/18" title="Flipgrid" class="context_external_tool_18">Flipgrid</a></li></ul></nav>
        </div>
      <div id="not_right_side" class="ic-app-main-content">
        <div id="content-wrapper" class="ic-Layout-contentWrapper">
            

          <div id="content" class="ic-Layout-contentMain" role="main">
            



<div id="assignment_show" class="assignment content_underline_links">
    <!--Student View-->
    <div class='assignment-title'>
      <div class='title-content'>
        <h1 class="title">
          Slope, Midpoint, and Distance Drag and Drop
        </h1>
      </div>
      <div class='assignment-buttons'>
        

        <a role="button" class="Button Button--primary submit_assignment_link " href="#">Submit Assignment</a>
      </div>
    </div>
    <ul class='student-assignment-overview'>
      <li>
        <span class='title'>Due</span>
        <span class='value'>
          <span class="date_text">
                <span class="display_date">Wednesday</span> by 
                <span class="display_time">11:59pm</span>
          </span>
        </span>
      </li>
      <li>
        <span class='title'>Points</span>
        <span class='value'>100</span>
      </li>
        <li>
          <span class='title'>Submitting</span>
          <span class='value'>a website url</span>
        </li>
      

      <div class="clear"></div>
    </ul>

  <div class="clear"></div>


  <div class="clear"></div>

  <div class="description user_content student-version"><h3>Directions</h3>
<p>Make a copy of the Google draw file (link below).  In your copy, change the name to "Your Name SOL G.3a Drag and Drop".  For example, your title should be something like "Ms. Cooper SOL G.3a Drag and Drop" or "John Wayne SOL G.3a Drag and Drop".</p>
<p>Then, complete the drag and drop</p>
<p>You will need to show work, and you will need to turn in a piece of work paper to me.</p>
<h3>To Submit</h3>
<p>Share your completed Google draw slide with me by clicking "Share" in the top right corner and copy/pasting the link to this assignment.</p>
<p>You will also need to turn in your work paper!</p></div>


  <div style="display: none;">
    <span class="timestamp">1537415999</span>
    <span class="due_date_string">09/19/2018</span>
    <span class="due_time_string">11:59pm</span>
  </div>
</div>


  
<div style="display: none;" id="submit_assignment" data-context_code="course_104" data-asset_string="assignment_1117">
  <div class="content" id="submit_assignment_tabs">
    <ul>
        <li><a href="#submit_online_url_form" class="submit_online_url_option">Website URL</a></li>
        <li><a href="#submit_from_external_tool_form_29"
          class="external-tool"
          data-id="29"
          data-name="CK-12">CK-12 Practice</a></li>
        <li><a href="#submit_from_external_tool_form_1"
          class="external-tool"
          data-id="1"
          data-name="Google Apps">Google Drive</a></li>
    </ul>


    <form id="submit_online_url_form" class="submit_assignment_form" action="/courses/104/assignments/1117/submissions" accept-charset="UTF-8" method="post"><input name="utf8" type="hidden" value="&#x2713;" /><input type="hidden" name="authenticity_token" value="F8uE3KvL9U8DDUI9eQ/x7pFaUXDDXOFG5b/wxwJJHdhiht2b3aC7CFFKLU4xRZmUwDxmJYItyiSv9sGGWDxnmw==" />
    <input value="online_url" type="hidden" name="submission[submission_type]" id="submission_submission_type" />
    <table class="formtable" style="width: 100%;">
      <tr>
        <td colspan="2">
          Copy and paste the link to the web site you&#39;d like to submit for this assignment.
            
          </td>
      </tr><tr>
        <td colspan="2">
          <label for="submission_url">Website URL:</label>
          &nbsp;&nbsp;
          <input style="min-width: 250px;" type="text" name="submission[url]" id="submission_url" />
        </td>
      </tr><tr>
        <td colspan="2" style="text-align: center;">
          <div style="text-align: left;">
            <textarea class="submission_comment_textarea" placeholder="Comments..." title="Additional comments" name="submission[comment]" id="submission_comment">
</textarea>
          </div>
        </td>
      </tr>
      

      <tr>
        <td colspan="2" class='button-container'>
          <button type="button" class='cancel_button btn'>Cancel</button>
          <button type="submit" class="btn btn-primary">Submit Assignment</button>
        </td>
      </tr>
    </table>
</form>
    <style>
    #google_docs_tree li.folder {
      cursor: pointer;
    }
    #google_docs_tree li.file {
      cursor: pointer;
      -moz-border-radius: 3px;
      width: 80%;
      padding-right: 20px;
    }
    #google_docs_tree li.file:hover {
      background-color: #eee;
    }
    ul.instTree li span.active {
      background: none;
    }
    #google_docs_tree li.file.leaf.active {
      background-color: #ddd;
    }
    #google_docs_tree li.file .filename {
      float: left;
      max-width: 98%;
    }
    #google_docs_tree li.file .popout {
      float: right;
    }
    </style>


      <div id="submit_from_external_tool_form_29" style="padding: 5px 5px 0 5px;"></div>
      <div id="submit_from_external_tool_form_1" style="padding: 5px 5px 0 5px;"></div>

  </div>
</div>





  <div id="rubrics" style="margin-bottom: 10px;">
    <div style="display: none;" id="rubric_parameters">
      <input type="hidden" name="rubric_association[association_type]" value="Assignment"/>
      <input type="hidden" name="rubric_association[association_id]" value="1117"/>
      <input type="hidden" name="rubric_association[purpose]" value="grading"/>
    </div>
    
<div id="rubric_long_description_dialog" style="display: none;">
  <div class="editing">
    <form id="edit_criterion_form" class="no-margin-bottom">
      <div>
        <label class="rating_form_label">Description
          <textarea class="description" rows="1" name="description"></textarea>
        </label>
      </div>
      <div>
        <label class="rating_form_label">Long Description
          <textarea class="long_description" rows="4" name="long_description"></textarea>
        </label>
      </div>
      <div class="button-container">
        <button type="button" class="btn btn button-secondary cancel_button">Cancel</button>
        <button type="button" class="btn save_button btn-primary">Update Criterion</button>
      </div>
    </form>
  </div>
  <div class="displaying">
    <div class="long_description">
    </div>
  </div>
</div>
<div id="rubric_criterion_comments_dialog" style="display: none;">
  <div
    class="criterion_description"
    style="border-bottom: 1px solid #ccc; padding: 5px 0; font-size: 1.2em; font-weight: bold; margin-bottom: 5px;"
    tabindex="-1"
  ></div>
  <div class="editing">
    <label for="criterion_comments_textarea">
      Additional Comments:
    </label>
    <textarea
      id="criterion_comments_textarea"
      class="criterion_comments"
      name="criterion_comments"
      style="width: 370px;"></textarea>
    <div class="button-container">
      <button type="button" class="btn btn button-secondary cancel_button">Cancel</button>
      <button type="button" class="btn save_button">Update Comments</button>
    </div>
  </div>
  <div class="displaying">
    Additional Comments:
    <div class="criterion_comments" style="margin-top: 10px;">
    </div>
  </div>
</div>
<div id="rubric_rating_dialog" style="display: none;">
  <div class="description" style="border-bottom: 1px solid #ccc; padding: 5px 0; font-size: 1.2em; font-weight: bold; margin-bottom: 5px;">
    <span id="edit_rating_form_criterion_description"></span>
  </div>
  <div class="editing">
    <form id="edit_rating_form" class="no-margin-bottom">
      <div class="toggle_for_hide_points">
        <div><label id='rating_form_score_label' class="rating_form_label">Rating Score</label></div>
        <span id='rating_form_max_score_label' hidden>Rating max score</span>
        <input id="points" aria-labelledby="rating_form_score_label" type="text" size="2" name="points" class="no-margin-bottom span1" />
        <span class="range_rating">to >
          <input aria-label="Rating min score" type="text" size="2" name="min_points" class="no-margin-bottom span1 min_points" placeholder="min"/>
        </span>pts
      </div>
      <div>
        <label for="rating_form_title" class="rating_form_label">Rating Title</label>
        <input id="rating_form_title" type="text" class="rating_description" style="width: 90%;" name="description"/>
      </div>
      <div>
        <label for="rating_form_description" class="rating_form_label">Rating Description</label>
        <textarea id="rating_form_description" rows="4" style="width: 90%;" class="rating_long_description" name="rating_long_description" form="edit_rating_form"></textarea>
      </div>
      <div class="button-container">
        <button type="button" class="btn button-secondary cancel_button">Cancel</button>
        <button type="button" class="btn btn-primary save_button ok_button">Update Rating</button>
      </div>
    </form>
  </div>
</div>

  </div>
  
<div
  class="rubric_container rubric  "
  id="default_rubric"
  style="display: none;"
  tabindex="0"
>
  <div class="screenreader-only"><h2>Rubric</h2></div>
  <div class="rubric_title">
    <div style="display: none;" class="links displaying pull-right">
      <a
        href="/courses/104/rubrics/%7B%7B%20id%20%7D%7D"
        class=" edit_rubric_link no-print no-hover"
        style=""
        title="Edit Rubric"
        aria-label="Edit Rubric"
        role="button"
      ><i class="icon-edit standalone-icon"></i></a>
      <a
        href="https://coderva.instructure.com/search/rubrics?q="
        class="find_rubric_link no-print no-hover"
        style=""
        title="Find Another Rubric"
        aria-label="Find Another Rubric"
        role="button"
      ><i class="icon-search standalone-icon"></i></a>
        <a
          href="/courses/104/rubric_associations/%7B%7B%20rubric_association_id%20%7D%7D"
          class="delete_rubric_link no-print no-hover"
          style=""
          title="Delete Rubric"
          aria-label="Delete Rubric"
          role="button"
        ><i class="icon-trash standalone-icon"></i></a>
      <div style="display: none;">
        <div class="use_for_grading">&nbsp;</div>
        <div class="free_form_criterion_comments">&nbsp;</div>
        <div class="hide_score_total">&nbsp;</div>
        <div class="hide_outcome_results">&nbsp;</div>
        <div class="hide_points">&nbsp;</div>
        <div class="rubric_association_id">&nbsp;</div>
        <div class="user_id">&nbsp;</div>
        <div class="assessment_type"></div>
        <a href="/courses/104/rubric_associations/%7B%7B%20rubric_association_id%20%7D%7D/assessments/%7B%7B%20assessment_id%20%7D%7D" rel="nofollow" class="edit_assessment_link">&nbsp;</a>
        <a href="/courses/104/rubrics/%7B%7B%20rubric_id%20%7D%7D" class="edit_rubric_url">&nbsp;</a>
          <a href="/courses/104/rubric_associations/%7B%7B%20association_id%20%7D%7D" class="delete_rubric_url">&nbsp;</a>
      </div>
    </div>
    <div style="float: right; font-size: 0.8em; display: none;" class="links displaying locked">
      <span style="">Can&#39;t change a rubric once you&#39;ve started using it.</span>
        <a href="/courses/104/rubric_associations/%7B%7B%20association_id%20%7D%7D" class="delete_rubric_url" style="display: none;">&nbsp;</a>
    </div>

    <div class="editing" style="float: right;">
      <a href="https://coderva.instructure.com/search/rubrics?q=" class="find_rubric_link icon-search" style="" title="Find Existing Rubric">Find a Rubric</a>
    </div>
    <div class="editing" style="text-align: left">
      <label for="rubric-title">Title:</label>
      <input id="rubric-title" type="text" class="no-margin-bottom" name="title" value="Some Rubric" style="width: 200px;" maxlength="255" aria-label="Title:"/>
      <a href="https://coderva.instructure.com/search/rubrics?q=" style="display: none;"><img alt="" src="https://du11hjcvx0uqb.cloudfront.net/dist/images/find-6164443e2a.png" /> Find Rubric</a>
    </div>
    <div class="displaying">
      <span class="title" tabindex="-1">Title</span>
    </div>
    <div class="has-assessments-warning" style="display: none;">
      You&#39;ve already rated students with this rubric.  Any major changes could affect their assessment results.
    </div>
  </div>
<table class="rubric_table">
<caption>
  <div class="screenreader-only">
    <span class="title">Title</span>
  </div>
</caption>
<thead>
  <tr>
    <th scope="col">Criteria</th>
    <th scope="col">Ratings</th>
    <th scope="col" class="toggle_for_hide_points ">
      Pts
    </th>
  </tr>
</thead>
<tbody>
  
<tr id="criterion_blank" class="criterion blank  " style="display: none;">
  <td class="criterion_description hover-container pad-box-micro">
    <div class="container">
      <div class="links editing">
          <a href="#" class="edit_criterion_link"><i class="icon-edit standalone-icon"></i><span class="screenreader-only">Edit criterion description</span></a>
        <a href="#" class="delete_criterion_link"><i class="icon-trash standalone-icon"></i><span class="screenreader-only">Delete criterion row</span></a>
      </div>
      <div class="description_content">
        <span class="outcome_sr_content" aria-hidden="true">
          <i class="learning_outcome_flag icon-outcomes" aria-hidden="true"></i>
          <span class="screenreader-only">This criterion is linked to a Learning Outcome</span>
        </span>
        <span class="description description_title">Description of criterion</span>
        <span class="learning_outcome_id" style="display: none;"></span>
        <span class="criterion_id" style="display: none;"></span>
          <div class="long_description small_description"></div>
        <div style="display: none;" class="long_description_holder editing empty">
          <a href="#" class="long_description_link hidden">view longer description</a>
          <textarea class="long_description" aria-label="Long Description" style="display: none;"></textarea>
        </div>
        <div class="hide_when_learning_outcome ">
          <div class="criterion_use_range_div editing toggle_for_hide_points ">
            <label>Range
              <input type="checkbox" class="criterion_use_range" /></label>
          </div>
        </div>
        <div class="threshold toggle_for_hide_points ">
          threshold:
          <span class="mastery_points">5</span> pts
        </div>
      </div>

    </div>
  </td>
  <td style="padding: 0;">
      <table class="ratings" style=""><tr>
          <td id="rating_blank"
              class="rating edge_rating
                
                "
          >
            <div class="container">
              <div class="rating-main">
                  <div class="editing links">
                    <a href="#" class="edit_rating_link"><i class="icon-edit standalone-icon"></i><span class="screenreader-only">Edit rating</span></a>
                    <a href="#" class="delete_rating_link"><i class="icon-trash standalone-icon" ></i><span class="screenreader-only">Delete rating</span></a>
                  </div>
                  <div class="clear"></div>
                <span class="nobr toggle_for_hide_points ">
                  <span class="points">5</span>
                  <span class="range_rating" style="display: none;">to ><span class="min_points">0</span></span> pts
                </span>
                <div class="description rating_description_value">Full Marks</div>
                <div class="rating_long_description small_description"></div>
                <span class="rating_id" style="display: none;">blank</span>
              </div>
                <div class="editing links add_rating_link">
                  <a href="#" class="add_rating_link_after" aria-label="Add rating"><i class="icon-add icon-Solid"></i></a>
                </div>
            </div>
          </td>
          <td id="rating_blank_2"
              class="rating edge_rating
                infinitesimal
                "
          >
            <div class="container">
              <div class="rating-main">
                  <div class="editing links">
                    <a href="#" class="edit_rating_link"><i class="icon-edit standalone-icon"></i><span class="screenreader-only">Edit rating</span></a>
                    <a href="#" class="delete_rating_link"><i class="icon-trash standalone-icon" ></i><span class="screenreader-only">Delete rating</span></a>
                  </div>
                  <div class="clear"></div>
                <span class="nobr toggle_for_hide_points ">
                  <span class="points">0</span>
                  <span class="range_rating" style="display: none;">to ><span class="min_points">0</span></span> pts
                </span>
                <div class="description rating_description_value">No Marks</div>
                <div class="rating_long_description small_description"></div>
                <span class="rating_id" style="display: none;">blank_2</span>
              </div>
            </div>
          </td>
      </tr></table>
      <div style="display: none; font-size: 0.8em; margin: 5px;" class="custom_ratings">
        This area will be used by the assessor to leave comments related to this criterion.
      </div>
  </td>
  <td class="nobr points_form toggle_for_hide_points ">
    <div class="editing" style="white-space: normal">
      <span style="white-space: nowrap; font-size: 0.8em">
          
            <input
              type="text"
              aria-label="Points"
              value="5"
              class="criterion_points span1 no-margin-bottom"
            />
           pts
      </span><br />
    </div>
    <div class="displaying">
      <span style="white-space: nowrap;">
        <span class="criterion_rating_points_holder" style="display: none;">
          <span class="criterion_rating_points">&nbsp;</span> /
        </span>
        <span class="display_criterion_points">5</span> pts<br />
      </span>
    </div>
    <div class="ignoring">
      <span> -- </span>
    </div>
    <div class="criterion_comments">
        <a href="#" class="no-hover criterion_comments_link" title="Additional Comments">
          <img alt="Additional Comments" src="https://du11hjcvx0uqb.cloudfront.net/dist/images/rubric_comment-ddae8546ab.png" />
        </a>
        <div class="custom_rating" style="display: none;"></div>
    </div>
  </td>
</tr>

  <tr class="summary">
    <td colspan="4">
      <div class="total_points_holder toggle_for_hide_points "
        style="float: right; ">
        <span>Total Points:
            <span class="rubric_total">
              5
            </span>
 <span class="assessing">out of 5</span>        </span>
      </div>
      <div class="editing pull-left">
        <span id="add_criterion_holder" class="criterion_link"></span>
      </div>
      <div class="clear"></div>
    </td>
  </tr>
</tbody>
</table>
</div>
<table style="display: none;">
  <tr id="edit_rubric">
    <td colspan="4">
      <form id="edit_rubric_form" class="edit-rubric-form no-margin-bottom">
        <div class="rubric_custom_ratings" style="">
          <input type="checkbox" id="rubric_custom_rating" class="rubric_custom_rating" />
          <label for="rubric_custom_rating">I&#39;ll write free-form comments when assessing students</label>
        </div>
          <div class="hide_points" style="">
            <input type="checkbox" id="hide_points" class="hide_points_checkbox" />
            <label for="hide_points">Remove points from rubric</label>
          </div>
          <div class="hide_outcome_results" style="">
            <input type="checkbox" id="hide_outcome_results" class="hide_outcome_results_checkbox" />
            <label for="hide_outcome_results">Don&#39;t post Outcomes results to Learning Mastery Gradebook</label>
          </div>
          <div class="rubric_grading" style="">
            <input type="checkbox" id="grading_rubric" class="grading_rubric_checkbox" />
            <label for="grading_rubric">Use this rubric for assignment grading</label>
          </div>
        <div class="totalling_rubric" style="">
          <input type="checkbox" id="totalling_rubric" class="totalling_rubric_checkbox" />
          <label for="totalling_rubric">Hide score total for assessment results</label>
        </div>
        <div class="ic-Action-header ic-Action-header--half-margin">
          <div class="ic-Action-header__Primary">
            <button type="button" class="Button cancel_button">Cancel</button>
            <button type="submit" class="Button Button--primary save_button">Create Rubric</button>
          </div>
        </div>
      </form>
    </td>
  </tr>
</table>

  


          </div>
        </div>
        <div id="right-side-wrapper" class="ic-app-main-content__secondary">
          <aside id="right-side" role="complementary">
            
<div id="sidebar_content">


</div>

          </aside>
        </div>
      </div>
    </div>
  </div>



    <div style="display:none;"><!-- Everything inside of this should always stay hidden -->
        <div id="page_view_id">ca862fd0-7193-4600-9cd0-eaa1beb68ca5</div>
    </div>
  <div id='aria_alerts' class='hide-text affix' role="alert" aria-live="assertive"></div>
  <div id='StudentTray__Container'></div>
    <div class="NewUserTutorialTray__Container"></div>
  

<script>
  INST = {"environment":"production","allowMediaComments":true,"kalturaSettings":{"domain":"nv.instructuremedia.com","resource_domain":"nv.instructuremedia.com","rtmp_domain":"fms-prod.instructuremedia.com","partner_id":"9","subpartner_id":"0","player_ui_conf":"0","kcw_ui_conf":"0","upload_ui_conf":"0","max_file_size_bytes":534773760,"do_analytics":false,"hide_rte_button":false,"js_uploader":true},"googleAnalyticsAccount":"UA-9138420-1","logPageViews":true,"maxVisibleEditorButtons":3,"editorButtons":[{"name":"Google Apps","id":1,"url":"https://google-drive-lti-iad-prod.instructure.com/lti/rce-content-selection","icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png","canvas_icon_class":null,"width":700,"height":600},{"name":"YouTube","id":2,"url":"https://www.edu-apps.org/lti_public_resources/?tool_id=youtube","icon_url":"https://www.edu-apps.org/assets/lti_public_resources/youtube_icon.png","canvas_icon_class":null,"width":560,"height":600},{"name":"Khan Academy","id":4,"url":"https://www.edu-apps.org/lti_public_resources/?tool_id=khan_academy","icon_url":"https://www.edu-apps.org/assets/lti_public_resources/khan_academy_icon.png","canvas_icon_class":null,"width":560,"height":600},{"name":"Quizlet","id":8,"url":"https://www.edu-apps.org/lti_public_resources/?tool_id=quizlet","icon_url":"https://www.edu-apps.org/assets/lti_public_resources/quizlet_icon.png","canvas_icon_class":null,"width":560,"height":600},{"name":"Screencast-O-Matic","id":20,"url":"https://screencast-o-matic.com/lti/editorButton","icon_url":"https://dfjnl57l0uncv.cloudfront.net/www/3.1.100/images/lti_canvas_editbutton.png","canvas_icon_class":null,"width":770,"height":600}]};
  ENV = {"ASSET_HOST":"https://du11hjcvx0uqb.cloudfront.net","active_brand_config_json_url":"https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/eb0cfef7c2eb514efe770dbeded10898/variables-750d72b9d3e5d522f965bf904110c132.json","url_to_what_gets_loaded_inside_the_tinymce_editor_css":["https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/eb0cfef7c2eb514efe770dbeded10898/variables-750d72b9d3e5d522f965bf904110c132.css","https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_normal_contrast/bundles/what_gets_loaded_inside_the_tinymce_editor-53dac18d10.css"],"url_for_high_contrast_tinymce_editor_css":["https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/default/variables-high_contrast-750d72b9d3e5d522f965bf904110c132.css","https://du11hjcvx0uqb.cloudfront.net/dist/brandable_css/new_styles_high_contrast/bundles/what_gets_loaded_inside_the_tinymce_editor-b4d65fe883.css"],"current_user_id":"180","current_user_roles":["user","student"],"current_user_disabled_inbox":false,"files_domain":"cluster7-files.instructure.com","DOMAIN_ROOT_ACCOUNT_ID":131270000000000001,"k12":false,"use_responsive_layout":false,"help_link_name":"Help","help_link_icon":"help","use_high_contrast":false,"LTI_LAUNCH_FRAME_ALLOWANCES":["geolocation *","microphone *","camera *","midi *","encrypted-media *"],"SETTINGS":{"open_registration":false,"eportfolios_enabled":true,"collapse_global_nav":false,"show_feedback_link":true,"enable_profiles":true},"current_user":{"id":"180","display_name":"Joseph Voda","avatar_image_url":"https://coderva.instructure.com/images/messages/avatar-50.png","html_url":"https://coderva.instructure.com/about/180"},"page_view_update_url":"/page_views/ca862fd0-7193-4600-9cd0-eaa1beb68ca5?page_view_token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJpIjoiY2E4NjJmZDAtNzE5My00NjAwLTljZDAtZWFhMWJlYjY4Y2E1IiwidSI6MTMxMjcwMDAwMDAwMDAwMTgwLCJjIjoiMjAxOC0wOS0xOVQxNjozOTo1My44NloifQ.kiT9Sh4bJjIx42wFhnirKANz86WA1UElhMJnFPpd71U","context_asset_string":"course_104","ping_url":"https://coderva.instructure.com/api/v1/courses/104/ping","TIMEZONE":"America/New_York","CONTEXT_TIMEZONE":"America/New_York","LOCALE":"en","BIGEASY_LOCALE":"en_US","FULLCALENDAR_LOCALE":"en","MOMENT_LOCALE":"en","RICH_CONTENT_SERVICE_ENABLED":true,"RICH_CONTENT_APP_HOST":"rich-content-iad.inscloudgate.net","RICH_CONTENT_CDN_HOST":"dvgcns7dz7zc.cloudfront.net/rce_service/versions/","RICH_CONTENT_SKIP_SIDEBAR":null,"JWT":"ZXlKaGJHY2lPaUprYVhJaUxDSmxibU1pT2lKQk1qVTJSME5OSW4wLi5Fd2lMQThwSVV0WTQ4aW5RLmJyZnNpLW9HU0ZBVDlxR2lTSm5qUUhzWG9oMWJsYUdmUFg0M3VHMGJtNkpGUG5CQVNsc0NsVEhObFZPYzBNNU5nZXgySlhyOUZRVzUwMU9qMDl3Rl9LanJYb1EyUEpxR2swTzBSN1pQQ0twVzd5dkEtRTVGTjZ3Zm8zWE9FYlFPSzhDY09KT25IMTBGelRfd2liaE5GbDB2U3ZTMldYZUVjX2lXU3NNYm5XMkxkVTFFZGp5Qng0SHhwQ2s0Y2lmTHYtQWhuTExqTkY1UDZNc2FPYlNrQ3p2WGRyc29ucmhudFlReE1MQTE0ZkhObGNkdEdNMnpNc29PUXdlZlh3VFNIYXkyZ1l0c0NaTzAwRGVlQWYtb29SekgwdjduQ1gydGVCY2RUZkZuelNERFZVZWlFRUhmX3YySGJvVFhfOU1xYWgtaDhPbTdIc3B1amNtcjEzQUt0bmJ1ckxyOFdIX3lQQ3JseWNlaW9FeXhQTm0wekE0LW8zUEQ4b19HUThGdnZIbUlSNXRIYUl0SWdtenJMV1RpZDJxMDZDbU9VeVBxNDE1eGl6Y0NEZDFMOVpkODdNVDlNVzY1V3pzMWRJYUQtdThHUjlOSmpqLV9qUjNwR0hablU0dmhzUTdZZGdGVHVyc3NrQlNvRFFVRDd1V3NRM0o2b1JnODJpT1MyRmRaX3oyS0xwTlJOX3ZqSGM3QTJFTDU3a2tJTWMtSElydm1mZjRQUWUtQVRtUGdRY1hqNGUwc1hYaVN5VzhkT0tfRVVhN0FmNVdYcUNEZXlvZHNpR1pNLWhGTlJ1a3dZRi1aRW12TVB2Vm1XUE1FRjRaR1dpZi03QkFmb1hmc05fVFBCME1WMzdmdjRBVTd4UlhWdFVDd2dWMU9iRkI0S2JiWVNJNEh4QWduSUE5YS0xRUpNTDdMVDE5VE5nZmw5YmgyNC00cXRMbFZFSXZ2LUtxVDFtblg2amlfcERrUDgwd3pqQi1MYXhZVVl5RlVqOGR6ZjZNUmtQWGxPWGpJSUNvaFkzTElaTjBQSHZnMk9pb0ZaMUtJdUVIdTZDMFlLVTNQRkIzVkhVVGlKYmRaLjNkUXloczRmdjJoQmZOZ00xMlc3Z1E=","RICH_CONTENT_CAN_UPLOAD_FILES":false,"ROOT_OUTCOME_GROUP":{"id":"45","title":"Geometry - Cooper","vendor_guid":null,"url":"/api/v1/courses/104/outcome_groups/45","subgroups_url":"/api/v1/courses/104/outcome_groups/45/subgroups","outcomes_url":"/api/v1/courses/104/outcome_groups/45/outcomes","can_edit":false,"import_url":"/api/v1/courses/104/outcome_groups/45/import","context_id":"104","context_type":"Course","description":null},"COURSE_ID":104,"ASSIGNMENT_ID":1117,"EXTERNAL_TOOLS":[{"id":"29","domain":"ck12.org","url":"https://www.ck12.org/auth/launch/lti/ltiApp","consumer_key":"jVNOdq7doxPKO8A1InyKIEfVxCvO0upDW51O7hxc2C1XLfnnbq","name":"CK-12","description":"CK-12 Foundation is a leading open educational resources (OER) non-profit organization dedicated to increasing access to high-quality K-12 STEM education materials. CK-12 offers free high-quality, standards-aligned, open content in the STEM subjects through an integrated set of tools for learning including digital textbooks, concept-based learning resources, simulations, interactive practice and more. All content is created and curated by teachers, for teachers and students.\n\nAll CK-12 products and services are 100% free and are being used by students and teachers across thousands of schools both in the US and rest of the world. ","created_at":"2018-09-10T18:19:38Z","updated_at":"2018-09-10T18:19:38Z","privacy_level":"public","custom_fields":{},"workflow_state":"public","vendor_help_link":null,"account_navigation":null,"similarity_detection":null,"assignment_menu":null,"assignment_selection":null,"collaboration":null,"course_assignments_menu":null,"course_home_sub_navigation":null,"course_navigation":null,"course_settings_sub_navigation":null,"discussion_topic_menu":null,"editor_button":null,"file_menu":null,"global_navigation":null,"homework_submission":{"enabled":"true","selection_height":600,"selection_width":800,"text":"CK-12 Practice","url":"https://www.ck12.org/auth/launch/lti/ltiApp","label":"CK-12 Practice"},"link_selection":null,"migration_selection":null,"module_menu":null,"post_grades":null,"quiz_menu":null,"resource_selection":{"enabled":"true","selection_height":600,"selection_width":800,"text":"CK-12 Practice","url":"https://www.ck12.org/auth/launch/lti/ltiApp","label":"CK-12 Practice"},"tool_configuration":null,"user_navigation":null,"wiki_page_menu":null,"not_selectable":false},{"id":"1","domain":"google-drive-lti-iad-prod.instructure.com","url":"https://google-drive-lti-iad-prod.instructure.com/lti/course-navigation","consumer_key":"ef8777eb-5f94-47a5-ada9-cbc92cc0d33e","name":"Google Apps","description":"Allows you to pull in documents from Google Drive to Canvas","created_at":"2018-07-02T20:32:14Z","updated_at":"2018-07-02T20:32:14Z","privacy_level":"name_only","custom_fields":{"account_id":"$Canvas.account.id","assignment_title":"$Canvas.assignment.title","base_url":"$Canvas.api.baseUrl","collaboration_members_url":"$Canvas.api.collaborationMembers.url","domain":"$Canvas.api.domain","group_context_ids":"$Canvas.group.contextIds","masquerading_user_id":"$Canvas.masqueradingUser.userId","membership_service_url":"$ToolProxyBinding.memberships.url","previous_context_ids":"$Canvas.course.previousContextIds","previous_context_ids_recursive":"$Canvas.course.previousContextIds.recursive","time_zone":"$Person.address.timezone","user_id":"$Canvas.user.id"},"workflow_state":"name_only","vendor_help_link":null,"account_navigation":null,"similarity_detection":null,"assignment_menu":null,"assignment_selection":{"message_type":"ContentItemSelectionRequest","text":"Google Docs Cloud Assignment","url":"https://google-drive-lti-iad-prod.instructure.com/lti/cloud-template-selection","label":"Google Docs Cloud Assignment","selection_width":800,"selection_height":400,"icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png"},"collaboration":{"canvas_icon_class":"icon-lti","icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png","message_type":"ContentItemSelectionRequest","text":"Google Drive","url":"https://google-drive-lti-iad-prod.instructure.com/lti/collaboration-content-selection","label":"Google Drive","selection_width":800,"selection_height":400},"course_assignments_menu":null,"course_home_sub_navigation":null,"course_navigation":{"text":"Google Drive","url":"https://google-drive-lti-iad-prod.instructure.com/lti/course-navigation","label":"Google Drive","selection_width":800,"selection_height":400,"icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png"},"course_settings_sub_navigation":null,"discussion_topic_menu":null,"editor_button":{"icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png","message_type":"ContentItemSelectionRequest","selection_height":600,"selection_width":700,"url":"https://google-drive-lti-iad-prod.instructure.com/lti/rce-content-selection","label":"Google Apps"},"file_menu":null,"global_navigation":null,"homework_submission":{"canvas_icon_class":"icon-lti","icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png","message_type":"ContentItemSelectionRequest","text":"Google Drive","url":"https://google-drive-lti-iad-prod.instructure.com/lti/homework-content-selection","label":"Google Drive","selection_width":800,"selection_height":400},"link_selection":{"enabled":"true","message_type":"ContentItemSelectionRequest","selection_height":600,"selection_width":700,"text":"Google Drive","url":"https://google-drive-lti-iad-prod.instructure.com/lti/module-content-selection","label":"Google Drive","icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png"},"migration_selection":null,"module_menu":null,"post_grades":null,"quiz_menu":null,"resource_selection":null,"tool_configuration":null,"user_navigation":null,"wiki_page_menu":null,"icon_url":"https://google-drive-lti-iad-prod.instructure.com/assets/google_drive_icon-ba12a17e3e3d7f70f910b17f1b4c0500ff0298ad087a93a6c133ca623c40f0f8.png","not_selectable":false}],"EULA_URL":null,"CONDITIONAL_RELEASE_SERVICE_ENABLED":true,"CONDITIONAL_RELEASE_ENV":{"jwt":"ZXlKaGJHY2lPaUprYVhJaUxDSmxibU1pT2lKQk1qVTJSME5OSW4wLi5fRnRiTDc2SThLN01HTmpCLkY4djJWMlFMVk84dk53dFpTUmpKRlpza29PS29VUWg0QzQ5QVRGRjlsNVRqc2x2TTllMzJ1U3VzWWNvUUI0dnhxeXhoVVlPNWNrNTZQS2FnNFNHdzd5blJHazRmNTFlSFBubVN4VFpDT25SQk1Ya3VWSFJKM1NNc2R2ZjQyTV9CWGwtNXdxeUdpZXpOOHE3QlNNeTBXNWxtQTZicGUyUFpzTHRHNXNhWUU0ZVdOZWhBVGhtVlllVDdTNkUxZkVjMDgwN21rRF9wQ2Z1V3JRMXFMbkF5d3ZFNWhFcWtnNV82TDhDNWxTalBMY3BLV3FveEZrQlRKZGVMVGd0dllUX3ZYakxSRThYUjJCcmlxbWtFTU9xNFc3R05pQ2JEM0l4aWw2SjVtbi00VXIyUVFOc1VEVnl4NUNSVXQ3OXJ3RndKZ210ckNwbkVic0JiMjMxa19SUVJZdEh3WkJ5RXRET0M2b3pVa3lpT0U0U1B4SkY2Nm81UFJBYXY2QTV0NDVIdnltMUJmeFR3bTYzSW9LazRPWE8xcFBDaFhrVkFESFZaZXp0S1BDcnZQTDlOeUZJbDB4QjEtbWxheEJHZERRNld3aFZxX1RUNUhubUptbU9vdjZuYlVpV0hxdG02elA1SWNkekZYeVdGQ01sZWYyTncxU2xCbVp0TzRJTThBdU4tZzNxNVEtUnIteTd4OHlJUG5jUFFOQXloeHB3Z181RUNRbXZuSDZlMEtyU3hvQW1ZdFI2cUpQbnJGVVRHX1hWbTNrYjUwNzFCZTlFdU1xY2hka2hjTVdwMWxwQkFzZ20zMnV2c2pXSWp1cEJUdjhxTVRRX25vTXRwX1c4WWZlUFltRHlWeTdxUElpRDF0bl80cVFzRkxOVHN0THVMWnl6ck9LcWFhcXhpTXlHQ1VydTRoNFE0bnBrVkF3MWhEWkZ2TWN0SDdzOU9OdjFDOTlyMXZVbWtHN1JpOTZNMUlTQUkyN3FqZ1hEUDBocU52RThfX0taM0Iwbm9ZSkdWVVpjdWdQWHpuZENwNVpkMG5FMkpIM1N4anhrZldVUGRjLWI1Nzh6cURidTV2enhfSjlOTFlSUEhPSHhqWlhISVBMTm0zN25zOHZ6YXJIaDdORUNfZ1Q4TlhlQkllSy01QmNMd1ItZ0YweVhZQW1uelFhcW0ybkJBVFFFa1VZckJwWXc4ejBqbjg0WXBZdHl4UFZMXzhpblg1M1lQVjRUaUI4aTljY1lnRWM4WmcxUDd0OTBzMW5sOXZLWGRFMld2ZFdpTGk3VmdySkY5NG5sSGItM29FMGlfbVRuMnh6aXd5elhNRFpkb014YnpZLWJYdHh0b0ZQTzdZNWNBdEo2S1kteVJkVWFfUndmc2xjLU1CaC1YZmswWE1uNXJBY2xBX3hFUzM1a0tFTzJZTjJzQ0FfaG8wbnRwbmdXRXRPVV9sd2wzbWhjYzBoZjRJT1Nqd0FDRHpyTjJtc1NCYU9WOWlZXzB5dVdheF9FUVZRUk04MjFWQ21mSUxnVUQ1RGJmVG5RRzh5MElkSUhhLXkwT3B6cHduaXV3Zlg4SmdqdjZzODBvSnhXS2ZVeVJMWVNFN1hOQTlzWThXQThhaVNndHhMTmJHQ2hCRGtQdG54YkcwQjd4OWZVUVV3Q05RMV9JNXd0MzljRldLUDdjMjRNUFpOSnNiWHl3ejhaeldtQ3gwaUh0V2FfRy0xTG5jOWlxd0JVelF5T21TclEycFdvcDhrejZaZFNXZ3B4dERfbTkyU1RYOVRZY0QxUXFxdTRSNl9PUFBjaDdoS2RzTERlTWNqZU5CVnl2SkxwZWtNV2Z6SUNjVGsxaW1zQ0lENnR6WTZHZ1ZPc2tqN1RUcVBpaVFTdlcxVkdDSlVvVkdCZjNGNGQwOUtULXFobUpESENwd3BOdmRyb0JSWG9JLU9oc1FVTEE2cUxKdmxFQ0xjNjJpYjZ2WTNLZVpSY1Jqd1lFOWZnNVBFNUdEenNtamRWN0t3NExMeTJ0aklhWWhlbkRZSmFFZmU1UE03NWZxeG9rSElScUp5VmItNjRGaHBnRlotVzctYU1GSFllRXlISWJXMEI4QnZHMGttUUZhSjVzTElGZFhsRU82SlZGMWYwQnVmamNueEtKQ2dyUm1maG9ZcFhoS1pKaEVxZjdwRWlhQ2VsaGRpbU5qMXEzcDhNTEdyQVdnRnlCaGJfVVFGNUt6M09pWUNlT0FPT3BlTzBzalhHbGhrRTMtMzhPR08wanI0MXFrbklBZFAwQURQczBmR0VYZFhlOFdsR21zRGVYT29Fek1adU1iWDUxcHllS3RFV1lUTEs1dkgtNU1pcmlMQ2tvU1Q5dlRxRXVvR2dfNWlzRzBoVVJkRlgwcndLQ0t1UTJRaFNqb2EzNGxvZmRtb19OWnJsdm15S05HcHhOYS1ORG9sLVR0YXNEeUh3S3FRNkp4M3FmOEtwa1lvU3U4ZW1sbXBsaHUxM1ZmS0FsWG1Rb0pVanBLLXc3VzhHWHVVOXZFQ2haTGxWVHl2VUpnWmNseHJzQlo4VG1CZkl5cEZteDJQZ2wtaUl2dWNXUzZqMEdxMmdwZng3OGZZRVl4bkVGRlU3Y2NKSUFnWmtaQjV0ZUxHLUhmd2pBQ3gwZFUzQVF0QUxvVTVLOW03YTI5VTdVdkZJd1NTUnNiMllobWtWTXRfV0VnMGhrUWRLQzlyVS12TEdpejhyanZmb3RRSXJNdmpkc1Jsc00tN0pLOUFKTHh2NFBRVEJMWlpYN3hESjY1VndZOUc4cFpNVTBQRTlPb3hicUVwc1NfQjZnbGV5TEhrVEIzZ2VBOG14ck5BVzd4YlZBQ1BmTS0wV1d6MEFfSVA1c3gyTjYwQTJpRW15QzNJcGdfSHg1aUthemJkU2diWEFtLkhqd25uU0JBMDlXOFBtd016dTdzRUE=","assignment":{"id":"1117","title":"Slope, Midpoint, and Distance Drag and Drop","description":"\u003ch3\u003eDirections\u003c/h3\u003e\r\n\u003cp\u003eMake a copy of the Google draw file (link below).  In your copy, change the name to \"Your Name SOL G.3a Drag and Drop\".  For example, your title should be something like \"Ms. Cooper SOL G.3a Drag and Drop\" or \"John Wayne SOL G.3a Drag and Drop\".\u003c/p\u003e\r\n\u003cp\u003eThen, complete the drag and drop\u003c/p\u003e\r\n\u003cp\u003eYou will need to show work, and you will need to turn in a piece of work paper to me.\u003c/p\u003e\r\n\u003ch3\u003eTo Submit\u003c/h3\u003e\r\n\u003cp\u003eShare your completed Google draw slide with me by clicking \"Share\" in the top right corner and copy/pasting the link to this assignment.\u003c/p\u003e\r\n\u003cp\u003eYou will also need to turn in your work paper!\u003c/p\u003e","points_possible":100.0,"grading_type":"percent","submission_types":"online_url","grading_scheme":null},"stats_url":"https://conditional-release-iad-prod.instructure.com/stats","locale":"en","editor_url":"https://conditional-release-iad-prod.instructure.com/javascripts/generated/conditional_release_editor.bundle.js","base_url":"https://conditional-release-iad-prod.instructure.com/","context_id":"104","rule":null},"SUBMIT_ASSIGNMENT":{"ALLOWED_EXTENSIONS":[],"ID":1117,"GROUP_ID_FOR_USER":null},"badge_counts":{"submissions":2},"notices":[]};
</script>

<script src="https://du11hjcvx0uqb.cloudfront.net/dist/webpack-production/navigation_header.bundle-21a7d3ba13.js" defer="defer"></script>


</div> <!-- #application -->
</body>
</html>
