<div align="center">

# Minjeong Cho

### Backend & AI Developer

추천시스템과 생성형 AI를 연구하고, 아이디어를 실제로 동작하는 서비스로 구현합니다.

</div>

## About Me

- FastAPI 기반 백엔드와 AI 기능을 연결해 사용자에게 전달되는 서비스를 개발합니다.
- 추천시스템의 cold-start 문제와 graph-based recommendation을 연구합니다.
- LLM, Knowledge Graph, RAG를 활용한 학습·연구 지원 도구에 관심이 있습니다.
- 실험 결과뿐 아니라 재현 가능한 코드와 실제 사용 경험까지 만드는 것을 중요하게 생각합니다.

## Tech Stack

**Backend**

<p>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Uvicorn-499848?style=flat-square" alt="Uvicorn" />
  <img src="https://img.shields.io/badge/SQLAlchemy_2-D71F00?style=flat-square&logo=sqlalchemy&logoColor=white" alt="SQLAlchemy" />
  <img src="https://img.shields.io/badge/Pydantic_v2-E92063?style=flat-square&logo=pydantic&logoColor=white" alt="Pydantic" />
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white" alt="JWT" />
</p>

**AI / ML**

<p>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
  <img src="https://img.shields.io/badge/LightGCN-6A5ACD?style=flat-square" alt="LightGCN" />
  <img src="https://img.shields.io/badge/Amazon_Bedrock-FF9900?style=flat-square&logo=amazonwebservices&logoColor=white" alt="Amazon Bedrock" />
  <img src="https://img.shields.io/badge/Claude_Haiku_4.5-D97757?style=flat-square&logo=anthropic&logoColor=white" alt="Claude Haiku" />
  <img src="https://img.shields.io/badge/RAG-4B8BBE?style=flat-square" alt="RAG" />
  <img src="https://img.shields.io/badge/Knowledge_Graph-8B5CF6?style=flat-square" alt="Knowledge Graph" />
</p>

**Database & Infrastructure**

<p>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />
  <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=flat-square&logo=amazonec2&logoColor=white" alt="EC2" />
  <img src="https://img.shields.io/badge/Amazon_S3-569A31?style=flat-square&logo=amazons3&logoColor=white" alt="S3" />
  <img src="https://img.shields.io/badge/Amazon_RDS-527FFF?style=flat-square&logo=amazonrds&logoColor=white" alt="RDS" />
  <img src="https://img.shields.io/badge/Nginx-009639?style=flat-square&logo=nginx&logoColor=white" alt="Nginx" />
</p>

**Frontend & Application**

<p>
  <img src="https://img.shields.io/badge/Next.js_15-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
  <img src="https://img.shields.io/badge/React_19-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
  <img src="https://img.shields.io/badge/Streamlit-FF4B4B?style=flat-square&logo=streamlit&logoColor=white" alt="Streamlit" />
  <img src="https://img.shields.io/badge/PySide6-41CD52?style=flat-square&logo=qt&logoColor=white" alt="PySide6" />
</p>

## Featured Projects

### [EEUM · 개념 이해를 추적하는 AI 학습 튜터](https://github.com/itsminjeong/2026-capstone-eeum)

PDF 학습자료를 Knowledge Graph로 구조화하고, 수준진단·AI 채팅·미니퀴즈·학습 리포트를 연결하는 개인화 학습 서비스입니다. **Backend**를 담당했으며 FastAPI, SQLAlchemy, PostgreSQL, AWS 인프라와 AI 기능을 연결했습니다.

`FastAPI` `PostgreSQL` `AWS Bedrock` `Knowledge Graph` `RAG`

### [recsys-agnn](https://github.com/itsminjeong/recsys-agnn)

추천시스템의 cold-start 문제를 다루는 연구·실험 프로젝트입니다. MF, GCN, LightGCN의 속성 주입 효과를 비교하고 Teacher–Student 임베딩 전이와 item-item graph를 활용한 개선 방향을 탐구합니다.

`Python` `PyTorch` `LightGCN` `Recommender Systems`

### [MultiAgent Paper Agent](https://github.com/itsminjeong/multiagent-paper-agent)

논문 검색, 요약, 기여도·한계 분석, 참고문헌 생성, 관련 코드 탐색을 하나의 흐름으로 연결한 연구 지원 도구입니다.

`Python` `OpenAI API` `Semantic Scholar API` `Streamlit`

### [Grid Overlay](https://github.com/itsminjeong/grid-overlay)

선택한 화면 영역 위에 조절 가능한 격자를 표시하는 Windows 데스크톱 도구입니다. 전역 단축키, 투명 오버레이, 클릭 통과와 사용자별 설정 저장을 지원합니다.

`Python` `PySide6` `Windows API` `PyInstaller`

## Current Focus

- Teacher–Student 기반 item cold-start 추천
- 임베딩 scale·distribution과 추천 성능의 관계
- Knowledge Graph와 RAG를 결합한 개인화 학습 경험
- 유지보수 가능한 모듈형 AI agent

