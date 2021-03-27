---
layout: layouts/post.njk
title: Contact Me
templateClass: tmpl-post
eleventyNavigation:
  key: Contact Me
  order: 5
---

<form name="contact" method="POST" data-netlify="true">
  <div class="form-floating mb-3">
  <p>
    <label>Your Name: <input type="text" name="name" required/></label>   
  </div></p>
  <div class="form-floating mb-3">
  <p>
    <label>Your Email: <input type="email" name="email" required/></label></p></div>
    <p><div id="email" class="form-text">We'll never share your email with anyone else.</div>
  </div></p>
  <select class="form-select" aria-label="describe yourself">
  <p>I am... </p>
  <option selected>Please pick the option that best describes you</option>
  <option value="interested">interested in starting the Montessori method</option>
  <option value="follower">follower of the Montessori method</option>
  <option value="activities">just looking for inspiration for activities</option>
</select>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
</p>
    <p>
    <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="CheckUpdates">
    <label class="form-check-label" for="examplFCheck1">I'd love to hear more Montessori-inspired activities from you.</label>
    </p>
   <p>
    <div class="mb-3 form-check">
    <input type="checkbox" class="form-check-input" id="CheckTOC">
    <label class="form-check-label" for="exampleCheck1">I have read the terms and conditions</label>
    </p>
  <p>
    <button type="submit">Send</button>
    </p>
</form>
