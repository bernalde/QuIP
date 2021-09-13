---
title: Reading
layout: page
menuItem: Reading
menuPosition: 5
---
{% if site.docsUrl != "" %}
You can access all the required reading material via the links provided.
{% endif %}

From among many References, we will discuss in detail one or two papers (or book chapters) per class, depending on the topic. 
Students should read them in advance so that class discussions can be more productive.  


<ol>
{% assign syllabus = (site.syllabus | sort: "week") %}
{% for week in syllabus %}
  <li>
  	<a href="{{ site.baseurl }}{{ week.url }}">{{ week.title }}</a> 
  	{% for tag in week.tags %}
  		<b>#{{ tag }}</b>
  	{% endfor %}
  	({{ week.day }})</li>
{% endfor %}
</ol>

Besides each week's papers there are some casual references we will visit. There is no single text book for the course. This is a  restricted list of various interesting and useful books that will be touched during the course. You may need to consult them occasionally.
- Georges Irfah, The Universal History of Computing, John Wiley & Sons, 2001.
- Eleanor G. Rieffel and Wolfgang H. Polak, Quantum Computing: A Gentle Introduction, MIT Press, 2011. [PDF](http://mmrc.amss.cas.cn/tlb/201702/W020170224608150244118.pdf)
- Richard J. Lipton and Kenneth W. Regan, Quantum Algorithms via Linear Algebra. A Primer, MIT Press, 2014.

Moreover, thanks to the students at IIT-Madras, we have lecture notes for all the classes transcribed and freely available in [arXiv](https://arxiv.org/abs/2012.11382).
