<div align="center">

<img src="./assets/onequery-banner.png" alt="OneQuery — 흩어진 API를 자연어 질문 하나로" width="100%" />

<br/>

**여러 시스템에 나뉘어 있는 데이터를, AI 에이전트가 필요한 것을 스스로 찾아<br/>
가져와 합치고 보고서까지 만들어 주는 대화형 데이터 활용 플랫폼**

<br/>

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![FastAPI](https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![DuckDB](https://img.shields.io/badge/DuckDB-FFF000?style=flat-square&logo=duckdb&logoColor=black)
![Claude](https://img.shields.io/badge/Claude-D97757?style=flat-square&logo=anthropic&logoColor=white)

</div>

<br/>

## 👋 **MEMBER**

<table align="center" style="font-weight : bold">
    <tr>
        <td align="center">
            <a href="https://github.com/chaerin1ee">
                <img alt="이채린" src="https://avatars.githubusercontent.com/chaerin1ee" width="180" />
            </a>
        </td>
        <td align="center">
            <a href="https://github.com/jueundev">
                <img alt="최주은" src="https://avatars.githubusercontent.com/jueundev" width="180" />
            </a>
        </td>
    </tr>
    <tr>
        <td align="center"><b>이채린</b></td>
        <td align="center"><b>최주은</b></td>
    </tr>
    <tr>
        <td align="center"><sub>개발 · 데이터 검증</sub></td>
        <td align="center"><sub>기획 · 설계 · 개발</sub></td>
    </tr>
</table>

<br/>

## 🎯 **PROBLEM**

> 질문 하나에 세 개 부서, 며칠

서비스가 늘어날수록 데이터는 시스템마다 쪼개집니다.

- 개발자는 같은 형태의 데이터 추출 요청에 매주 시간을 씁니다
- 실무자는 컬럼명과 코드 체계가 제각각인 파일을 손으로 맞추다가 누락과 중복을 반복합니다
- 결정권자는 회의 중 궁금한 것을 물어도 며칠을 기다립니다

<br/>

## 💡 **SOLUTION**

> 데이터를 옮기지 말고, 인터페이스를 AI의 도구로

데이터를 한곳에 모으는 대신, **각 서비스가 이미 제공하는 인터페이스(OpenAPI/Swagger)를
AI가 쓸 수 있는 도구로 자동 전환**합니다. 원천 서비스는 **코드 한 줄 바꾸지 않습니다.**

```text
   Swagger 주소 등록  ─────►  기능 자동 수집 · 분류 · 색인
                                      │
   자연어 질문        ─────►  필요한 기능 선택 · 실행
                                      │
                              여러 시스템 데이터 병합
                                      │
                                      ▼
                          엑셀 · 보고서 · 차트
```

<br/>

## ⚙️ **HOW IT WORKS**

<table>
  <tr><th width="110">단계</th><th>하는 일</th></tr>
  <tr><td align="center"><b>수집</b></td><td>등록된 Swagger 문서를 읽어 오퍼레이션 단위로 분해합니다</td></tr>
  <tr><td align="center"><b>분류</b></td><td>각 기능이 조회인지 변경인지 판정해 정책 등급을 매깁니다</td></tr>
  <tr><td align="center"><b>색인</b></td><td>자연어로 찾을 수 있도록 기능 설명을 임베딩해 검색 가능한 형태로 둡니다</td></tr>
  <tr><td align="center"><b>계획</b></td><td>질문을 읽고 어떤 기능을 어떤 순서로 부를지 에이전트가 정합니다</td></tr>
  <tr><td align="center"><b>실행</b></td><td>페이지네이션 · 기간 분할 · 인증을 처리하며 데이터를 모읍니다</td></tr>
  <tr><td align="center"><b>집계</b></td><td>모인 데이터를 합쳐 답변과 산출물을 만듭니다</td></tr>
</table>

> [!IMPORTANT]
> **변경 계열 기능은 사람이 승인하기 전에는 실행되지 않습니다.**
> 조회는 자동, 변경은 승인, 금지는 차단 — 이 구분이 시스템 전체를 관통하는 원칙입니다.

<br/>

## 🧭 **PRINCIPLE**

- **원천을 건드리지 않는다** — 연동을 위해 상대 서비스에 코드를 요구하지 않습니다
- **되돌릴 수 없는 일은 묻는다** — 조회와 변경을 같은 취급하지 않습니다
- **실측으로 말한다** — 「동작한다」고 쓰기 전에 실제로 돌려 보고 수치를 남깁니다
- **안 되는 것을 적는다** — 한계를 숨기는 것보다 아는 편이 쓸모 있습니다

<br/>

## 📂 **REPOSITORIES**

> [!NOTE]
> 이 조직의 프로젝트 저장소는 **모두 비공개**입니다.
> 다루는 주제의 성격상 시스템 주소나 접속 정보가 밖으로 나가지 않도록
> 처음부터 비공개로 두고 작업했습니다.

| 저장소 | 내용 |
|---|---|
| `OneQuery_Submission` | 제출본 |
| `OneQuery_FULL` | 전체 아카이브 — 기획 문서 · 백엔드 · 프론트엔드 · 목 서비스 |
| `OneQuery_BE` · `OneQuery_FE` | 용도별로 나눈 사본 |
| `OneQuery_swagger` | 개발 · 검증용 테스트 서버 |

<br/>

<div align="center">

**OneQuery Lab**

<sub>2026 SK AI 해커톤 · AI Solution 리그</sub>

</div>
