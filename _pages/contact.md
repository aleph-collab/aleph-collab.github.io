---
layout: splash
permalink: /contact
title: Contact 
---
<br>

# We would love to hear from you

For any questions regarding curriculum or pricing. Please contact us below.

We look forward to supporting you or your student accomplish all academic goals! 

<section>
	<div class="row">
        <div class="column">
            <form action="https://formspree.io/f/xjvlwbzp" method="POST" style="background-color:#02818180;">
                <div class="row">
                    <div class="column" style="padding:5px;">
                        <label for="name">Name</label>
                        <input type="text" name="name" id="name" />
                    </div>
                    <div class="column" style="padding:5px;">
                        <label for="email">Email</label>
                        <input type="email" name="email" id="email" />
                    </div>
                </div>
                <div class="row">
                    <div class="field">
                        <label for="message">Message</label>
                        <textarea name="message" id="message" rows="6"></textarea>
                    </div>
                    <ul class="actions">
                        <li><input type="submit" value="Send Message" class="special" /></li>
                        <li><input type="reset" value="Clear" /></li>
                    </ul>
                </div>
			</form>
        </div>
        <div class="column" style="background-color:#02818180;">
            <section>
                <div style="display:inline;">
                    <span class="fas fa-fw fa-envelope-square"></span>
                    <h5>Email</h5>
                    <a href="mailto:{{ site.email }}">{{ site.email }}</a>
                </div>
            </section>
		</div>
	</div>
</section>