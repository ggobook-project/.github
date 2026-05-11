<div align="center">
  <br />
  <h2>🐢 GGoBook (꼬북) 📖</h2>
  <p><b>웹툰·웹소설 통합 AI 플랫폼, 함께 읽고 함께 쓰는 이야기</b></p>
  <br />
</div>

<div align="center">
  <img src="https://img.shields.io/badge/React%2019-61DAFB?style=for-the-badge&logo=react&logoColor=black">
  <img src="https://img.shields.io/badge/Vite-646CFF?style=for-the-badge&logo=vite&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Java%2021-007396?style=for-the-badge&logo=java&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Boot_3-6DB33F?style=for-the-badge&logo=springboot&logoColor=white">
  <img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=for-the-badge&logo=springsecurity&logoColor=white">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white">
  <img src="https://img.shields.io/badge/Redis-DC382D?style=for-the-badge&logo=redis&logoColor=white">
  <br>
  <img src="https://img.shields.io/badge/Python%203.11-3776AB?style=for-the-badge&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white">
  <img src="https://img.shields.io/badge/AWS_EC2-FF9900?style=for-the-badge&logo=amazonec2&logoColor=white">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white">
</div>

<br>

### 📦 레포지토리 (Repositories)
GGoBook은 MSA(Microservices Architecture) 관점을 고려하여 총 3개의 레포지토리로 분리하여 관리하고 있습니다.
* ⚙️ **Backend Repository**: https://github.com/ggobook-project/ggobook-backend
* 🎨 **Frontend Repository**: https://github.com/ggobook-project/ggobook-frontend
* 🤖 **AI (LLM) Repository**: https://github.com/ggobook-project/ggobook-ai

---

### 👨‍💻 팀원 소개 (Untitled)

<table>
  <thead>
    <tr>
      <th width="10%" align="center">포지션</th>
      <th width="10%" align="center">이름</th>
      <th width="60%" align="center">담당 업무</th>
      <th width="20%" align="center">Github</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td align="center"><b>팀장</b></td>
      <td align="center"><b>김승경</b></td>
      <td>프로젝트 총괄, 포트원 결제, 작품/회차 관리, 평행우주 외전, 꼬북이 챗봇, AWS S3 및 배포</td>
      <td align="center"><a href="https://github.com/iamsugu0106">@iamsugu0106</a></td>
    </tr>
    <tr>
      <td align="center"><b>팀원</b></td>
      <td align="center"><b>강한수</b></td>
      <td>관리자 시스템, 작품 심사(SSE 알림), 회원 정지/신고, AI 검수, 릴레이 소설 백엔드 (Redis 분산 락)</td>
      <td align="center"><a href="https://github.com/dlive838-maker">@dlive838-maker</a></td>
    </tr>
    <tr>
      <td align="center"><b>팀원</b></td>
      <td align="center"><b>김재민</b></td>
      <td>프론트엔드 아키텍처 및 전체 UI/UX, Typecast TTS API 연동, 마이페이지, 릴레이/로그인 뷰</td>
      <td align="center"><a href="https://github.com/woals10006-commits">@woals10006-commits</a></td>
    </tr>
    <tr>
      <td align="center"><b>팀원</b></td>
      <td align="center"><b>임성훈</b></td>
      <td>일반/소셜(OAuth2) 로그인, 댓글/답글, 평점/찜/좋아요, 마이페이지 백엔드 API 설계</td>
      <td align="center"><a href="https://github.com/sh1575">@sh1575</a></td>
    </tr>
  </tbody>
</table>

---

### 💡 기획 배경 및 목적
매년 급성장하는 웹툰·웹소설 시장에서 분리된 콘텐츠 소비 환경을 통합하고자 기획되었습니다. **GGoBook**은 독자와 작가를 하나의 플랫폼으로 연결하며, 단순한 열람을 넘어 **AI 챗봇, TTS 오디오북, 릴레이 소설, 평행우주 외전** 등 능동적이고 개방적인 창작 및 소비 생태계를 제공합니다.

---

### 🚀 주요 기능 (Key Features)

#### 🤖 AI 기능 결합 (Gemini & Typecast)
* **꼬북이 챗봇:** 사용자의 독서 취향(DB)을 실시간으로 분석하여 맞춤형 작품 추천 및 FAQ 제공
* **평행우주 외전:** 독자가 직접 "만약에..?"라는 가정을 입력하면 원작 세계관을 반영한 500자 외전 스토리 즉시 생성
* **멀티보이스 TTS:** AI가 자동으로 대사와 서술을 분리하여 화자별 목소리로 스트리밍 재생(배속 조절 지원)

