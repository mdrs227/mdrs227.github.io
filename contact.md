---
title: Contact
feature_text: |
  Please contact us about our mission!
feature_image: "https://raw.githubusercontent.com/mdrs227/mdrs227.github.io/master/bannerContact.png"
excerpt: "A demo of Markdown and HTML includes"
aside: false
---

{::nomarkdown}
<p>Would you like to know more about and/or support MDRS 227? Please fill out the form below and we will get back to you shortly!</p>
<form action="https://formspree.io/mdrs2272020@gmail.com" method="POST" name="sentMessage" id="contactForm" novalidate>            
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Name</label>
            <input type="text" name="mdrsText" class="form-control" placeholder="Name" id="name" required data-validation-required-message="Please enter your name.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Email Address</label>
            <input type="email" name="mdrsEmail" class="form-control" placeholder="Email Address" id="email" required data-validation-required-message="Please enter your email address.">
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <div class="row control-group">
        <div class="form-group col-xs-12 floating-label-form-group controls">
            <label>Message</label>
            <textarea rows="5" name="mdrsMessage" class="form-control" placeholder="Message" id="message" required data-validation-required-message="Please enter a message."></textarea>
            <p class="help-block text-danger"></p>
        </div>
    </div>
    <br>
    <div id="success"></div>
    <div class="row">
        <div class="form-group col-xs-12">
            <button type="submit" class="btn btn-default">Send</button>
        </div>
    </div>
</form>
{:/nomarkdown}


