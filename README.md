<!DOCTYPE html>
<html>
<head>
 
<title>{Title} {block:TagPage}/ #{Tag}{/block:TagPage}{block:PostSummary}: {PostSummary}{/block:PostSummary}</title>
 
<link rel="shortcut icon" href="{Favicon}">
<link rel="alternate" type="application/rss+xml" href="{RSS}">
{block:Description}<meta name="description" content="{MetaDescription}"/>{/block:Description}
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
 
<!--
  THEME BY: JUU MENDES 
  CODE BASE BY: SEYCHE
-->
 
<title>{Title}</title>
 
<link rel="alternate" type="application/rss+xml" href="{RSS}">
 
{block:Description}<meta name="description" content="{MetaDescription}" />{/block:Description}
 
 
<!---------------------------------------------------------- FONT AWESOME -->
 
<link rel="stylesheet" href=
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.9.0/css/all.css">
</link>
 
<!--------------------------------------------------------------- JQUERY -->
 
<script src="https://ajax.googleapis.com/ajax/libs/jquery/3.2.1/jquery.min.js"></script>
 
<!--------------------------------------------------------------- FAVICON -->
 
<link rel="icon" href="{image:sidebar image}" type="image/gif" />
 
<!-------------------------------------------------------- SCROLL TO TOP -->
<div style="float:right;bottom: 0px; margin-top:15px; margin-right:3px;"><a href="https://tumblings.net/post/44212620655/tumblreffects" target="_blank"></a></div>
 
<script type="text/javascript" src="https://static.tumblr.com/ikeq9mi/DfYl6o46t/scrolltotop.min.js"></script>
 
 
<div style="position:fixed;bottom:10px;right:10px;z-index:1;">
<a href="javascript:;" id="scrollToTop" rel="nofollow" title="Go to Top" alt="Go to Top"> <i class="fa fa-chevron-up" style="color:{color:accent 4}";></i></a></div>
 
<!-------------------------------------------------------- TOOLTIPS -->
 
<script src="https://static.tumblr.com/uopakca/GVcnvdwbq/jquery.style-my-tooltips.js"></script>
<script>
(function($){
$(document).ready(function(){
$("a[title]").style_my_tooltips({
tip_follows_cursor:true,
tip_delay_time:90,
tip_fade_speed:700,
attribute:"title"
});
});
})(jQuery);
</script>
 
<head>
 
 
<!---------------------------------------------------------------- IMAGES -->
 <meta name="image:icon" content=""/>
<meta name="image:sidebar image" content=""/>
 
<!---------------------------------------------------------------- COLORS -->
<meta name="color:Background" content="#191414"/>
<meta name="color:Post" content="#191414"/>
<meta name="color:Text" content="#191414"/>
<meta name="color:Link" content="#191414"/>
 
<!-------------------------------------------------------- FONT SELECTION -->
<meta name="font:title" content="Favorit"/>
<meta name="font:text" content="Favorit"/>
 
<!----------------------------------------------------------------- TOGGLE-->
 
<meta name="if:sidebar image" content="0" />
 
<!------------------------------------------------------------------ TEXT -->
<meta name="text:link 1" content="ask" />
<meta name="text:link 1 url" content="/ask" />
<meta name="text:link 2" content="archive" />
<meta name="text:link 2 url" content="/archive" />
<meta name="text:link 3" content="" />
<meta name="text:link 3 url" content="" />
<meta name="text:link 4" content="" />
<meta name="text:link 4 url" content="" />
<meta name="text:SCM music player" content="" />
 
 
 
<style type="text/css">
 
/*----------------------------------------------------------- SCROLLBAR --*/
 
 
::-webkit-scrollbar {
 
width: 10px;
background: {color:accent 1};
}
 
::-webkit-scrollbar-track {
 
background: none;
}
 
 
::-webkit-scrollbar-thumb {
 
border-radius: 15px;
background:{color:accent 4};
 
}
 
::-webkit-scrollbar-thumb:horizontal {
 
background:{color:accent 4};
 
}
 
/*---------------------------------------------------------------- MAIN --*/
 
 
body{
background-image:url('{image:background}');
background-attachment: fixed;
background-repeat: repeat;
background-color: {color:accent 1};
margin-left:0px;
margin-top:0px;
color:{color:text};
font-family:{font:text};
font-size:12px;
line-height:25px;
letter-spacing:1px;
 
}
 
