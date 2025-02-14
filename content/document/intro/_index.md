---
title: OpenCFD 介绍
# linkTitle: Data Science
summary: OpenCFD简要介绍
date: '2023-09-18'
type: book
tags:
  - by 李新亮
---

## 简介

OpenCFD软件是中国科学院力学研究所李新亮研究员课题组开发的一套高精度计算流体力学软件。该软件集成了课题组自行开发的系列高精度差分格式及当前流行的多种高精度差分格式，其最高计算精度最高可达7阶，主要用于湍流及燃烧直接数值模拟、大涡模拟等高分辨率模拟。此外，该软件具有非常强的并行性能，可支持上百亿网格，数十万CPU核心以及数万块GPU卡超大规模异构并行.
 
OpenCFD软件是当前应用最为广泛的可压缩湍流高分辨率数值模拟软件之一，目前已得到国内外200余家用户使用。获2022年度中国空气动力学会科学技术一等奖（自然科学类），获得陕西省科学技术奖二等奖（2018）三等奖（2013）等奖项。

OpenCFD软件由若干独立的求解器（模块）构成，包括：
- `OpenCFD-SC` :  高精度有限差分求解器，主要用于湍流等复杂流动的直接数值模拟(DNS)、大涡模拟（LES）等高分辨率计算；
- `OpenCFD-EC`: 多块结构网格有限体积求解器，主要用于工程复杂流场计算；
- `OpenCFD-Comb`: 化学反应流动高精度差分求解器，主要用于化学反应流场的高分辨率计算；
- `OpenCFD-SCU`: OpenCFD-SC的GPU版。 支持上万块GPU卡的大规模并行

## 所获荣誉

- 2022年度中国空气动力学会科学技术一等奖（自然科学类）；
- 2018年度陕西省科学技术二等奖
- 2013年度陕西省科学技术三等奖
- 2015年度全国并行应用挑战赛“最佳应用奖”
- 2020年度中科院“先导杯”并行应用大奖赛开放赛题一等奖；
- 2019年度中国科学院信息化优秀案例；
- 2020年度国家超算广州中心“天河之星”优秀应用奖；
- 2018年度国家超算天津中心“天河应用创新优秀奖”
- 2013年度中国科学院超算中心“最佳应用奖”