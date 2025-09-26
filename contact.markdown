---
layout: page
title: Contact
permalink: /contact/
order: 3
---

<style>
input[type="text"], input[type="email"], input[type="search"], 
input[type="submit"], button, textarea { 
  padding: 1em 1.5em; 
  border: 1px solid #e5e5e5; 
  border-radius: 300px; 
  margin-bottom: 1em; 
  font-family:  -apple-system, BlinkMacSystemFont, "Segoe UI", 
                "Roboto", "Oxygen", "Ubuntu", "Cantarell", 
                "Fira Sans", "Droid Sans", "Helvetica Neue", 
                Arial, sans-serif; 
  font-size: 14px;
}

textarea { width: 100%;  resize: none; }
</style>


<!-- modify this form HTML and place wherever you want your form -->
<form
  action="https://formspree.io/f/xgvnowpv"
  method="POST"
>
  <label>
    Your email:<br />
    <input type="email" name="email">
  </label>

  <br /><br />

  <label>
    Your message:<br />
    <textarea name="message"></textarea>
  </label>
  <!-- your other form fields go here -->
  <br />
  <button type="submit">Send</button>
</form>