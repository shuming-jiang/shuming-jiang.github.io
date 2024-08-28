---
layout: archive
title: "Test"
permalink: /test/
author_profile: true
---
< html>
<html lang="en">

<body>

<h2>会议信息表</h2>

<!-- 2023年会议表格 -->
<h3>2023年会议</h3>
<table>
    <tr>
        <th>会议名称</th>
        <th>接受开始日期</th>
        <th>截止日期</th>
        <th>会议官网</th>
        <th>会议论文列表</th>
    </tr>
    {% for conference in conferences_2023 %}
    <tr>
        <td>{{ conference.name }}</td>
        <td>{{ conference.start_date }}</td>
        <td>{{ conference.deadline }}</td>
        <td><a href="{{ conference.website }}">{{ conference.name }}</a></td>
        <td>
            <ul>
                {% for paper in conference.papers %}
                <li>{{ paper }}</li>
                {% endfor %}
            </ul>
        </td>
    </tr>
    {% endfor %}
</table>

<!-- 2024年会议表格 -->
<h3>2024年会议</h3>
<table>
     <tr>
        <th>会议名称</th>
        <th>接受开始日期</th>
        <th>截止日期</th>
        <th>会议官网</th>
        <th>会议论文列表</th>
    </tr>
    {% for conference in conferences_2024 %}
    <tr>
        <td>{{ conference.name }}</td>
        <td>{{ conference.start_date }}</td>
        <td>{{ conference.deadline }}</td>
        <td><a href="{{ conference.website }}">{{ conference.name }}</a></td>
        <td>
            <ul>
                {% for paper in conference.papers %}
                <li>{{ paper }}</li>
                {% endfor %}
            </ul>
        </td>
    </tr>
    {% endfor %}
</table>

</body>
</html>
