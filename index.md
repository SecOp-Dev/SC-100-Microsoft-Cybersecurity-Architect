---
title: Online Hosted Instructions
permalink: index.html
layout: home
---

# Content Directory

Hyperlinks to each case study is listed below.

https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/01-LAB_SC_100_Lab3_Ex1_Compliance_Assessment.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/02-LAB_SC_100_Lab2_Ex1_Entra_ID_policies.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/03-LAB_SC_100_Lab2_Ex2_Conditional_Access.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/05-LAB_SC_100_Lab1_Ex1_Sentinel.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/07-LAB_SC_100_Lab3_Ex2_Data%20classification%20framework.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/03-LAB_SC_100_Lab2_Ex2_Conditional_Access.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/07-LAB_SC_100_Lab3_Ex2_Data%20classification%20framework.md
https://github.com/SecOp-Dev/SC-100-Microsoft-Cybersecurity-Architect/blob/master/Instructions/Labs/07-LAB_SC_100_Lab3_Ex2_Data%20classification%20framework.md

## Case studies reorganized for May 2023 content refresh

{% assign casestudy= site.pages | where_exp:"page", "page.url contains '/Instructions/CaseStudyv2/'" %}
| Module | CaseStudy |
| --- | --- | 
{% for activity in casestudy  %}| {{ activity.casestudy.module }} | [{{ activity.casestudy.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}


## Old case study organization

{% assign casestudy= site.pages | where_exp:"page", "page.url contains '/Instructions/CaseStudy/'" %}
| Module | CaseStudy |
| --- | --- | 
{% for activity in casestudy  %}| {{ activity.casestudy.module }} | [{{ activity.casestudy.title }}]({{ site.github.url }}{{ activity.url }}) |
{% endfor %}
