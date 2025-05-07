---
title: |-
  <group id="content" extype="content"><group id="paragraph-101"><trans-unit id="p101" translate="no" xml:space="preserve" restype="x-metadata">
            <source>演習の手順</source>
          </trans-unit><group id="sentence-101"><trans-unit id="101" translate="yes" xml:space="preserve" restype="x-metadata">
            <source>演習の手順</source>
          </trans-unit></group></group><group id="paragraph-102"><trans-unit id="p102" translate="no" xml:space="preserve">
            <source>演習</source>
          </trans-unit><group id="sentence-102"><trans-unit id="102" translate="yes" xml:space="preserve">
            <source>演習</source>
          </trans-unit></group></group><group id="paragraph-103"><trans-unit id="p103" translate="no" xml:space="preserve">
            <source>このページには、<bpt id="p1">[</bpt>Microsoft Learn<ept id="p1">] の Microsoft スキルアップ コンテンツに関連付けられている演習が記載されています (https://learn.microsoft.com)</ept></source>
          </trans-unit><group id="sentence-103"><trans-unit id="103" translate="yes" xml:space="preserve">
            <source>このページには、<bpt id="p1">[</bpt>Microsoft Learn<ept id="p1">] の Microsoft スキルアップ コンテンツに関連付けられている演習が記載されています (https://learn.microsoft.com)</ept></source>
          </trans-unit></group></group><group id="paragraph-104"><trans-unit id="p104" translate="no" xml:space="preserve">
            <source>{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %} {% for activity in labs  %}</source>
          </trans-unit><group id="sentence-104"><trans-unit id="104" translate="yes" xml:space="preserve">
            <source>{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %} {% for activity in labs  %}</source>
          </trans-unit></group></group><group id="paragraph-105"><trans-unit id="p105" translate="no" xml:space="preserve">
            <source><bpt id="p1">[</bpt>{{ activity.lab.title }}<ept id="p1">]({{ site.github.url }}{{ activity.url }})</ept> {% endfor %}</source>
          </trans-unit><group id="sentence-105"><trans-unit id="105" translate="yes" xml:space="preserve">
            <source><bpt id="p1">[</bpt>{{ activity.lab.title }}<ept id="p1">]({{ site.github.url }}{{ activity.url }})</ept> {% endfor %}</source>
          </trans-unit></group></group></group>
permalink: index.html
layout: home
---

# Exercises

This page lists exercises associated with Microsoft skilling content on <bpt id="p1">[</bpt>Microsoft Learn<ept id="p1">](https://learn.microsoft.com)</ept>

{% assign labs = site.pages | where_exp:"page", "page.url contains '/Instructions/Labs'" %} {% for activity in labs  %}
- <bpt id="p1">[</bpt>{{ activity.lab.title }}<ept id="p1">]({{ site.github.url }}{{ activity.url }})</ept> {% endfor %}

