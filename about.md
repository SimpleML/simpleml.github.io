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

SimpleML.org is an effort to make machine learning algorithms exceptionally easy to understand. The internet is filled with tutorials, slides, blogs, and videos on machine learning algorithms, but I always find at least one of the following missing: clarity, structure, examples, completeness, and visualizations. SimpleML.org tries to fix that.

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

### Contribute
All contributions are welcome. Please contact me if you would like to contribute. 

* **Web Development**: Improve SimpleML.org website by using HTML, CSS, JavaScript and other modern web technologies.
* **Design**: Overall design and user-friendliness of the website.
* **SEO**: Improve SEO of the website.
* **Translation**: Translate articles into other natural languages.
* **Logo**: Design a better logo.
