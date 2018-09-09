---
layout: page
title: About
permalink: /about/
tags: about
---

Created and maintained by [Sumit Gupta](http://sumitg.com/about). <br>
Feel free to send me an email at **sumit743@gmail.com** if you would like to talk.

### Why did I create SimpleML.org?

> "Machine Learning algorithms are simple, beautiful, and a work of art -- they should be presented like one."

SimpleML.org is an effort to provide exceptionally easy-to-understand articles on machine learning algorithms. The internet is filled with tutorials, slides, blogs, and videos on machine learning algorithms, but I always find at least one of the following missing: clarity, structure, examples, completeness, and visualizations. SimpleML.org tries to fix that.

I don't remember when exactly I got the idea of starting SimpleML.org, but it was sometime in 2015-2016.

### Logo
The shape is called [Sombrero](https://www.google.com/search?q=sombrero+shape). Why this logo? No reason. I just liked it. It can be reproduced by the following [Octave](https://www.gnu.org/software/octave/) code.

{% highlight matlab %}
clear
tx = ty = linspace (-10, 10, 1000);
[xx, yy] = meshgrid (tx, ty);
r = sqrt (xx .^ 2 + yy .^ 2) + eps;
tz = -10 + sin (r) ./ r;
mesh (tx, ty, tz);
surf (tx, ty, tz, 'edgecolor', 'none');
{% endhighlight %}

I am looking for a better logo, please contact me if you can design one. The logo should incorporate the *"machine learning"* theme. It also should incorporate that all articles on SimpleML.org are highly technical yet extremely simple to understand. I am not looking for a [robot logo](https://www.google.com/search?q=machine+learning+images) or a human brain with wires and gears.
