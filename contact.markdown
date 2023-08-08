---
layout: bare
title: Contact
permalink: contact
type: page
order: 99
slug: contact
show_in_nav: false
---

<form id="fs-frm" name="simple-contact-form" accept-charset="utf-8" action="https://formspree.io/f/xdorarvd" method="post" class="uk-card contact-form">
  <div class="uk-card-body">
    <h3>
      <span uk-icon="comment" class="inline-icon uk-margin-right"></span>Contact Me
    </h3>
    <fieldset id="fs-frm-inputs" uk-grid>
        <div class="uk-form-controls uk-width-1-2@s">
          <label class="uk-form-label" for="full-name">Your Name</label>
          <input class="uk-input" type="text" name="name" id="full-name" placeholder="" required="">
        </div>
        <div class="uk-form-controls uk-width-1-2@s">
          <label class="uk-form-label" for="email-address">Email Address</label>
          <input class="uk-input" type="email" name="_replyto" id="email-address" placeholder="" required="">
        </div>
        <div class="uk-form-controls uk-width-1-1">
          <label class="uk-form-label" for="message">Message</label>
          <textarea class="uk-textarea" rows="5" name="message" id="message" placeholder="" required=""></textarea>
        </div>
      <input type="hidden" name="_subject" id="email-subject" value="Contact Form Submission">
    </fieldset>
    <input type="submit" value="Submit" class="uk-button uk-button-default uk-margin">
  </div>
</form>

<script>
 window.onbeforeunload = () => {
  for(const form of document.getElementsByTagName('form')) {
    form.reset();
  }
}
</script>
