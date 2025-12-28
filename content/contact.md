+++
title = "Contact"
template = "page.html"
+++

<form class="lead-form" action="https://formspree.io/f/REPLACE_ME" method="POST">
  <label>
    Name
    <input type="text" name="name" autocomplete="name" required />
  </label>

  <label>
    Email
    <input type="email" name="email" autocomplete="email" required />
  </label>

  <label>
    Company / Project
    <input type="text" name="company" />
  </label>

  <label>
    What are you building?
    <textarea name="message" rows="6" required></textarea>
  </label>

  <!-- Optional: Helps you filter spam -->
  <input type="hidden" name="_subject" value="New lead from saunee.co" />
  <input type="hidden" name="_replyto" value="%email%" />

  <div class="cta">
    <button type="submit">Send</button>
    &nbsp;&nbsp;
    <a href="/book">Or book a call</a>
  </div>
</form>
