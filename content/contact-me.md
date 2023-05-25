---
title: "Contact me"
menu: "main"
---

<form name="contact" action="/thank-you" class="contact-form" method="post" netlify netlify-honeypot="phone">
  <div><input type="text" name="name" placeholder=" " required>
    <label for="name">Name</label><i class="fa" aria-hidden="true"></i>
    <span class="underline"></span>
  </div>

  <p aria-hidden="true"><input type="text" name="phone" placeholder=" " autocomplete="off" tabindex="-1">
    <label for="phone">Phone</label><i class="fa" aria-hidden="true"></i>
    <span class="underline"></span>
  </p>
  
  <div><input type="email" name="email" placeholder=" " required>
    <label for="email">Email</label><i class="fa" aria-hidden="true"></i>
    <span class="underline"></span>
  </div>

  <div><input type="text" name="subject" placeholder=" ">
    <label for="subject">Subject <i>· Optional</i></label>
    <span class="underline"></span>
  </div>

  <div><textarea name="message" placeholder=" " required></textarea>
    <label for="message">Message</label></i>
    <span class="underline"></span>
  </div>

  <button type="submit" class="form-submit">
    <span><i class="fa fa-paper-plane" aria-hidden="true"></i>Send</span>
  </button>
</form>
