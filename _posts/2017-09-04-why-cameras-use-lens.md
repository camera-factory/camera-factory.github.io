---
layout: post
title: Why cameras use lens instead of a pinhole?
category: Working principles of cameras
---

We have talked about the [pinhole camera]({% post_url	2017-08-31-pinhole %}) in the last post. The structure of pinhole camera is 
simple, the images taken by pinhole camera have full depth of view. And you don't have to spend hundreds of dollars on your len, 
after all the cost of manufacturing a high-quality pinhole is much lower than that of a high-qulity lens. So why almost all 
morden cameras use lens? This question seems to be very simple, but worth discussing.  

Firstly, let us have a further look at the pinhole camera. In order to get a image form a pinhole camera, the size of the hole is 
actually a key parameter.   

Ideally, lights emitted by a point on the object should reach one point on the sensor so that we can get a sharp image. The pinhole 
camera achieves this by blocking most of the lights, only the lights passing through the pinhole are preserved. This bruch of lights 
reach the image plane as a small circle instead of an idea point.  

![2017-09-04-lens-pinhole]({{site.baseurl}}/images/20170904-lens-pinhole.png)

If we increase the size of the pinhole, the circle also increases, resulting in a blurred image. But with a smaller pinhole, we cannot 
gain enought lights, this tends to produce noisy image. Even assuming we have a super sensitive film and can make the pinhole super 
tiny, the diffraction of light will also hinder us from getting sharp images， let alone this kind of film is hardly to obtain.  

This contradiction is the inherent weakness of pinhole cameras. And the lens helps to solve this problem. As shown in the following 
figure, we enlarge the pinhole, and install a lense on it to focus the divergent lights again. Although not all lights pass a 
straight way, they all reach the same point as they really travelled a straing way. 

![2017-09-04-lens-lens]({{site.baseurl}}/images/20170904-lens-lens.png)

In conclusion, the lens helps to gather more lights without breaking the linear projection relation.  

At last, it is worth mentioning that the lense are very precise instrument. Any piece of lens may have imperfections on account of 
the design, the material and so on. And this is why the price gap of different lenses is that large. You can read another [post about 
lens]({% post_url 2017-09-05-what-makes-for-a-good-lens %}) for a genral understanding of what makes lenses different and why a lense is good or bad.
