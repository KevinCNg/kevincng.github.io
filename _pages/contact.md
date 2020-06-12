---
layout: archive
title: "CONTACT ME"
permalink: /contact/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLScfI0thzrZ2s0paSAtgX03aHpo7bo-Ab0GHfp37z1QaRAIhTA//formResponse?" target="hidden_iframe" onsubmit="submitted=true;">  
  Name:<br>
  <input type="text" name="entry.637184215" id="entry.637184215"><br>
  Email:<br>
  <input type="text" name="entry.63001815" id="entry.63001815"> <br>
  Message:<br>
  <input type="text" name="entry.1916994249" id="entry.1916994249">
  <input type="submit" value="Send">
</form>

<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed.');
  });
</script>