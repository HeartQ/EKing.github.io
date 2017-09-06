---
layout: post
title:  "Jekyll ＆ Hexo" 
tags: TEST
categories: original
---

The differences with **Jekyll and Hexo**.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>


----------

jekyll hexo 区别
jekyll 你把原文上傳 github， 可以直接生成博客，也可以用在線編輯器處理 
hexo 是本地生成 html 再上傳

----------

jekyll gem 
CMS(基于网站内容管理)
serve : locachost:4000
grep jekyll
post_url 文章链接模版 `/[Name of link/]`
加载评论 ： 多说 ， Intensedebate 