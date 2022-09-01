---
layout: post
title: Router Config helper
description: 라우터, 스위치의 Command 생성기 입니다
image: R_G/basic.jpg
date: 2022-09-01 22:50:00 +0900
tags: network tool router switch
categories: [network]
---
### **구성**
{: .no_toc }
<details open markdown="block">
 <summary>펼치기/접기</summary>
 {: .text-delta }

1. TOC
{:toc}
</details>
---
<head>
<style>
    h5 {
        line-height : 165%; 
    }
</style>
</head>

# 📎 **명령어 제작 tool**
<div style="margin-left:5%;margin-right:5%;">
<h5> 보안에 대해 공부하다보면 개발능력이 어쩔수없이 요구되는것 같습니다😂 다행스러운건 개발에도 재미를 느낀다는점..?!ㅎㅎ 본론으로 돌아가서 이번에 소개 해드릴 주제는 최근 개발한 라우터, 스위치 설정 커맨드 제작기 입니다! 네트워크망 구축/설계에 대해 공부하다 보면 어쩔수 없이 반복적으로 입력하게 되는 명령어가 생기는데 이런 명령어에 대해 굉장히 <b>숙달되신분</b>과 아직 헷갈리는 부분이 많은 <b>입문자</b> 분들이 사용하면 좋지 않을까 싶어 개발을 연습할겸 제작 해 봤는데요! 단점은 python언어로 개발했기 때문에 python없이 독립적으로 동작하진 않습니다😅</h5></div>
<br>

# **> 구성**
<img src = "/images/R_G/if_conf.jpg" width="63%" height="63%"><br>
<div style="margin-left:5%;margin-right:5%;">
<h5>GUI 구성은 위 사진과 같습니다! 아직 프로토타입에 가깝기 때문에 많은 기능은 구현하지 못했습니다😅 현재 버전에서 구현된 기능으론 인터페이스에 대한 설정 관련 입니다 :)</h5></div>
<br>
<br>
<img src = "/images/R_G/vlan_acc.jpg" width="63%" height="63%">
<div style="margin-left:5%;margin-right:5%;">
<h5 align="center"> <b>Vlan Access port 설정</b>
</h5></div>
<br><br>
<img src = "/images/R_G/vlan_trk.jpg" width="63%" height="63%">
<div style="margin-left:5%;margin-right:5%;">
<h5 align="center"> <b>Vlan Trunk port 설정</b>
</h5></div><br><br>

# 📎 [Download](https://github.com/kidchanj/shared)
<div style="margin-left:5%;margin-right:5%;">
<h5>추후 ospf, nat, iptable 등 시간이 되는대로 python언어와 더 친숙해지기 위해(?) 추가로 기능을 구현하려 합니다! 혹시 code가 궁금하시거나 사용해보고 싶으시다면 Download 링크를 통해 받아가시길 바랍니다! :)</h5><br><br>