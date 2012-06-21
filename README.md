<h1>Adobe Business Catalyst Reset Project</h1>
=====================================

<p>This project aims to reset the default style sheet served for any Adobe Business Catalyst website.</p>
<p>The purpose of this is to reset all the pre-defined styles, fix incorrectly applied classes and methods and make minor changes to it easier to apply consistent custom styles for your own site which won't conflict with 3rd party style sheets and javascript.</p>

<h2>How to use</h2>
<p>Just hot link the latest reset style sheet inside your html file as the first CSS reference.</p>
<!--
&lt;link href="/StyleSheets/ModuleStyleSheets.css" type="text/css" rel="StyleSheet" /&gt;
-->
<h2>A little background</h2>
<p>Whenever you create a new Adobe Business Catalyst website you'll notice the following line of code gets added to any HTML file you create inside BC.
<pre>
&lt;link href="/StyleSheets/ModuleStyleSheets.css" type="text/css" rel="StyleSheet" /&gt;
</pre>
<p>This style sheet is the default style sheet served by Business Catalyst in order to pre-style a basic website.</p>
<p>The major issue with this is that the styles often conflict with your own custom stylesheet and many "default" styles do not relect what you may want to appear in your website.</p>
<p>There is also very little consistency in font-sizes, line-heights, margins, padding which make it very difficult to create a website which conforms to basic design principles and make a site look its best.</p>