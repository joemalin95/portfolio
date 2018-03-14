---
layout: page
title: Contact
permalink: /contact/
---

<script>
    $("#contact-form").validate();
</script>

<div class="header-row">
        <span class="header-text">Contact Me</span>
</div>
<div class="description-row">
        <span class="description-text">
            <p>
                If you have an questions or would simply like to say hello, please fill out the form below and I will get back to you as soon as possible! If you prefer to call or email me directly, I have also included my direct contact information below.
            </p>
            <div class="contact-info">
                <div class="contact-info-row">
                    <span class="contact-info-label">
                        Email Address: 
                    </span>
                    <span class="contact-info-value">
                        <a href="mailto:joemalin95@gmail.com" target="_top">joemalin95@gmail.com</a>
                    </span>
                </div>
                <div class="contact-info-row">
                    <span class="contact-info-label">
                        Phone Number:    
                    </span>
                    <span class="contact-info-value">
                        <a href="tel:630-390-6519">630-390-6519</a>
                    </span>
                </div>
            </div>
        </span>
</div>


<form action="https://formspree.io/joemalin95@gmail.com" method="POST">
  <input type="hidden" name="_next" value="{{site.url}}/{{site.return_path}}/"/>
  <input type="text" name="_gotcha" style="display:none" />

  <div class="contact-container">
      <div class="contact-row">
          <div class="contact-field left">
              <div class="contact-label">
                  <label for="name-input">Your Name</label>
              </div>
              <div class="contact-input">
                  <input  id="name-input" type="text" name="name" required>
              </div>
          </div>
          <div class="contact-field right">
              <div class="contact-label">
                  <label for="email-input">Your Email</label>
              </div>
              <div class="contact-input">
                  <input id="email-input" type="email" name="_replyto" required>
              </div>
          </div>
      </div>
      <div class="contact-row">
          <div class="contact-field">
              <div class="contact-label">
                  <label for="message-input">Message</label>
              </div>
              <div class="contact-input">
                  <textarea id="message-input" name="Message" rows="5" required ></textarea>
              </div>
          </div>
      </div>
      <div class="contact-row">
            <button class="contact-submit-btn std-btn" type="submit">
                <i class="fa fa-paper-plane"></i>
                <span>Send</span>
            </button>
      </div>
  </div>
</form>

