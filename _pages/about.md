---
permalink: /
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at [State Key Lab of CAD&CG](http://www.cad.zju.edu.cn/), Zhejiang University, supervised by [Prof. Xiaogang Jin](http://www.cad.zju.edu.cn/home/jin/). I received my Bachelor's degree in Software Engineering from the College of Computer Science and Technology at Zhejiang University in 2023.

My research focuses on **Character Animation**. I am passionate about bringing digital characters to life with emerging technologies and creating more expressive and natural motions.

**Address:** Zijingang Campus of Zhejiang University, 866 Yuhangtang Rd, Hangzhou 310058, P.R. China.

**Contact:** bwzheng@zju.edu.cn / zhengbowen.crist@gmail.com



------
# Publications

{% for post in site.publications reversed %}
    {% if post.select == true %}
      {% include archive-single.html %}
    {% endif %}
{% endfor %}