#### ✍️ 릴레이 소설 및 창작 지원
* **협업 창작:** 누구나 주제를 등록하고 순서대로 소설을 이어 쓰는 참여형 게시판
* **예약 업로드 & 관리:** 작가를 위한 회차별 예약 업로드 및 상태 관리 (DRAFT → PUBLISHED)
* **AI 대사 자동 변환:** 텍스트 원고 등록 시 멀티보이스 TTS를 위한 포맷으로 자동 변환

#### 💳 결제 및 통합 관리
* **포인트 결제:** 포트원(PortOne) V1 연동을 통한 유료 회차 결제 시스템
* **통합 관리자 모드:** 작품 심사(승인/반려), 회차 블라인드, 회원 정지, 공지사항 및 TTS 목소리 관리
* **실시간 알림(SSE):** 관리자의 작품 심사 결과를 작가에게 실시간 Push 알림으로 전송

---

### 📸 프로젝트 시연 (Demo Video)

각 이미지를 클릭하면 해당 기능의 유튜브 시연 영상으로 이동합니다.

| 01. 메인페이지 & 꼬북 AI | 02. 회원가입 & 로그인 |
| :---: | :---: |
| [![시연 영상 1](https://img.youtube.com/vi/aoGZK8Dv_Wc/mqdefault.jpg)](https://youtu.be/aoGZK8Dv_Wc) | [![시연 영상 2](https://img.youtube.com/vi/c-ex_8DJNUA/mqdefault.jpg)](https://youtu.be/c-ex_8DJNUA) |
| 파도 배경 랜딩 화면 및<br>Gemini API 기반 맞춤형 챗봇 | OAuth2 소셜 로그인 및<br>안전한 일반 회원가입 프로세스 |

| 03. 마이페이지 & 작품 등록 | 04. 포인트 결제 시스템 |
| :---: | :---: |
| [![시연 영상 3](https://img.youtube.com/vi/FWNMFbMQqkE/mqdefault.jpg)](https://youtu.be/FWNMFbMQqkE) | [![시연 영상 4](https://img.youtube.com/vi/1O4uTDgLyi8/mqdefault.jpg)](https://youtu.be/1O4uTDgLyi8) |
| 사용자 활동 통합 관리 및<br>작가의 작품/회차 업로드 | 포트원 연동을 통한 포인트 충전 및<br>유료 회차 구매 |

| 05. 웹툰 & 웹소설 뷰어 | 06. 릴레이 소설 |
| :---: | :---: |
| [![시연 영상 5](https://img.youtube.com/vi/66q7e0tLGnI/mqdefault.jpg)](https://youtu.be/66q7e0tLGnI) | [![시연 영상 6](https://img.youtube.com/vi/SnzyNI7bKQE/mqdefault.jpg)](https://youtu.be/SnzyNI7bKQE) |
| 멀티보이스 TTS 오디오 청취 및<br>평행우주 외전 생성 | 여러 작가가 동시에 참여하는<br>협업 창작 시스템 |

| 07. 관리자 통합 운영 |
| :---: |
| [![시연 영상 7](https://img.youtube.com/vi/ZbXTrw2mecg/mqdefault.jpg)](https://youtu.be/ZbXTrw2mecg) |
| 작품 검수, 회원 정지/신고 처리 및<br>AI 블라인드 요약 기능 |

---

### 🛠 트러블 슈팅 (Trouble Shooting)

**1. 결제 시스템의 Race Condition 방어**
* **문제:** 다수의 결제 요청이 동시에 발생할 경우 잔액이 중복으로 차감되거나 갱신 손실(Lost Update)이 발생할 위험.
* **해결:** `Wallet` 엔티티에 낙관적 락(`@Version`)을 적용하고, `Payment` 검증 시 비관적 락(`PESSIMISTIC_WRITE`)을 걸어 동시성 문제 해결 및 데이터 정합성 확보.

**2. 릴레이 소설 동시 작성 충돌 방지**
* **문제:** 여러 유저가 동시에 "이어쓰기"를 클릭 시 순번(`entryOrder`)이 중복 생성되는 문제.
* **해결:** Redis 분산 락(Distributed Lock)을 활용해 원자적으로 제어하고, 1분 단위 하트비트 연장 및 최대 30분 초과 시 좀비 락을 강제 회수하는 안정적 로직 구축.

**3. TTS 청크 크기 최적화 및 AI Fallback**
* **문제:** Typecast API에 텍스트 전체를 한 번에 요청 시 응답 지연으로 재생이 늦어짐. 또한 Gemini API 다운 시 대사 분리 기능이 마비됨.
* **해결:** 본문을 800자 단위의 **청크로 분할하여 순차 스트리밍**함으로써 첫 음성 재생 시간을 대폭 단축. Gemini API 장애 시 정규식 기반 패턴으로 자동 폴백(Fallback) 처리하여 무중단 운영 확보.
