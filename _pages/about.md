---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am currently a M.S. student at State Key Lab of CAD&CG, Zhejiang University supervised by [Prof. Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin/). I received my Bachelor degree in Software Engineering from the College of Computer Science and Technology at Zhejiang University in 2021.


**Address:** Zijingang Campus of Zhejiang University, 866 Yuhangtang Rd, Hangzhou 310058, P.R. China.

**Research Interest:** Character Animation, AIGC

**Contact:** bwzheng@zju.edu.cn / zhengbowen.crist@gmail.com


# Publications

{% for post in site.publications reversed %}
    {% if post.select == true %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}
