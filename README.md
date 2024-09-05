# 한바탕 소고기 판매점 (Han ba tang)

<!--배지-->
![MIT License][license-shield] ![Repository Size][repository-size-shield] ![Issue Closed][issue-closed-shield]

<!--프로젝트 대문 이미지-->
![Project Title](./img/spring_boot_thymeleaf_title.png)

<!--프로젝트 버튼-->
 [![Readme in English][readme-eng-shield]][readme-eng-url] [![View Demo][view-demo-shield]][view-demo-url] [![Report bug][report-bug-shield]][report-bug-url] [![Request feature][request-feature-shield]][request-feature-url]

<!--목차-->
# Table of Contents
- [[1] About the Project](#1-about-the-project)
  - [Features](#features)
  - [Technologies](#technologies)
- [[2] Getting Started](#2-getting-started)
  - [Prerequisites](#prerequisites)
  - [Installation](#installation)
  - [Configuration](#configuration)
- [[3] Usage](#3-usage)
- [[4] Contribution](#4-contribution)
- [[5] Acknowledgement](#5-acknowledgement)
- [[6] Contact](#6-contact)
- [[7] License](#7-license)



# [1] About the Project
한바탕은 프리미엄 소고기 판매 사이트로, 국내 및 국외 높은 등급의 소고기를 부위 별로 판매하는 사이트 입니다.
이 프로젝트는 고품질의 소고기를 보고, 소비자가 원하는 고기를 구매할 수 있는 맞춤형 플랫폼을 제공하여 
사용자들이 소고기에 대한 설명을 확인하고 구매할 수 있게 합니다.

## Features
회원가입 및 마이페이지
- *회원 가입 / 회원 탈퇴*
- *내 정보 조회 / 수정*

로그인
- *로그인 / 로그아웃*
- *아이디/비밀번호 찾기*

메인페이지
- *slide 로 넘기면서 볼 수 있는 사진 및 영상*
- *사이드바*
- *카테고리 별 제품 목록 출력*

고객센터
- *전체 조회, 다른 사람이 작성한 비공개 글은 조회 X (본인만 가능)*
- *글 등록*
- *게시글 공개 / 비공개*

챗봇
- *팝업 기능*
- *자주 묻는 질문 클릭 → 답변 출력 (토글)*
- *ID/PW 찾기 이동 기능*

제품 상세정보
- *장바구니 담기 / 구매 버튼*
- *해당 상품 정보 보기*

- 최고 멋진 **README**를 쉽게 작성할 수 있도록 *이텔릭체*로 된 **가이드**를 제공
- 뱃지로 **언어 옵션**을 제공

## Technologies

**프론트엔드:**
- [HTML]
- [CSS]
- [JavaScript]

**백엔드:**
- [Java](https://www.java.com/en/)
- [Spring](https://spring.io/) 2.4.3
- [Maven](https://maven.apache.org/) 3.6.3
- [Mybatis](https://blog.mybatis.org/) 3.5.11
- [Lombok](https://projectlombok.org/)

**데이터베이스:**
- [Oracle](https://www.oracle.com/)

**배포:**

**기타:**
- [Git]


# [2] Getting Started
*만약 운영체제에 따라 프로그램을 다르게 동작시켜야한다면, 운영체제별로 동작 방법을 설명하세요*

## Prerequisites
*프로젝트를 동작시키기 위해 필요한 소프트웨어와 라이브러리를 나열하고 어떻게 다운받을 수 있는지 설명하세요.*

- [OpenWeather API key](https://openweathermap.org/) (무료)
- npm
```bash
npm install npm@latest -g
```

## Installation
*어떻게 이 프로젝트의 소스코드를 다운받을 수 있는지 설명하세요.*
1. Repository 클론
```bash
git clone https://github.com/LeePaDack/Hanbatang_PJ 수정해야함
```
2. NPM packages 설치
```bash
npm install
```

## Configuration
*코드의 어느 부분을 채우거나 수정해야하는지 설명하세요.*
- `config.js`에 Openweather API key를 입력
```bash
const API_KEY = "<Your API key>";
```



# [3] Usage
***스크린샷, 코드** 등을 통해 **사용 방법**과 **사용 예제**를 보여주세요. 사용 예제별로 h2 헤더로 나누어 설명할 수 있습니다.*

![usage](./img/spring_boot_diagram.png)

```java
// 몇 개의 API 사용 예제를 코드와 함께 보여주세요.
```



# [4] Contribution
기여해주신 모든 분들께 대단히 감사드립니다.[`contributing guide`][contribution-url]를 참고해주세요.
이 프로젝트의 기여하신 분들을 소개합니다! 🙆‍♀️
*이모티콘 쓰는 것을 좋아한다면, 버그 수정에 🐞, 아이디어 제공에 💡, 새로운 기능 구현에 ✨를 사용할 수 있습니다.*
- 🐞 [dev-ujin](https://github.com/): 메인페이지 버그 수정



# [5] Acknowledgement
***유사한 프로젝트의 레포지토리** 혹은 **블로그 포스트** 등 프로젝트 구현에 영감을 준 출처에 대해 링크를 나열하세요.*

- [Readme Template - Embedded Artistry](https://embeddedartistry.com/blog/2017/11/30/embedded-artistry-readme-template/)
- [How to write a kickass Readme - James.Scott](https://dev.to/scottydocs/how-to-write-a-kickass-readme-5af9)
- [Best-README-Template - othneildrew](https://github.com/othneildrew/Best-README-Template#prerequisites)
- [Img Shields](https://shields.io/)
- [Github Pages](https://pages.github.com/)



# [6] Contact
- 📧 jjuni818@naver.com
- 📋 [https://github.com/LeePaDack](https://www.github.io/contact)



# [7] License
MIT 라이센스
라이센스에 대한 정보는 [`LICENSE`][license-url]에 있습니다.



<!--Url for Badges-->
[license-shield]: https://img.shields.io/github/license/dev-ujin/readme-template?labelColor=D8D8D8&color=04B4AE
[repository-size-shield]: https://img.shields.io/github/repo-size/dev-ujin/readme-template?labelColor=D8D8D8&color=BE81F7
[issue-closed-shield]: https://img.shields.io/github/issues-closed/dev-ujin/readme-template?labelColor=D8D8D8&color=FE9A2E

<!--Url for Buttons-->
[readme-eng-shield]: https://img.shields.io/badge/-readme%20in%20english-2E2E2E?style=for-the-badge
[view-demo-shield]: https://img.shields.io/badge/-%F0%9F%98%8E%20view%20demo-F3F781?style=for-the-badge
[view-demo-url]: https://dev-ujin.github.io
[report-bug-shield]: https://img.shields.io/badge/-%F0%9F%90%9E%20report%20bug-F5A9A9?style=for-the-badge
[report-bug-url]: https://github.com/dev-ujin/readme-template/issues
[request-feature-shield]: https://img.shields.io/badge/-%E2%9C%A8%20request%20feature-A9D0F5?style=for-the-badge
[request-feature-url]: https://github.com/dev-ujin/readme-template/issues

<!--URLS-->
[license-url]: LICENSE.md
[contribution-url]: CONTRIBUTION.md
[readme-eng-url]: ../README.md