a{
text-decoration:none;
color:{color:links};
transition:0.4;
}
 
a:hover {
color:{color:links hover};
 
}
 
b {
color:{color:bold};
}
 
i {
color:{color:italics};
}
 
 
li {
margin-left: -15px;
list-style-type: none;
}
 
li:before {
 
content: "•";
font-family: 'Font Awesome\ 5 Free';
font-weight: 900;
font-size:15px;
margin-left: -20px;
margin-right: 8px;
}
 
blockquote {
padding-left:10px;
border-left:1px dashed {color:blockquote};
margin-left:10px;
}
 
 
.content {
 
width:80%;
max-width:800px;
margin:3em auto;
display:grid;
grid-template-columns:1fr 2fr;
grid-gap:4em;
background:transparent;
margin-top:-30px;
 
}
 
.title {
font-size: 30px;
text-align: center;
padding:10px;
margin-bottom:10px;
color: {color:accent 3};
font-family:{font:title};
line-height:35px;
}
 
.title a {
font-size: 30px;
text-align: center;
padding:10px;
margin-bottom:10px;
color: {color:accent 3};
font-family:{font:title};
 
 
}
 
 
 
/*---------------------------------------------------------------- POSTS --*/
 
#postmargin{
 
padding-top: 10px;
width:400px;
margin-top:120px;
}
 
.posts{
 
background-color:{color:accent 2};
width:450px;
padding:40px 30px 40px 30px;
overflow: hidden;
border-radius:10px;
margin-bottom:50px;
margin-left:70%;
 
}
 
 
.posts img:not(.lightbox-image){
max-width:100%;
text-align:center;
border-radius:10px;
}
 
 
.avatar img {
 
border-radius:100px!important;
width:30px!important;
height:30px!important;
margin-top:10px;
}
 
 
.avatar-box {
 
display:flex;
flex-direction: row;
 
}
 
.username {
margin-left:10px;
margin-top:13px;
}
 
 
 
/*-------------------------------------------------------------- SIDEBAR --*/
 
.sidebar {
margin-left:-50px;
background:transparent;
height:100vh;
 
}
 
.sticky {
position:fixed;
top:0;
margin-top:90px;
 
}
 
.desc-box {
 
width:200px;
padding:30px 20px 30px 20px;
height:auto;
margin-top:10px;
background:{color:accent 2};
border-radius:10px;
text-align:center;
}
 
 
 
{block:ifsidebarimage}
.sidebar-image {
 
 
width: 90px!important;
height: 90px!important;
border-radius:100px;
margin-bottom:20px;
 
}
{/block:ifsidebarimage}
 
 
 
 
 
 
 
.link-box {
 
width:200px;
padding:20px;
height:auto;
margin-top:20px;
background:transparent;
border-radius:10px;
}
 
.link-box a {
 
padding:10px 12px 10px 12px;
background:{color:accent 2};
border-radius:100px;
transition:0.4s;
margin-right:5px;
font-size:15px;
 
}
 
.link-box a:hover {
 
background:{color:sidebar links hover};
transition:0.4s;
}
 
.link-box i {
 
color:{color:accent 3};
}
 
 
 
 
 
 
.pagination-box {
 
width:200px;
padding:20px;
height:auto;
margin-top:-6px;
background:transparent;
border-radius:10px;
font-size:30px;
 
}
 
.pagination {
color:#000;
display:flex;
flex-direction: row;
justify-content: space-around;
}
 
.pagination a {
 
padding:10px 12px 10px 12px;
background:{color:accent 2};
transition:0.4s;
margin-right:5px;
font-size:15px;
border-radius:6px;
}
 
 
.pagination a:hover {
 
background:{color:sidebar links hover};
transition:0.4s;
}
 
