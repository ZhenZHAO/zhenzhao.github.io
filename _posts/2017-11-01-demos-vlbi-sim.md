---
title: 'VLBI Simulator'
date: 2017-11-01
permalink: /posts/2017/11/demos-vlbi-sim/
tags:
  - VLBI
  - demos

---
To develop an integrated VLBI simulator, named VNSIM, for the VLBI research community. 
This work is initially motivated by the demand of the East Asia VLBI Networks and can also be expandable to other VLBI networks and generic interferometers.

## 设计要求

### 功能列表

- UV 覆盖, 及其相关， UV plots and UV plots within a time duration
- 参数估算，FITS fie size, bandwidth and time smearing 
- （观测）时间规划， Plot AZ-EL and Sky survey for observation schedule
- 图像参数评估，图像模拟 （dirty Beam, dirty Map) Original and Dirty Image
- 图形处理窗口， ［clean 算法］

### UI设计

- 参数设置： 参数列表，阵列复选，功能复选，
- log窗口： 时时tell当前正在处理什么内容
- image窗口： 时时显示图片结果
- 输出窗口： 一套输出结果，可导出

### 交互要求

- 数据库支持UI添加新数据
- 一次配置，全部显示
- 动态修改，动态显示

### 开发细节

- 前期：python, tkinter (个别功能用wxpython美化), sqlite
- 后期: 做成服务的形式，在SKA组的网站上在线使用



## 第一版本

project available at https://github.com/ZhenZHAO/EAVNSIM/wiki

a detailed paper is available at http://cn.arxiv.org/abs/1808.06726

Main GUI

![soft_gui](/files/demos/vlbi/soft_gui.png)

Database

![soft_gui](/files/demos/vlbi/ui_db.png)

Calculator

![soft_gui](/files/demos/vlbi/ui_cal.png)