---
layout: splash
permalink: /
title: Personalized Education
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/csaba-balazs-q9URsedw330-unsplash.jpg
  actions:
    - label: "<i class='fas fa-fw fa-calendar-alt'></i> Try a free session today"
      url: "https://app.squarespacescheduling.com/schedule.php?owner=25887823"
    - label: "<i class='fa fa-question-circle'></i> How it works"
      url: "https://alephinst.com/about"
excerpt: >
    Coding, College Prep, & Mathematics tailored to each student.
feature_row:
  - image_path: /assets/images/building.jpg
    alt: "steps logo"
    title: "Modular Curriculums"
    excerpt: "Each course is tailored to a student and their unique foundational needs and goals."
    url: "/about#how-does-aleph-work"
    btn_class: "btn--success"
    btn_label: "Learn more"
  - image_path: /assets/images/collab.png
    alt: "collaboration logo"
    title: "Collaboration"
    excerpt: "Students have the opportunity to collaborate with other student coders to learn new skills."
    url: "/about#collaboration"
    btn_class: "btn--success"
    btn_label: "Learn more"
  - image_path: /assets/images/remote.jpg
    alt: "internet on laptop logo"
    title: "100% Remote"
    excerpt: "Lessons supported by online tools designed with the students needs in mind."
    url: "/about#how-does-aleph-work"
    btn_class: "btn--success"
    btn_label: "Learn more"      
---

<!-- Messenger Chat Plugin Code -->
<div id="fb-root"></div>

<!-- Your Chat Plugin code -->
<div id="fb-customer-chat" class="fb-customerchat">
</div>

<script>
  var chatbox = document.getElementById('fb-customer-chat');
  chatbox.setAttribute("page_id", "102363732402787");
  chatbox.setAttribute("attribution", "biz_inbox");
</script>

<!-- Your SDK code -->
<script>
  window.fbAsyncInit = function() {
    FB.init({
      xfbml            : true,
      version          : 'v13.0'
    });
  };

  (function(d, s, id) {
    var js, fjs = d.getElementsByTagName(s)[0];
    if (d.getElementById(id)) return;
    js = d.createElement(s); js.id = id;
    js.src = 'https://connect.facebook.net/en_US/sdk/xfbml.customerchat.js';
    fjs.parentNode.insertBefore(js, fjs);
  }(document, 'script', 'facebook-jssdk'));
</script>

{% include feature_row %}

<section>
  <div class="row">
    <h3 style="padding-left:10px;">Who are we?</h3>
  </div>
  <div class="row">
    <div class="column-contact" style="padding-left:50px;width:25%;">
      <img src="assets\images\fullbarns_comp-modified.png" width="70%">
    </div>
    <div class="column-contact" style="width:75%;">
      <p style="padding-left:10px;">We are a group of experienced instructors and college students dedicated to providing well-planned, dynamic, and comprehensive plans and mentorship to help students learn new subjects, improve academic performance, or restructure foundational knowledge.</p> 
    </div>
  </div>
</section>
<hr>

<section>
  <div class="row">
    <h3 style="padding-left:10px;">What does Aleph mean?</h3>
  </div>
  <div class="row">
    <div class="column-contact" style="width:75%;">
      <p style="padding-left:25px;">Mathematics has existed as one big global collaborative project long before its 
      compartmentalization into the standardized school curriculum. From the concept of zero from the ancient near east, to modern studies devoted to different sizes of infinity, called <b>aleph numbers</b>.</p> 
      <p style="padding-left:25px;">In the early 20th century, an informal institution devoted to set theory and aleph numbers had attracted students and teachers devoted to ideas of <b>self-discovery</b>, <b>knowledge for the sake of knowledge</b>, and <b>de-mystifying the abstract</b>. We hope to emulate these principles to guide students to academic excellence in all subjects.</p> 
    </div>
    <div class="column-contact" style="padding-left:80px;width:25%;padding-top:20px;">
      <img src="assets\images\640px-Aleph0.svg.png" width="100%">
    </div>
  </div>
</section>
<hr>


### Contact
<section>
  <p style="padding-left:25px;">If you are interested in signing up, or for any questions regarding curriculum or pricing, please contact us below. We look forward to supporting you or your student accomplish all academic goals!</p> 
	<div class="row" style="background-color:#F2F3F3;">
    <div class="column-contact">
      <form action="https://formspree.io/f/xjvlwbzp" method="POST">
          <div class="row">
            <div class="column-contact-inner">
              <label for="name"><b>Name</b></label>
              <input type="text" name="name" id="name" />
            </div>
            <div class="column-contact-inner">
              <label for="email"><b>Email</b></label>
              <input type="email" name="email" id="email" />
            </div>
          </div>
          <div class="row">
            <div class="field">
              <label for="message"><b>Message</b></label>
              <textarea name="message" id="message" rows="6"></textarea>
            </div>
            <div class="field">
              <label for="ref-name"><b>Referrer</b></label>
              <input type="text" name="ref-name" id="ref-name" />
            </div>
            <input type="submit" value="Send Message" class="btn--info" />&nbsp; 
            <input type="reset" value="Clear" class="btn--info" />
          </div>
      </form>
    </div>
    <div class="column-contact">
          <hr>
          <b>Email</b><br>
          &nbsp; <i class="fas fa-fw fa-envelope-square" aria-hidden="true"></i>
          <a href="mailto:{{ site.email }}">{{ site.email }}</a>
          <hr>
          <b>Github</b><br>
          &nbsp;<i class="fab fa-fw fa-github" aria-hidden="true"></i>
          <a href="https://github.com/{{ site.github }}" itemprop="sameAs" rel="nofollow noopener noreferrer me">
          {{ site.github }}</a>
          <hr>
          <b>Twitter</b><br>
          &nbsp; <i class="fab fa-fw fa-twitter-square" aria-hidden="true"></i>
          <a href="https://twitter.com/{{ site.twitter }}" itemprop="sameAs" rel="nofollow noopener noreferrer me">{{ site.twitter }}</a>
          <hr>
          <b>Youtube</b><br>
          &nbsp; <i class="fab fa-fw fa-youtube" aria-hidden="true"></i>
          <a href="{{ site.youtube }}" itemprop="sameAs" rel="nofollow noopener noreferrer me">Aleph</a>
          <hr>
		</div>
	</div>
</section>
