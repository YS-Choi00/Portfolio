# **최윤석 포트폴리오**

# 👋 About Me

안녕하세요! 데이터와 인공지능을 통해 실질적인 가치를 창출하는 것을 목표로 하는 AI 개발자입니다.  
테이블 데이터, 자연어 처리(NLP), LLM, RAG 등 다양한 분야에 관심을 가지고 연구 및 프로젝트를 진행하고 있습니다.  
끊임없이 학습하고, 새로운 기술을 실제 문제 해결에 적용하는 것을 좋아합니다.

+ ## **학력**
  + #### 2023년 03월 ~ 2024년 8월 : 공학 석사(서울시립대학교 전자전기컴퓨터공학 전공, 도시빅데이터융합전공 이수)
  + #### 2019년 03월 ~ 2023년 2월 : 공학사(서울시립대학교 전자전기컴퓨터공학부)

---
+ ## **기술 스택**
<img src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=C&logoColor=white">

<img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=MySQL&logoColor=white">

<img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=Jupyter&logoColor=white"><img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=Python&logoColor=white"><img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=PyTorch&logoColor=white"><img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=TensorFlow&logoColor=white">
---
+ ## **진행한 프로젝트**
  1. #### 연관단어 검색기
      <details>
        <summary>자세히</summary>
      
      + 개요
        +  고유명사 수준의 검색어에 대하여 의미적으로 연관된 다양한 고유명사를 주제별로 분류하여 보여주는 시스템
        +  본 시스템 구현을 위해서, BERT를 활용한 품사 분석, 개체명 분석 그리고 뉴스 기사를 통해 학습한 단어간 코사인 유사도 분석을 통해 입력 단어와 의미적으로 연관된 고유명사 단어가 인명, 지명, 기관명 등의 주제로 구분되어 연관도 순으로 출력되도록 함
        +  아래의 그림은 연관단어 검색기의 UI를 나타낸 것임
            +  입력단어로 손흥민을 넣어 검색하면, 손흥민과 관련있는 단어들을 인명, 지명, 기관명으로 분류해서 보여줌
       
          
          ![화면 캡처 2024-09-05 191044](https://github.com/user-attachments/assets/3b327f3c-fb93-49f8-aa04-f77da03e1164)
      + 사용한 프로그래밍 언어
        + Python
      + [연관단어 검색기 코드](https://github.com/uos-dmlab/Named-Entiry-Classification/tree/master/code)
      + 프로젝트 실적
        + [국내 학술대회 - 2022년 한국전자거래학회_춘계학술대회 발표](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/%EC%97%B0%EA%B4%80%EB%8B%A8%EC%96%B4%20%EA%B2%80%EC%83%89%EA%B8%B0/2022_%ED%95%9C%EA%B5%AD%EC%A0%84%EC%9E%90%EA%B1%B0%EB%9E%98%ED%95%99%ED%9A%8C_%EC%B6%98%EA%B3%84%ED%95%99%EC%88%A0%EB%8C%80%ED%9A%8C_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
      </details>
  2. #### 정형 테이블 데이터셋에 대한 딥러닝 기반 데이터 융합 기술 개발(CNE-Join기법)
      <details>
        <summary>자세히</summary>
        
      + 개요
        + 컬럼명 임베딩과 개체명 인식 기법을 통합하여 자동으로 조인 융합 가능한 테이블을 찾아내는 기법
        + 컬럼명 임베딩을 위해서 FastText 임베딩 모델을, 개체명 인식을 위해서 BERT 임베딩 모델을 사용함
        + 사용자에게 입력으로 다수의 테이블 데이터를 입력받으면, 그에 대한 출력으로 사용자에게 조인 가능한 테이블쌍과 조인의 기준이 되는 컬럼쌍을 제공함
        + 아래의 그림은 CNE-Join과 추후 설명할 N-Join-Pair가 합쳐진 아키텍처임     
          ![image](https://github.com/user-attachments/assets/a7a2ba75-de34-4c1d-870c-9286c5a42086)
      + 사용한 프로그래밍 언어
        + Python
      + [CNE-Join 코드 및 실행 방법](https://github.com/uos-dmlab/Structured-Data-Embedding/tree/master)
      + 프로젝트 실적
        + [국내 학술대회 - 2023년 한국 인공지능 학술대회 발표](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2023_%ED%95%9C%EA%B5%AD%20%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%20%ED%95%99%EC%88%A0%EB%8C%80%ED%9A%8C_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
        + [서울시립대학교 석사 학위논문](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/%ED%95%99%EC%9C%84%EB%85%BC%EB%AC%B8_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
        + [국내 저널(KCI 우수등재지) - 2024년 한국전자거래학회지 8월호 논문 게재](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2024_%ED%95%9C%EA%B5%AD%EC%A0%84%EC%9E%90%EA%B1%B0%EB%9E%98%ED%95%99%ED%9A%8C%EC%A7%80_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
        + [특허 제 10-2648215호 데이터셋 융합 가능 여부 판단 장치 및 방법 출원](https://github.com/YS-Choi00/Portfolio/blob/main/%ED%8A%B9%ED%97%88/CNE-Join%EA%B4%80%EB%A0%A8%20%ED%8A%B9%ED%97%88.pdf)
        + [프로그램 등록번호 C-2023-045822 - 정형 데이터에 대한 자동 조인 융합 시스템 등록](https://www.cros.or.kr/psnsys/cmmn/infoPage.do?w2xPath=/ui/twc/sch/regInfSerc/regInfSercDtl.xml)
      </details>
  3. #### 정형 테이블 데이터셋에 대한 딥러닝 기반 데이터 융합 기술 개발(N-Join-Pair기법)
      <details>
        <summary>자세히</summary>
        
      + 개요
        + CNE-Join 결과로 얻은 조인 융합 가능한 테이블쌍을 활용해 조인 융합 가능한 3개 이상의 테이블 데이터 조합들을 찾아내고, 이들을 조인 테이블과 조인에 사용된 소스 테이블간 코사인 유사도 값을 기준으로 랭킹하는 기법
        + CNE-Join의 출력으로 얻은 조인 융합 가능한 테이블쌍을 입력받으면, 그에 대한 출력으로 3개 이상의 조인 가능한 테이블 조합을 랭킹을 매겨 사용자에게 제공한다
      + 사용한 프로그래밍 언어
        + Python
      + [N-Join-Pair 코드 및 실행 방법](https://github.com/uos-dmlab/Structured-Data-Embedding/tree/master)
      + 프로젝트 실적
        + [국제 학술대회 - 2024년 WITC 발표](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2024_WITC_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
        + [서울시립대학교 석사 학위논문](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/%ED%95%99%EC%9C%84%EB%85%BC%EB%AC%B8_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
        + [국내 저널(KCI 우수등재지) - 2024년 한국전자거래학회지 8월호 논문 게재](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2024_%ED%95%9C%EA%B5%AD%EC%A0%84%EC%9E%90%EA%B1%B0%EB%9E%98%ED%95%99%ED%9A%8C%EC%A7%80_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
      </details>
---
+ ## **Publication**
  + [국내 학술대회 - 2022년 한국전자거래학회_춘계학술대회 - 뉴럴 임베딩 기반 주제별 고유명사 연관어 탐색 시스템 개발](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/%EC%97%B0%EA%B4%80%EB%8B%A8%EC%96%B4%20%EA%B2%80%EC%83%89%EA%B8%B0/2022_%ED%95%9C%EA%B5%AD%EC%A0%84%EC%9E%90%EA%B1%B0%EB%9E%98%ED%95%99%ED%9A%8C_%EC%B6%98%EA%B3%84%ED%95%99%EC%88%A0%EB%8C%80%ED%9A%8C_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
  + [국내 학술대회 - 2023년 한국 인공지능 학술대회 - 컬럼 임베딩과 개체명 인식을 통합한 조인 가능한 데이터셋 검색](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2023_%ED%95%9C%EA%B5%AD%20%EC%9D%B8%EA%B3%B5%EC%A7%80%EB%8A%A5%20%ED%95%99%EC%88%A0%EB%8C%80%ED%9A%8C_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
  + [국제 학술대회 - 2024년 WITC - Joinable Tabular Data Search with Table Embedding](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2024_WITC_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
  + [서울시립대학교 석사 학위논문](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/%ED%95%99%EC%9C%84%EB%85%BC%EB%AC%B8_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
  + [국내 저널(KCI 우수등재지) - 2024년 한국전자거래학회지 8월호 - 뉴럴 임베딩 기술을 활용한 정형 데이터의 자동 조인 융합 기법](https://github.com/YS-Choi00/Portfolio/blob/main/%EB%85%BC%EB%AC%B8/CNE-Join%20%2B%20N-Join-Pair/2024_%ED%95%9C%EA%B5%AD%EC%A0%84%EC%9E%90%EA%B1%B0%EB%9E%98%ED%95%99%ED%9A%8C%EC%A7%80_%EC%B5%9C%EC%9C%A4%EC%84%9D.pdf)
  + [특허 제 10-2648215호 - 데이터셋 융합 가능 여부 판단 장치 및 방법](https://github.com/YS-Choi00/Portfolio/blob/main/%ED%8A%B9%ED%97%88/CNE-Join%EA%B4%80%EB%A0%A8%20%ED%8A%B9%ED%97%88.pdf)
  + [프로그램 등록번호 C-2023-045822 - 정형 데이터에 대한 자동 조인 융합 시스템](https://www.cros.or.kr/psnsys/cmmn/infoPage.do?w2xPath=/ui/twc/sch/regInfSerc/regInfSercDtl.xml)