.pagination i {
 
color:{color:accent 3};
}
 
 
/*----------------------------------------------------------------- TAGS --*/
 
 
.tags-container {
 
display:flex;
justify-content:left;
align-items:left;
flex-direction:row;
-webkit-transition: all 0.7s ease-in-out;
transition: all 0.7s ease-in-out;
-moz-transition: all 0.7s ease-in-out;
-o-transition: all 0.7s ease-in-out;
position:relative;
 
}
 
 
.tags a {
 
background:{color:accent 1};
color:{color:text};
padding:7px;
padding-left: 10px;
padding-right:10px;
border-radius:6px;
margin-right:5px;
-webkit-transition: all 0.5s ease-in-out;
transition: all 0.5s ease-in-out;
-moz-transition: all 0.5s ease-in-out;
-o-transition: all 0.5s ease-in-out;
box-shadow: 0px 5px 30px -9px rgba(0,0,0,0.12);
}
 
 
.tags a:hover {
 
background:{color:accent 3};
color:{color:accent 1};
padding:8px;
border-radius:7px;
padding-left: 12px;
padding-right:12px;
-webkit-transition: all 0.5s ease-in-out;
transition: all 0.5s ease-in-out;
-moz-transition: all 0.5s ease-in-out;
-o-transition: all 0.5s ease-in-out;
 
}
 
 
.tags {
 
height:0px;
line-height:330%;
text-align:left;
font-size:12px;
opacity:0;
-webkit-transition: all 0.5s ease-in-out;
transition: all 0.5s ease-in-out;
-moz-transition: all 0.5s ease-in-out;
-o-transition: all 0.5s ease-in-out;
margin-top:-60px;
 
}
 
 
.posts:hover .tags {
 
opacity:1;
-webkit-transition: all 0.7s ease-in-out;
transition: all 0.7s ease-in-out;
-moz-transition: all 0.7s ease-in-out;
-o-transition: all 0.7s ease-in-out;
margin-bottom:0px;
float:left;
padding:5px;
width:450px;
margin-top:20px;
height:auto;
}
 
 
/*--------------------------------------------------------------- NOTES --*/
 
.notes-container {
 
margin: 0;
padding: 0;
position:relative;
width:490px;
margin-left:280px;
border-radius:7px;
background:{color:accent 2};
height:400px;
overflow:auto;
padding:15px;
margin-top:auto;
 
}
 
 
.notes li:before {
 
margin-left: 0px;
float:left;
content: "";
font-family: 'Font Awesome\ 5 Free';
font-size:15px;
}
 
 
.notes li {
 
list-style-type: none;
padding:5px;
margin-left:-20px;
width: 100%;
float: left;
text-align:left;
 
}
 
 
 
.notes img {
 
margin-right: 15px;
margin-left: 15px;
float: left;
width: 20px;
height: 20px;
border-radius: 100px;
}
 
 
 
/*------------------------------------------------------ ASK & QUESTIONS --*/
 
 
.askerbg {
 
padding: 0px;
border-radius: 100px;
 
}
 
.askerbg img {
 
border-radius:100px!important;
 
}
 
 
 
.question {
 
width: auto;
margin-top: 10px;
margin-bottom:20px;
color:{color:text 2};
padding: 10px;
border-radius: 7px;
background:{color:accent 1};
 
}
 
/*----------------------------------------------------------- SEARCH BAR --*/
 
.search {
 
margin-top:20px;
 
}
 
 
.sfm input {
width:150px;
background-color: #f5f5f5;
font-size: 11px;
border: 0px;
text-transform: uppercase;
margin-top: 0px;
color: #999;
letter-spacing: 1px;
padding: 4px 8px;
font-family: {font:text};
border-radius: 20px;
padding: 8px 20px 8px 20px;
border-radius: 70px;
color:{color:text 2};
transition: 0.4s;
background:{color:accent 1};
 
}
 
 
/*---------------------------------------------------------------- QUOTE --*/
 
#quote{
font-size:20px;
margin-bottom:20px;
margin-top:20px;
font-weight:Bold;
}
 
#link{
text-align:center;
font-size:15px;
}
 
/*------------------------------------------------------------ PERMALINK --*/
 
.permalink
{
 
display:flex;
flex-direction: row;
justify-content: space-around;
}
 
.permalink-box {
width:100%;
margin-top:30px;
padding-top:10px;
padding-bottom:10px;
height:auto;
text-align:center;
background:{color:accent 1};
border-radius:100px;
 
}
 
/*----------------------------------------------------------------- CHAT --*/
 
.chatbox {
margin-top:-30px;
margin-bottom:180px;
 
}
 
.answer span,.convo i {
 
 
border-radius:1em;
padding:.5em 10px;
max-width:75%;
position:relative;
margin-bottom:10px;
 
 
}
 
