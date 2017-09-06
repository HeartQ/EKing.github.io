---
layout: post
title:  "OpenStack" 
tags: TEST
categories: original
---

**OpenStack** is a cloud operating system that... 

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

## OpenStack  ##

----------

UI界面的可视化搭建于 Horizon  ，OpenStack OS由 python编写 ，现主流的分布式系统编写语言并不去完全依赖于C/C++ ，例如 Hadoop →JAVA，Spark →Scala 。 

框架是为了提供API的支持，而OpenStack 作为OS 所具备的能力必然脱离不了资软管理。
1. 计算 Nova
2. 存储 块存储(Cinder) 镜像存储(Glance) 对象存储(Swift)
3. 网络 Nova →Nova network Neutron

OpenStack != 虚拟化软件
管理虚拟机 并不具备虚拟化的功能，虚拟计算是实现云化的一种手段，而云化并不等于虚拟化。

----------


