# [KDT] CJONS Project Based Learning Report

# 1. 보고서 양식 개요 및 설명

- 08.26일 cover

    일부 특수한 개발 방법론([애자일 방법론](https://www.redhat.com/ko/devops/what-is-agile-methodology), [테스트 주도 개발 방법론](https://ko.wikipedia.org/wiki/%ED%85%8C%EC%8A%A4%ED%8A%B8_%EC%A3%BC%EB%8F%84_%EA%B0%9C%EB%B0%9C) 등)을 제외하면, 소프트웨어를 체계적으로 개발하고 관리하기 위해, 개발 과정에 따른 소프트웨어의 생명 주기(Software Life Cycle)라는 것이 있습니다. 보통 6단계로 나누어지며 이는 

    - 요구사항 분석의 6단계

        요구사항 분석

        시스템 명세

        설계

        프로그래밍

        테스트

        유지보수

    의 단계를 따릅니다. 본 프로젝트에서는 이같은 소프트웨어 라이프 사이클의 구성을 일부 차용하여, **시스템의 명세와 설계~테스트까지의 단계를 압축하여 수행하고 그 결과물을 최소한의 보고서 양식으로 정리할 것을 요구**하고자 합니다. 특히, Bottom-Scratch(아무런 Backbone 아키텍쳐 없이 시작하는 프로젝트)가 아니라 나름 검증된 프레임워크와 많이 사용된 Task를 프로젝트 레벨에서 올리는 만큼 남이 만든 코드 위에 여러분들의 최적화나 창의성을 부여해야 하므로, 이같은 문서 작업은 결과물의 관리와 포트폴리오로도 활용할 수 있다는 점에서 여러분에게도 효율적일 것이라 생각됩니다.  

    ---

    추가적으로, 여러분들의 사전 지식 평가를 위해 아래와 같은 설문조사를 추가적으로 배치하였습니다. 설문에 응해주시면 감사하겠습니다.

    [https://forms.gle/H3WmFkma3vPG9qSL6](https://forms.gle/H3WmFkma3vPG9qSL6)

---

# 2. 템플릿 이용 및 세부 페이지

## 2.1. 템플릿 및 컨벤션

- 
    - 여러분들의 팀이 구성되면 팀 브랜딩과 프로젝트 전체적인 진행을 관리하는 매니저(팀장)이 기본적인 최종 문서들의 최종 버전을 검토하고 제출하는 역할을 부여받게 됩니다.
    - 사용하시는 툴은 본 문서가 작성된 Notion 앱의 편집기로 일괄적으로 통일하도록 하겠습니다.

## 2.2. 리서치-end-to-end 프로젝트

문서화(documentation)의 경우 해당 하위 문서에서 작성하기 바랍니다.

[리서치 프로젝트](https://www.notion.so/92058c847e9143729b7eba0a4d4df202)

- 팀 브랜딩-팀 구성과 코드 관리, 저와의 소통, 다른 사람이 봐도 '이 팀이 어떤 프로젝트를 하는지 알 수 있는'관련 자료를 작성하는 곳입니다.
- 선택한 주제에 대한 관련 연구, 알고리즘 등 이론적인 부분을 작성하는 부분입니다.
- 본인들만의 아이디어가 추가로 들어가면 best입니다.

### 2.2.1 개인별 페이지 모음

- 개인별 페이지

    [오송렬 의 사본](https://www.notion.so/ba50b3d74a1f413a9c3e75bb4bf0671e)

    [박성민의 사본](https://www.notion.so/a7855146b1874e258dc57a66a20bcb69)

    [홍세원의 사본](https://www.notion.so/1e8d63c476964059833f425d20cd2f5a)

    [이호세의 사본](https://www.notion.so/e79b72f41cfd4de4a507f2fbf6ccc14e)

    [김태연의 사본](https://www.notion.so/ac3fd732025a473085c3c1061c733bda)

    [장지원의 사본](https://www.notion.so/acbf2e65655747e689944394ed728ac5)

    [오창영의 사본](https://www.notion.so/ef4da838b3cf4db2928be15ec6d1ec0f)

2.3. 버전관리 및 코드매니징

- 본 github주소에 팀을 만들고 코드 매니징을 수행하시면 되겠습니다.

[K-Digital Training for GIST supported by CJ Olive Networks](https://github.com/CJOGIST)

- 선생님들 github 아이디

    [VCS_ID](https://www.notion.so/2c51e196b7e445a4a0af2bab36b02079)

2.4. 최종성과물 및 포스트프로덕션

- 최종 발표 보고 PPT 첨부
    - 발표내용은 이하 내용을 포함해야 합니다
        - 프로젝트 주제
            - 팀 구성 및 역할
            - 관련 연구 및 사용된 알고리즘의 이론적 정의
        - (팀원별) 기여 내용(이하 내용이 모두 들어가 있을 필요는 없습니다. 단, 도메인 적용은 필수)-수행절차 및 방법(기간별)
            - 도메인 적용
            - 성능 개선
            - XAI
        - 사용한 데이터셋
        - 벤치마크 성능(정량적 평가)
        - 느낀 점 및 정성적 평가
- 학생분들의 수강 만족도를 조사하기 위해 이하의 설문을 프로젝트 최종일에 제출해 주시기 바랍니다.(링크 추후 생성)

# 설문조사_post_session

[[KDT] Post-Session 설문지](https://forms.gle/vgmuZsgn5eXgnn8A8)

---

## 프로젝트_1+2

각자 개인별로 완수했던 수업과 관련된 내용에 대해 적어서 올려주시면 감사하겠습니다.

내용 및 목차는 전혀 신경 쓰지 않아도 됩니다.

[[별첨2] 팀별 프로젝트 수행 결과 작성 양식.pptx](%5BKDT%5D%20CJONS%20Project%20Based%20Learning%20Report%20af2b2302d8a24a47bbd9704432da7f3b/%EB%B3%84%EC%B2%A82_%ED%8C%80%EB%B3%84_%ED%94%84%EB%A1%9C%EC%A0%9D%ED%8A%B8_%EC%88%98%ED%96%89_%EA%B2%B0%EA%B3%BC_%EC%9E%91%EC%84%B1_%EC%96%91%EC%8B%9D.pptx)

## 다 작성하신 분은 바로 여기에 업데이트 해 주세요!

만드신 ppt/pdf파일은 드래그 & 드롭으로 업로드가 됩니다

### 3. 참고사항

---

[[강사] 데일리 체크리스트_보고자료](https://www.notion.so/_-3ef679bdac4b4e21aac5d04fd8cc0423)

[[CJO]교육 커리큘럼 수업계획서](https://www.notion.so/CJO-b65495d8cc4e417bac5ba9124b3fbe31)

[레퍼런스-참고용](https://www.notion.so/597cf11dd57a460c97a85b6a1156e6ce)

[개인발표](https://www.notion.so/abccea0cd5b94fe29da14a09ef6ef85a)

[교육일정](https://www.notion.so/834a8ebb76274976aecab4c63215b638)

---