.answer .them,.user_1,.user_3,.user_5,.user_7,.user_9,.user_11 {
 
color:{color:text 2};
border-radius: 7px;
background:{color:accent 1};
float:left;
height:auto;
left:3px;
}
 
 
.me::after,.user_1::after,.user_3::after,.user_5::after,.user_7::after,.user_9::after,.user_11::after {
 
 
content:' ';
position:absolute;
border:8px solid {color:accent 1};
top:1em;
right:99%;
margin-top:-7px;
clip-path: polygon(100% 11%, 35% 45%, 100% 85%);
 
 
}
 
 
.answer .me,.user_2,.user_4,.user_6,.user_8,.user_10,.user_12 {
color:{color:text 2};
border-radius: 7px;
background:{color:accent 1};
float:right;
right:3px;
height:auto;
}
 
 
.them::after,.user_2::after,.user_4::after,.user_6::after,.user_8::after,.user_10::after,.user_12::after {
content:' ';
position:absolute;
border:8px solid {color:accent 1};
top:1em;
left:99%;
clip-path: polygon(0 8%, 0 86%, 55% 48%);
margin-top:-7px;
}
 
 
/*--------------------------------------------------- LIKE/REBLOG BUTTON --*/
 
.like svg path, .reblog svg path {
 
fill:{color:links};
transition: 0.4s;
}
 
 
.reblog {
float:right;
margin-left:40px;
margin-top:0px;
 
}
 
.reblog a {
color:{color:links};
}
 
.reblog a:hover {
 
color:{color:links hover};
transition: 0.4s;
 
}
 
.like {
 
float:left;
margin-right:20px;
position: relative;
margin-top:2px;
 
}
 
/* Position like button above your custom one */
.like .like_button {
position: absolute;
top: 0;
opacity: 0;
 
}
 
/* Keep like functionality active */
.like .like_button.liked {
opacity: 1;
}
 
/*---------------------------------------------------------- AUDIO POSTS --*/
 
.playbutton-container {
 
position:relative;
margin-left:20px;
z-index:9;
overflow:hidden;
padding:20px;
text-align: center;
opacity: .8;
padding:20px;
width:60px;
height:60px;
}
 
.playbutton {
 
border-radius:100px;
width:30px;
height:30px;
margin-top:50px;
margin-left:5px;
 
}
 
.playbutton-bg {
 
margin-top:-45px;
margin-left:30px;
position: absolute;
width: 40px;
height: 40px;
background-color: #000;
padding: 10px;
border-radius: 40px;
opacity: .7;
z-index:1;
 
}
 
 
.albumart img {
 
position:relative;
margin-top:-75px;
margin-left:0px
height:120px!important;
width:120px!important;
border-radius:100px!important;
 
}
 
.trackinfo {
 
padding: 10px 20px 10px 20px;
margin-bottom:10px;
color:{color:accent 3};
top:-10px;
position:relative;
margin-left:140px;
height:auto;
margin-top:-120px;
border-radius:6px;
text-align:left;
background:{color:accent 1};
 
}
 
.trackname {
 
position:relative;
font-size:12px;
text-transform:uppercase;
font-weight: bold;
 
 
}
 
.artist {
 
font-size:11px;
text-transform:uppercase;
 
}
 
.album {
 
font-style: italic;
font-size:11px;
 
}
 
 
/*------------------------------------------------------------ TOOL TIPS --*/
 
#s-m-t-tooltip {
 
margin-left:15px;
margin-top:-21px;
letter-spacing:0px;
font-family:{font:text};
text-transform:auto;
font-size:12px;
color: {color:accent 1};
padding: 3px;
z-index:99999999999999999999999;
transition:all 0.4s;
background:{color:accent 3};
padding: 5px 10px 5px 10px;
border-radius: 100px;
 
}
 
/*------------------------------------------------------ TUMBLR CONTROLS --*/
 
 
iframe#tumblr_controls, .iframe-controls--desktop {
 
 
top:0px!important; /* or whatever you want */
right:-30px!important; /* or whatever you want */
transform:scale(0.8,0.8); /* or whatever you want */
-webkit-filter:invert(100%); filter:invert(100%);
opacity:0!important;
-webkit-backface-visibility:hidden;
padding:10px 40px 10px 10px;
-webkit-transition:opacity .3s ease-out;
transition:opacity .3s ease-out;
 
 
}
 
 
#tumblr_controls:hover, .tmblr-iframe:hover {
 
