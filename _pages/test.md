---
layout: archive
title: "Test"
permalink: /test/
author_profile: true
---

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>会议信息表</title>
    <style>
        table {
            width: 100%;
            border-collapse: collapse;
        }
        table, th, td {
            border: 1px solid black;
        }
        th, td {
            padding: 8px;
            text-align: left;
        }
        th {
            background-color: #f2f2f2;
        }
    </style>
</head>
<body>

<h2>会议信息表</h2>
<table>
    <tr>
        <th>会议名称</th>
        <th>接受开始日期</th>
        <th>截止日期</th>
        <th>会议官网</th>
        <th>会议论文列表</th>
    </tr>
    <!-- 示例会议1 -->
    <tr>
        <td>会议名称1</td>
        <td>2024-01-01</td>
        <td>2024-03-01</td>
        <td><a href="http://www.conference1.com">会议官网1</a></td>
        <td>
            <ul>
                <li>论文1标题</li>
                <li>论文2标题</li>
                <!-- 更多论文 -->
            </ul>
        </td>
    </tr>
    <!-- 示例会议2 -->
    <tr>
        <td>会议名称2</td>
        <td>2024-02-01</td>
        <td>2024-04-01</td>
        <td><a href="http://www.conference2.com">会议官网2</a></td>
        <td>
            <ul>
                <li>论文3标题</li>
                <!-- 更多论文 -->
            </ul>
        </td>
    </tr>
    <!-- 更多会议 -->
</table>

</body>
</html>
