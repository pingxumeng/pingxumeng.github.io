---
layout: post
title: Maven pluginManagement
---
pluginManagement 是用来管理module的插件的，一般用于parent pom，在parent pom中管理所有moduel的插件。如果不是子module不应该加。否则会导致插件工作不正常，不能正常执行插件的goal。
参考:[stackoverflow answer](http://stackoverflow.com/questions/10483180/maven-what-is-pluginmanagement)
