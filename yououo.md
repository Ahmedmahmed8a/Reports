# Vulnerability type:
##  xss
# Domain :[yououo.atwebpages.com](http://yououo.atwebpages.com)
# How:
  Xss vulnerability in user input 
# infected tags :
`<input type="text" name="contact" class="form-control" id="validationCustom05" placeholder="Facebook link or Whatsapp link" required>
  `  
#   payloads:
1. "data:text/html;base64,PHNjcmlwdD5hbGVydCgiSGVsbG8iKTs8L3NjcmlwdD4="
2. href="Javascript:alert('hi');"
# exploitablity :
Injecting the attribute
# Impact :
Stealing cookies or hacking the browser

# State :
Fixed 
# Solution :
Allowing only `http/https` links
----