opacity:.5!important;
}
 
 
/*-------------------------------------------------------------- CREDIT --*/
 
 
.credit {
 
position:fixed;
bottom:18px;
right:25px;
font-size: 20px;
 
}
 
.credit a {
color:{color:accent 1};
}
 
/*-------------------------------------------------------- SCROLL TO TOP --*/
 
#scrollToTop:link,
#scrollToTop:visited {
 
display: none;
position: fixed;
bottom:48px;
right:17px;
font-size: 20px;
padding: 13px;
color:{color:accent 4};
 
}
 
/*--------------------------------------------------------------- FOOTER --*/
 
.footer {
 
height:100px;
}
 
 
/*------------------------------------------------- FIX TEXT POST IMAGES --*/
 
iframe, img, embed, object, video:not(.lightbox-image) {
max-width: 100%;
}
 
 
img:not(.lightbox-image) {
height: auto;
width: auto;
}
 
 
/*------------------------------------------- STYLE/HEAD END & BODY START--*/
 
 
</style></head><body>
 
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
 
 
<div class="content">
 
 
<!--------------------------------------------------------- SIDEBAR START -->
 
<div class="sidebar"><!-- sidebar wrapper -->
<div class="sticky">
<div class="desc-box">
 
<div class="title">
<a href="/">{Title}</a>
</div>
 
{block:ifsidebarimage}
<center><img class="sidebar-image" src="{image:Sidebar image}"/></center> {block:ifsidebarimage}
 
{description}
 
<!--------------------------------------------------------------- SEARCH -->
 
<div class="search">
 
<form onsubmit="return tagSearch(this)" class="sfm">
 
<input type="text" name="tag" placeholder="Search..."value="{SearchQuery}" id="sf" onfocus="if (this.value == '{SearchQuery}') {this.value=''}" onblur="if (this.value == '') {this.value='{SearchQuery}'}" />
 
</form>
 
</div>
 
</div><!--desc box-->
 
<!---------------------------------------------------------------- LINKS -->
 
<div class="link-box">
<center>
 
{block:iflink1url} <a href="{text:link 1 url}" title="{text:link 1}"> <i class="fab fa-canadian-maple-leaf"></i></a>{block:iflink1url}
{block:iflink2url} <a href="{text:link 2 url}" title="{text:link 2}"> <i class="fab fa-pagelines"></i></a>{block:iflink2url}
{block:iflink3url} <a href="{text:link 3 url}" title="{text:link 3}"> <i class="fas fa-seedling"></i></a> {block:iflink3url}
{block:iflink4url} <a href="{text:link 4 url}" title="{text:link 4}"> <i class="fas fa-tree"></i></a>{block:iflink4url}
 
</center>
</div><!-- link box-->
 
<!------------------------------------------------------------ PAGINATION -->
 
<div class="pagination-box">
<center>
<div class="pagination">
{block:PreviousPage}
<div class="previous-button"><a href="{PreviousPage}"> <i class="fas fa-angle-left"></i> </a></div>
{/block:PreviousPage}
 
{block:NextPage}
<div class="next-button"><a href="{NextPage}"> <i class="fas fa-angle-right"></i> </a></div>
{/block:NextPage}
</div>
<center>
</div><!-- pagination box-->
 
 
</div> <!-- sticky -->
 
 
 
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
 
 
 
<!----------------------------------------------------------- POSTS START -->
 
<div id="postmargin">
{block:Posts}
<div class="posts">
 
 
 
<!------------------------------------------------------------ TEXT POSTS -->
 
 
{block:Text}
 
 
<div id="link">
{block:Title}
<div class="title">{Title}</div>
{/block:Title}
</div>
 
{block:Caption}
 
<div class="caption">
 
{block:NotReblog}
{Caption}
{/block:NotReblog}
 
{block:RebloggedFrom}{block:Reblogs}
<div class="comment_container">
<div class="commenter">
<div class="avatar-box">
<div class="avatar">
 
<img src="{PortraitURL-64}" />
 
 
</div>
 
<span>
{block:HasPermalink}
<a href="{Permalink}">
{/block:HasPermalink}
<div class="username">{Username}</div>
{block:HasPermalink}</a>
{/block:HasPermalink}
 
</div>
</span>
</div>
 
<blockquote>
<div class="comment">{Body}</div>
</blockquote>
</div>
{/block:Reblogs}{/block:RebloggedFrom}
</div>
{/block:Caption}
 
