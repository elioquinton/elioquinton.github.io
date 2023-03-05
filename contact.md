---
layout: page
title: Contact
subtitle: 
description: Elio Quinton contact form
hide_hero: true
---


# CONTACT

----


<!-- Contact form setup using Herotofu: https://herotofu.com/solutions/guides/jekyll-contact-form -->

<!-- #TODO: Wrap in a column to center and reduce width https://bulma.io/documentation/columns/sizes/-->
<form action="https://public.herotofu.com/v1/351dc4b0-aa12-11ed-a31e-753411848f80" method="POST" target="_blank">
    <div class="field">
        <label class="label">Name</label>
        <div class="control">
            <input class="input" type="text" placeholder="Name" required />
        </div>
    </div>
    <div class="field">
        <label class="label">Email</label>
        <div class="control has-icons-left">
            <input class="input"  type="email" placeholder="Email" name="email" required />
            <span class="icon is-small is-left">
            <i class="fa fa-envelope"></i>
            </span>
        </div>
    </div>
    <div class="field">
        <label class="label">Message</label>
        <div class="control">
            <textarea class="textarea" placeholder="Message" name="message" required></textarea>
        </div>
    </div>
    <div class="control">
        <button class="button is-link" type="submit" value="Download CTA">Submit</button>
    </div>
</form>


