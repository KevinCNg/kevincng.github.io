---
layout: archive
title: "CONTACT ME"
permalink: /contact/
author_profile: true
---

{% include base_path %}
<body>
   <link rel="stylesheet" href="https://unpkg.com/purecss@1.0.0/build/pure-min.css">
   <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
   <link rel="stylesheet" href="style.css">

  <form class="gform pure-form pure-form-stacked" method="POST" data-email=""
  action="https://script.google.com/macros/s/AKfycbyUGuOikgt01pXbtIzolxU1twBeNLHzuWW4UREPU9SMnToFFS_g/exec">

    <div class="form-elements">
      <fieldset class="pure-group">
        <label for="name">Name: </label>
        <input id="name" name="name" placeholder="Name" />
      </fieldset>

      <fieldset class="pure-group">
        <label for="email">Email:</label>
        <input id="email" name="email" type="email" value=""
        required placeholder="example@email.com"/>
      </fieldset>

      <fieldset class="pure-group">
        <label for="message">Message: </label>
        <textarea id="message" name="message" rows="10"
        placeholder="Message"></textarea>
      </fieldset>

      <button class="button-success pure-button button-xlarge">
        <i class="fa fa-paper-plane"></i>&nbsp;Send</button>
    </div>
    <div class="thankyou_message" style="display:none;">
      <h2>Thank you for contacting me!</h2>
    </div>

  </form>

  <script data-cfasync="false" type="text/javascript" src="https://kevincng.github.io/assets/js/form-submission-handler.js"></script>
</body>