{Body}
{/block:Text}
 
 
 
<!----------------------------------------------------------------- PHOTO -->
 
 
 
{block:Photo}
 
<center>
{LinkOpenTag}
<img src="{PhotoURL-500}" width="500">
{LinkCloseTag}
</center>
 
 
{block:Caption}
 
<div class="caption">
 
{block:NotReblog}
{Caption}
{/block:NotReblog}
 
{block:RebloggedFrom}{block:Reblogs}
<div class="comment_container">
<div class="commenter">
<div class="avatar-box">
<div class="avatar">
 
<img src="{PortraitURL-64}" />
</div>
 
<span>
{block:HasPermalink}
<a href="{Permalink}">
{/block:HasPermalink}
<div class="username">{Username}</div>
{block:HasPermalink}</a>
{/block:HasPermalink}
 
</div>
</span>
</div>
 
<blockquote>
<div class="comment">{Body}</div>
</blockquote>
</div>
{/block:Reblogs}{/block:RebloggedFrom}
</div>
{/block:Caption}
 
 
 
{/block:Photo}
 
 
 
 
 
 
 
<!-------------------------------------------------------------- PHOTOSET -->
 
 
 
{block:Photoset}
 
 
<center>
{Photoset-400}
</center>
 
{block:Caption}
 
<div class="caption">
 
{block:NotReblog}
{Caption}
{/block:NotReblog}
 
{block:RebloggedFrom}{block:Reblogs}
<div class="comment_container">
<div class="commenter">
<div class="avatar-box">
<div class="avatar">
 
<img src="{PortraitURL-64}" />
 
 
</div>
 
<span>
{block:HasPermalink}
<a href="{Permalink}">
{/block:HasPermalink}
<div class="username">{Username}</div>
{block:HasPermalink}</a>
{/block:HasPermalink}
 
</div>
</span>
</div>
 
<blockquote>
<div class="comment">{Body}</div>
</blockquote>
</div>
{/block:Reblogs}{/block:RebloggedFrom}
</div>
{/block:Caption}
 
 
{/block:Photoset}
 
 
 
<!---------------------------------------------------------------- QUOTES -->
 
{block:Quote}
 
<div id="quote">
<i class="fas fa-quote-left" style="font-size:30px; color:{color:text}"></i>
{Quote}
</div>
{block:Source}— {Source}{/block:Source}
 
{/block:Quote}
 
<!----------------------------------------------------------------- LINKS -->
 
{block:Link}
 
<div id="link"><a href="{URL}" {Target}>{Name}</a></div>
 
{block:Description}{Description}{/block:Description}
 
{/block:Link}
 
<!----------------------------------------------------------------- CHAT -->
 
 
{block:Chat}
 
<div class="chatbox">
 
{block:Title}
<h1>{Title}</h1>{/block:Title}<br>
 
<ul class="convo">
 
{block:Lines}
<i class="line_{Alt} user_{UserNumber}">{block:Label}<span class="label"><strong>{Label}</strong></span>{/block:Label}{Line}</i>
{/block:Lines}
 
</ul>
 
</div>
 
{/block:Chat}
 
 
 
<!------------------------------------------------------------ AUDIO POSTS-->
 
 
{block:Audio}
{block:AudioPlayer}
 
<div class="playbutton-container">
<div class="playbutton">
{AudioPlayerBlack}
</div>
</div>
 
<div class="playbutton-bg"></div>
 
{block:AlbumArt}
<div class="albumart"><img src="{AlbumArtURL}"></div>
{/block:AlbumArt}
 
<div class="trackinfo">
 
<div class="trackname">
{block:TrackName}{TrackName}{/block:TrackName}
</div>
<div class="artist">
{block:Artist}{Artist}{/block:Artist}
</div>
<div class="album">
{block:Album}{Album}{/block:Album}
</div>
 
</div>
 
{block:Caption}
 
<div class="caption">
 
{block:NotReblog}
{Caption}
{/block:NotReblog}
 
{block:RebloggedFrom}{block:Reblogs}
<div class="comment_container">
<div class="commenter">
<div class="avatar-box">
<div class="avatar">
 
<img src="{PortraitURL-64}" />
 
 
</div>
 
<span>
{block:HasPermalink}
<a href="{Permalink}">
{/block:HasPermalink}
<div class="username">{Username}</div>
{block:HasPermalink}</a>
{/block:HasPermalink}
 
