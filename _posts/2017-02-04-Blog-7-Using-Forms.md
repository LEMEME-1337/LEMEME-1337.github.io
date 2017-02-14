---
layout: post
title: Using Forms
---
<head>
<script>
function Message() {
  var message = document.getElementById("meme").innerHTML
  document.getElementById("meme").innerHTML = document.getElementById("meme")
}
</script>
</head>

<p>So in my blog i will...<em>USE FORMS</em>.</p>

<p>I will use it for searching for specific blogs by blog number (1, 2, 3, etc).</p>
<p>This makes the process of finding a specific blog easier.</p>

<form id="meme" onsubmit="Message()">
<textarea rows="4" cols="50" >
Type text here and press enter to post it
</textarea>
<input type="submit" value="Submit" name="button">
</form>


