# Cybertalants-writeup

# Web Security challenges



# Admin has the power



- when you opne the page you can right click and view the page source code.

- we will see the `<TODO: remove this line ,  for maintenance purpose use this info (user:support password:x34245323)>`

- here we can login with username=support and password=x34245323

- open Burp-suite and intercept on and when you login with the page check proxy >> "intercept"

- send the http request to Repeater

- you will see the the cookie and role=support

- the challenge say Admin has the power so the role=admin

- you will see the flag: `hiadminyouhavethepower`
