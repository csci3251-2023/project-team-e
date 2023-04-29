# CSCI3251 project Team E

## Introduction
In this project, our team will work out several issues according to the tasks.

**Tasks are in Issue folder above tabs and also listed below:**

|  Tasks  |  Details  |
| ------------- | ------------- |
|  4  |  Write C Code  |
|  5  |  Get a Status Badge  |
|  6  |  Showcase your team  |
|  7  |  Register your repo |

## Code
```c
{%include_relative code.c%}
```
![Workflow Status](https://github.com/csci3251-2023/project-team-e/actions/workflows/c-cpp.yml/badge.svg)

## Contributors
{% for stu in site.stu %}
  >> !({{ stu.image }})@{{ stu.user }} {{( stu.name )}}
  {{ "\t" }}>> {{ stu.content | markdownify }}
{% endfor %}
