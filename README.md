# SDGs-for-Universities-in-South-Korea

## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Features](#features)
* [Visualization - Dashboard](#screenshots)
* [Usage](#usage)
* [Project Status](#project-status)
* [Room for Improvement](#room-for-improvement)
* [Contact](#contact)
<!-- * [License](#license) -->


## General Information
paper:
https://www.springerprofessional.de/en/advances-in-computer-science-and-ubiquitous-computing/25444280?tocPage=1


(CSA 2022)


SDGs(Sustainable Development Goals)는 UN에서 전 세계가 지속가능한 발전을 위해 2030년까지 달성하기로 합의한 목표이다. 전 세계의 다양한 이해관계자들은 해당 목표들을 달성하도록 요구받고 있으며, 대학 또한 사회 내의 중요 이해관계자로서 SDGs에 대한 적극적인 이행을 요구받고 있다. 위와 같은 움직임에 발맞춰, 다수의 해외 대학에서는 매년 SDGs 이행 여부에 대한 보고서를 발간하고 있으며, 기존의 대학 영향력 평가기관에서도 SDGs 항목을 평가 기준에 포함하려는 움직임이 늘고 있다. 하지만 현재 국내 대학은 전체적인 지표에서 종합평가보다 SDGs 관련 이행점수가 부족한 모습을 보이고 SDGs 보고서를 발행하는 대학 또한 현저히 부족한 상황이다. 따라서 본 논문에서는 국내 대학의 SDGs 이행에 도움을 줄 수 있는 서비스의 필요성을 인지하고 해당 서비스 개발 내용에 대해 설명한다. 
기존 SDGs 관련 연구들은 주로 국가적, 기업적 차원에서 SDGs 이행 방안을 논한 바 있다. SDGs와 대학을 연계해 다룬 논문이 존재하긴 하나, 해당 논문도 SDGs에 대한 교육을 담당하는 기관으로써 대학을 바라보는 것이지, SDGs의 이행 주체로 대학을 다루지는 않는다. 또한, 자연어 처리 기술을 활용하여 특정 도메인의 주제를 분류하는 서비스를 구축한 선행 연구가 존재한다. 본 연구에서는 텍스트 분류 모델을 활용하되, 단순 주제 분류를 넘어 대학의 SDGs 이행 정도를 분석하고 관련 활동 이행을 지원하는 서비스를 구축하고자 하였다.


## Technologies Used
- D3.js
- KoBERT
- Google PEGASUS
- textrank
- KEYBERT


## Features
![image](https://user-images.githubusercontent.com/113409289/196021743-ba93998e-acf4-4057-99f8-ab15a3de57a7.png)


## Screenshots
<img width="349" alt="image" src="https://user-images.githubusercontent.com/113409289/196021757-f57012d1-5e9d-474b-b3b8-7ad6e7f13f71.png">

해당 시스템을 바탕으로 구현한 SDGs 분석 대시보드

Bar chart : THE(영국 글로벌 대학 평가기관)가 발표한 2022년도 세계대학 영향력 평가점수 및 3개년 점수 추이
Pie Chart : 자동분류모델을 통해 도출한 5가지 항목별 뉴스 기사의 비율
Bar chart2 : 부문별 대학의 Impact Rankings 점수와 국내 전체 대학 및 해외 전체 대학의 평균 점수 비교
Bar chart2(keyword):  TextRank와 KeyBERT 기반의 키워드 분포
Benchmark Cases : 해당 대학에 없는 타 대학들의 키워드 기반 대학별로 참고할 수 있는 사례 제시

## Usage

해당 시스템은 분석 대상으로 선정된 국내 대학교가 SDGs에 대한 활동들을 효율적으로 점검할 수 있도록 분석 결과를 대시보드 형태로 제시하고, 관련 활동을 계획할 때 참고할 만한 사례들을 추가적으로 제공한다. 나아가 본 시스템은 분석 대상으로 선정되지 않은 국내 대학들의  SDGs 활동에 대한 인식 제고 및 관련 계획 수립의 동기로도 작용할 것으로 기대한다. 


## Project Status
Project is: _complete_ / _no longer being worked on_. 


## Room for Improvement

- 자동화

## Contact
-feel free to contact me! (summercheriy@gmail.com)


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
