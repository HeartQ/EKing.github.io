---
layout: post
title:  "The first NOTEs" 
tags: TEST
categories: original
---

**Trustworthy Software** is a trust on software

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{ post.excerpt }}
    </li>
  {% endfor %}
</ul>

When I first study on  github
Now the working there are 

[DE]({% post_url 2017-02-05-welcome-to-mark %})
{{ site.time | date_to_rfc822 }}

基于模型和规约的可信软件测试技术 
> **可信性的探究**

- `可用性` MTTF/（MTTF+MTTR）*100%（功能、响应时间）
- `可靠性` 避错法，容错法
- `安全性` 应用程序级别，系统级别
- `可维护性` 具有易于修改，可进化的能力，维护费用小
- `完整性` 为一个实现特点的目标而进行的工作期望

> *ISO/IEC 15408 标准 将可信定义为：一个可信的组件可预测*  

> **软件质量**

1. 软件产品中能满足给定需要的性质和特性的总体
2. 软件具有所期望的各种属性的组合程度
3. 顾客和用户觉得软件满足其综合期望的程度
4. 确定软件在使用中将满足顾客预期要求的程度
5. 成本趋向于固定量 ‘A’ 然而需求的变化量趋向于 ‘∞’

> **可信软件**
> 任意条件下存在服务与预期相符一致

> **基于模型**   对软件的行为结构建模

- 系统操作限于约束条件\[Value\]\[Event\]
- 系统将半自动/自动的转换为模型[XML]←→[有向图]
- \[有向图\]\(next、precede\)

----------

![test]({{ site.url }}/assets/IMG_0266.JPG)

----------

2/7/2017 2:19:44 PM 
