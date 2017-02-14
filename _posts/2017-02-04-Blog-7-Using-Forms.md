---
layout: post
title: Using Forms
---
<head>
<script>
function Message() {
  var message = document.getElementById("meme").value;
  document.getElementById("print").innerHTML = "Anonymous said: " + message
}
</script>
</head>

<p>So in my blog i will...<em>USE FORMS</em>.</p>

<p>I will use it for searching for specific blogs by blog number (1, 2, 3, etc).</p>
<p>This makes the process of finding a specific blog easier.</p>

<form onsubmit="Message()" method="post">
<textarea rows="4" cols="50" id="meme">
Type text here and press enter to post it
</textarea>
<input type="submit" value="Submit" name="button">
</form>

<p id="print"></p>


