---
layout: post
title:      "Rack, the Internet, and Me"
date:       2018-05-23 14:06:53 +0000
permalink:  rack_the_internet_and_me
---




  I'm supposed to explain my particular style of working with Rack and the Internet, but I'm not quite sure what that means. Are you asking me to explain how I prepare every morning before I go to my lessons or how I buckle down and focus on the tasks at hand without getting distracted? Or do you want me to give you the technical details of it all. I don't feel like I have a specific way of working. I do some yoga to really help me wake up. And then when I get stuck on something I do some more stretches. It helps me loosen up and relax so I can get rid of the mental blocks. I look at the task on hand and take it one step at a time. I do however have a list, a checklist, of things to remember when working with Rack and requesting data from the Internet. 

  Rack, the underlying technology behind most of the web frameworks of Ruby, used to weave together pieces of code to form one big design. Rack has to request and respond. I do have a mini checklist of things when I'm working with Rack to make sure that my codes won't return an 'error'. I made this list a while back after attending a lecture given by a professor in NYU. Step 1 to ensuring that the relationship between Rack and the Internet is smooth and successful: I have an object that has to respond to the method call. Step 2: the forementioned call method has to take in a single argument (which we call the environment). Step 3: it finally has to return an array of 3 elements - a status, headers, and a body. This is almost verbatim what that university professor said, and I find it relevant every time. If you're reading this, I hope that this can help you when you're working with Rack too. And of course, if I get stuck or don't get it at first, I go back and try to see what I missed. If that doesn't work, the Internet!! 
