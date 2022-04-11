---
layout: splash
permalink: /about
title: How Aleph Works
header:
  overlay_color: "#5e616c"
  overlay_image: /assets/images/unsplash_header.jpg
  actions:
    - label: "<i class='fas fa-fw fa-calendar-alt'></i> Try a free session today"
      url: "https://app.squarespacescheduling.com/schedule.php?owner=25887823"
    - label: "<i class='fa fa-question-circle'></i> Contact Us"
      url: "https://alephinst.com/#contact"
excerpt: >
    From assessment to completion, we guide your student at every step of the way.
gallery:
  - url: /assets/images/example-page.png
    image_path: /assets/images/example-page.png
    alt: "A student's homepage"
    title: "A student's homepage"
  - url: /assets/images/example-curriculum.png
    image_path: /assets/images/example-curriculum.png
    alt: "The PSAT curriculum"
    title: "The PSAT curriculum"
gallery2:
  - url: /assets/images/replit-example.png
    image_path: /assets/images/replit-example.png
    alt: "Collaborative project example"
---

{% include gallery caption="A students custom page and curriculum!" %}

<details>
  <summary>
    <b>How do sessions work?</b>
  </summary>
  <p style="padding-left:10px;">We firstly create a custom page for each student that contains links to sessions, helpful resources, completed curriculums, and curriculums currently in-progress.</p> 
  <p style="padding-left:10px;">All of our curriculums start with an assessment where the student answers a set of foundational questions that represent the entire curriculum. Our team then generates coursework that addresses the needs of the student to ensure that we focus on critical concepts during sessions. This results in a unique lesson plan for every student!</p> 
  <p style="padding-left:10px;">Once coursework is generated, an instructor works with the student to assist in studying modules in a one-to-one online session. Our sessions generally last 1-hour.</p>
  <p style="padding-left:10px;">In regular intervals, instructors gauge a students progress by either evaluating independent projects or by running through assessments again. Once a student completes their curriculum they can either move onto something new, or go through the curriculum again to evaluate new modules!</p> 
</details>

<hr>


<details>
  <summary>
    <b>Do we offer homework help?</b>
  </summary>
  <p style="padding-left:10px;"> While we strive to ensure that sessions are used solely for coursework we acknowledge that completing and understanding homework is a vital part to a students success. For that reason,students may bring pertinent homework questions to a session, especially when it involves topics covered in our curriculum.</p> 
</details>
<hr>

<details>
  <summary>
    <b>How can students collaborate?</b>
  </summary>
  <p style="padding-left:10px;">Coding skills and computer science knowledge are fundemental pillars of being a good coder, and so is ability to work on a team! For our computer science courses, we offer students the opportunity to work with other students of similiar skill and age to create a personal coding project.</p>
  {% include gallery id="gallery2" layout="half" caption="An example of a collaborative project in Python" %} 
</details>

<hr>

<details>
  <summary>
    <b>Who are the instructors?</b>
  </summary>
  <p style="padding-left:10px;">We are a team of experienced instructors and college students motivated by seeing academic success in students. Our goal is the process of learning itself, while still upholding good grades and outcomes as positive signs of successful habits. This attitude ensures that we cultivate a culture of education and install a lifelong pursuit of knowledge.</p> 
</details>
<hr>

<section>
  <div class="row">
      <h3 style="padding-left:10px;">Contact</h3>
  </div>
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
