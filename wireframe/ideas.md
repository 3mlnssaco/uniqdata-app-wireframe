# UniQdata 앱 와이어프레임 디자인 아이디어

> **목적**: 피수집자(개인)용 모바일 앱 와이어프레임의 디자인 방향 결정

---

## 앱 특성

- **사용자**: 일반인 (건강 데이터 제공자)
- **핵심 가치**: 데이터 입력 → 보상, 건강 데이터 축적
- **주요 기능**: 데이터 입력, 연구 참여, 보상 관리
- **톤앤매너**: 신뢰, 간결, 보상 동기부여

---

## 디자인 아이디어

<response>
<text>
### Idea 1: Clinical Trust (임상적 신뢰)

**Design Movement**: Medical UI / Healthcare App Design

**Core Principles**:
1. 깔끔한 화이트 스페이스로 의료 앱의 신뢰감 전달
2. 데이터 시각화 중심 - 차트, 그래프, 진행률 바
3. 명확한 정보 계층 구조
4. 접근성 우선 (큰 터치 영역, 높은 대비)

**Color Philosophy**:
- Primary: Teal (#0D9488) - 의료/건강의 신뢰감
- Secondary: Slate (#475569) - 안정감
- Accent: Amber (#F59E0B) - 보상/성취 강조
- Background: White (#FFFFFF) + Light Gray (#F8FAFC)

**Layout Paradigm**:
- 카드 기반 정보 그룹핑
- 하단 탭 네비게이션 (5개 탭)
- 스크롤 가능한 세로 리스트

**Signature Elements**:
1. 원형 진행률 표시기 (데이터 입력 완료율)
2. 보상 금액 강조 배지
3. 체크리스트 스타일 입력 현황

**Interaction Philosophy**:
- 탭하여 확장되는 카드
- 스와이프로 빠른 액션
- 햅틱 피드백으로 완료 확인

**Animation**:
- 부드러운 페이드 인/아웃
- 숫자 카운트업 (보상 금액)
- 체크마크 완료 애니메이션

**Typography System**:
- Heading: Pretendard Bold
- Body: Pretendard Regular
- Numbers: SF Pro (금액 표시)
</text>
<probability>0.08</probability>
</response>

<response>
<text>
### Idea 2: Gamified Wellness (게이미피케이션 웰니스)

**Design Movement**: Gamification / Duolingo-style

**Core Principles**:
1. 성취감과 재미를 통한 지속적 참여 유도
2. 스트릭(연속 기록), 레벨, 배지 시스템
3. 밝고 친근한 컬러로 부담 없는 건강 기록
4. 마이크로 인터랙션으로 즉각적 피드백

**Color Philosophy**:
- Primary: Violet (#7C3AED) - 에너지, 창의성
- Secondary: Emerald (#10B981) - 건강, 성장
- Accent: Yellow (#FBBF24) - 보상, 성취
- Background: Soft Purple (#F5F3FF) + White

**Layout Paradigm**:
- 중앙 집중형 메인 액션 버튼
- 캐릭터/마스코트 활용
- 카드 스택 형태의 일일 미션

**Signature Elements**:
1. 불꽃 아이콘 스트릭 카운터 (연속 기록 일수)
2. 레벨 프로그레스 바
3. 축하 모달 (목표 달성 시)

**Interaction Philosophy**:
- 큰 버튼으로 명확한 액션 유도
- 완료 시 confetti 효과
- 드래그 앤 드롭 인터랙션

**Animation**:
- 바운스 효과 (버튼 탭)
- 파티클 효과 (보상 획득)
- 캐릭터 리액션 애니메이션

**Typography System**:
- Heading: Nunito Bold (둥근 느낌)
- Body: Pretendard Regular
- Numbers: Nunito Bold
</text>
<probability>0.06</probability>
</response>

<response>
<text>
### Idea 3: Minimal Finance (미니멀 금융)

**Design Movement**: Fintech / Banking App Design

**Core Principles**:
1. 보상(수익)을 핵심 가치로 전면 배치
2. 금융 앱처럼 숫자와 거래 내역 중심
3. 다크 모드 기본으로 프리미엄 느낌
4. 최소한의 UI로 핵심 정보만 표시

**Color Philosophy**:
- Primary: Zinc (#18181B) - 다크 배경
- Secondary: White (#FFFFFF) - 텍스트
- Accent: Lime (#84CC16) - 수익/긍정
- Accent2: Rose (#F43F5E) - 알림/중요

**Layout Paradigm**:
- 대형 숫자 중심 히어로 섹션
- 거래 내역 스타일 리스트
- 플로팅 액션 버튼

**Signature Elements**:
1. 대형 잔액 표시 (은행 앱 스타일)
2. 수익 그래프 (일별/주별/월별)
3. 트랜잭션 리스트 (입력 = 입금)

**Interaction Philosophy**:
- 길게 눌러 상세 보기
- 스와이프로 빠른 입력
- 풀다운 새로고침

**Animation**:
- 숫자 롤링 효과
- 그래프 드로잉 애니메이션
- 슬라이드 업 모달

**Typography System**:
- Heading: SF Pro Display Bold
- Body: SF Pro Text Regular
- Numbers: SF Mono (금액)
</text>
<probability>0.05</probability>
</response>

---

## 선택: Idea 1 - Clinical Trust

**선택 이유**:
1. 건강 데이터 앱으로서 **신뢰감**이 가장 중요
2. 게이미피케이션은 과도하면 진지함이 떨어질 수 있음
3. 금융 앱 스타일은 건강 앱 정체성과 맞지 않음
4. 의료 연구 참여라는 목적에 부합하는 톤앤매너
5. 접근성과 사용성 우선

**적용할 핵심 요소**:
- Teal + White 기반 클린한 컬러
- 카드 기반 정보 그룹핑
- 원형 진행률 표시기
- 보상 금액 강조 배지
- 체크리스트 스타일 입력 현황
