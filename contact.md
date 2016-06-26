---
layout: page
title: Contact
permalink: /contact/
published: true
---
Want to get in touch with us? Shoot us a note below.

<form id="contact" action="https://getsimpleform.com/messages?form_api_token=05bb82ce78f4a228ed59040f665de98d" method="post">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->
  <input type='hidden' name='redirect_to' value='http://breakingespanol.com/thanks' />
  <!-- all your input fields here.... -->
	<label for="name">Name</label><br/>
	<input type='text' name='name' />
	<label for="email">Email</label><br/>
  <input type='text' name='email' />
	<label for="message">Message</label><br/>
  <textarea id="msg" rows="10" cols="70" name="message" form="contact"></textarea><br/>
  <input type='submit' value='Send' />
</form>