</div>
</span>
</div>
 
<blockquote>
<div class="comment">{Body}</div>
</blockquote>
</div>
{/block:Reblogs}{/block:RebloggedFrom}
</div>
{/block:Caption}
 
{/block:AudioPlayer}
{/block:Audio}
 
 
 
<!---------------------------------------------------------------- VIDEOS -->
 
 
 
{block:Video}
 
{Video-500}
 
 
{block:Caption}
 
<div class="caption">
 
{block:NotReblog}
{Caption}
{/block:NotReblog}
 
{block:RebloggedFrom}{block:Reblogs}
<div class="comment_container">
<div class="commenter">
<div class="avatar-box">
<div class="avatar">
 
<img src="{PortraitURL-64}" />
 
 
</div>
 
<span>
{block:HasPermalink}
<a href="{Permalink}">
{/block:HasPermalink}
<div class="username">{Username}</div>
{block:HasPermalink}</a>
{/block:HasPermalink}
 
</div>
</span>
</div>
 
<blockquote>
<div class="comment">{Body}</div>
</blockquote>
</div>
{/block:Reblogs}{/block:RebloggedFrom}
</div>
{/block:Caption}
 
 
{/block:Video}
 
 
 
<!----------------------------------------------------------------- ASKS -->
 
 
{block:Answer}
<table style="padding-bottom:5px;margin-bottom:5px;">
<tr>
<td class="askerbg" style="vertical-align:top;padding-right:10px;"><img src="{AskerPortraitURL-64}"></td><td style="vertical-align:top;"><strong>{Asker} asked:</strong>
<div class="question">{Question}</div>
</td>
</tr>
</table>
{Answer}
{/block:Answer}
 
 
<!--------------------------------------------------------------POST INFO -->
 
{block:Date}
 
<div class="permalink-box">
<div class="permalink">
 
<div class="date-container">
<a href="{Permalink}">{DayOfMonthWithZero}/{MonthNumber}/{ShortYear}</a>
 
 
 
{block:NoteCount}
• <a href="{Permalink}">{NoteCount}</a> notes
 
{/block:NoteCount}
</div>
 
{block:RebloggedFrom}
<div class="source"><a href="{Permalink}">Permalink</a> •
<a href="{ReblogRootURL}">source</a></div>
{/block:RebloggedFrom}
 
<div class="share">
<div class="reblog">
<a href="{ReblogURL}" target="_blank"><span class="fas fa-sync-alt"></span></a>
<div class="like"> <svg width="14" height="14" viewBox="0 0 19 16" xmlns="http://www.w3.org/2000/svg" xmlns:xlink="http://www.w3.org/1999/xlink" fill="#010101"> <path d="M14.0425097,0.000920262799 C16.1435097,-0.0400797372 18.8835097,1.28192026 18.9635097,5.36992026 C19.0525097,9.95492026 15.1985097,13.3079203 9.48350967,16.2089203 C3.76650967,13.3079203 -0.0874903349,9.95492026 0.00150966509,5.36992026 C0.0815096651,1.28192026 2.82150967,-0.0400797372 4.92250967,0.000920262799 C7.02450967,0.0419202628 8.87050967,2.26592026 9.46950967,2.92792026 C10.0945097,2.26592026 11.9405097,0.0419202628 14.0425097,0.000920262799 Z"></path></svg>
 
{LikeButton size="14"}
 
 
 
</div>
</div>
</div>
</div>
{/block:Date}
 
 
 
 
<!------------------------------------------------------------------ TAGS -->
 
</div>
 
 
{block:date}
 
 
<div class="tags-container">
<div class="tags">
{block:Tags}{block:HasTags}
<a href="{TagURL}">{Tag}</a>
{/block:HasTags}{/block:Tags}
</div>
</div>
 
 
{/block:date}
 
 
 
 
 
</div>
{/block:Posts}
 
 
 
 
 
 
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
<!-------------------------------------------------------------------------->
 
 
 
 
 
 
 
 
<!-------------------------------------------------------- PERMALINK PAGE -->
 
{block:PermalinkPage}
{block:PostNotes}
<div class="notes-container">
<div class="notes">
{PostNotes}
</div>
</div>
{/block:PostNotes}
{/block:PermalinkPage}
 
 

 
</body></html>
