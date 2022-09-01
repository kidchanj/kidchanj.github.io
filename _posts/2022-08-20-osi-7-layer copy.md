---
layout: post
title: OSI 7 Layer
description: OSI 7계층 모델에 대한 기초 이론
image: 7layer.jpg
date: 2022-08-21 12:19:00 +0900
tags: OSI
categories: [network]
---
### **구성**
{: .no_toc }
<details open markdown="block">
 <summary>펼치기/접기</summary>
 {: .text-delta }

1. TOC
{:toc .text-delta }
</details>
---
<head>
<style>
    h5 {
        line-height : 165%; 
    }
</style>
</head>

## 📙 **OSI 7 Layer**
### **1) OSI 7계층 이란?**
><h5>국제 표준화 기구(ISO, International Organization for Standardization)에서  표준화를 위해 개발된 모델로써, 통신이 <br>일어나는 절차를 기능별로 나누어 계층적인 구조로 표현한 모델이다.</h5>

&nbsp;

### **2) 계층 구조**
<img src="/images/7layer.jpg" align="center">


|계층|기능|
|:-----:|----|
|&emsp;7계층 Application&emsp;<br>(응용 계층)|&emsp;사용자 인터페이스 계층으로 사용자의 명령을 받아주는 계층(응용 프로그램)&emsp;|
|6계층 Presentation<br>(표현 계층)| 상위계층에서 만들어진 데이터의 형태 표현 인코딩, 압축, 암호화 등에 대한 정보|
|5계층 Session<br>(세션 계층)|특정 종류(연결이 필요한 종류)의 서비스를 받을 때만 사용, 연결상태 제어|
|4계층 Transport<br>(전송 계층)|데이터 전송방식 결정, 서비스 구분(port), 필요에 따라 단편화 작업 수행|
|3계층 Network<br>(네트워크 계층)|출발지, 목적지 주소(논리적 주소)부여 => 종단 간 연결 보장|
|2계층 Data Link<br>(데이터 링크 계층)|인접 장비에 접근하기 위한 정보(물리적 주소,MAC)부여, 네트워크 환경에 맞는 정보 부여|
|1계층 Physical<br>(물리 계층)|비트 형태의 신호를 패턴을 부여하여 전기적 신호로 변경하여 전송|

<br>
<div style="margin-left:5%;margin-right:5%;">
<p><h5 align="left"> 각 계층에선 위 표에서 설명하는 기능을 수행하기 위한 정보를 Data에 담아 전송하게 되는데 이를 <b>'header'</b> 라고 합니다. 이러한 각 계층의 header 들의 정보를 담아 전송하는 Data가 실제 장비가 주고받는 Data가 됩니다.</h5></p>
</div>
<br>

### **3) Encapsulation & De-capsulation**
<div style="margin-left:3%;margin-right:3%;">
<p><h5 align="left"> 위에서 설명했듯 장비 간 Data를 주고 받을때 각 계층의 header 정보가 담기는데 실제 통신 과정에선 End device <br>사이에 수많은 장비들이 존재하고 필요로 하는 Data의 header정보의 범위가 다릅니다. 때문에 Data를 송,수신 하는 과정에서 header정보가 중구난방으로 입력돼 있다면 Data를 해석하기 위해서는 시간과 장비에서 필요로하는 성능이 올라가게 됩니다. 굉장히 비효율 적이죠, 때문에 Data를 보내거나 받을때 처리하는 과정과 절차가 있는데 이를 <b>Encapsulation(송신)</b>, <b>De-encapsulation(수신)</b> 이라고 합니다.
</h5></p>
</div>
<br>
<h5 align="center"> 작성중...</h5>