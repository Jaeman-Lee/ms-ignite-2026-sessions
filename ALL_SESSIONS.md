# Microsoft Ignite 2026 · 전체 세션 요약

공식 방송·녹화 기반 29개와 공식 실습자료 기반 2개를 한 문서로 모았습니다. 2026년 11월 19일 PST까지 수집한 자료 기준입니다. [세션 목록](README.md) · [소개만 확보한 세션](PREVIEWS.md)

[BRK240](#brk240) · [BRK441](#brk441) · [BRK548](#brk548) · [BRKSP630](#brksp630) · [INV640](#inv640) · [INV643](#inv643) · [KEY01](#key01) · [LIVE50](#live50) · [LIVE51](#live51) · [LIVE52](#live52) · [LIVE53](#live53) · [OD1931](#od1931) · [ODSP2172](#odsp2172) · [ODSP2215](#odsp2215) · [ODSP2235](#odsp2235) · [ODSP2244](#odsp2244) · [THR1014](#thr1014) · [BRK247](#brk247) · [BRK272](#brk272) · [BRK533](#brk533) · [BRKSP610](#brksp610) · [KEY02](#key02) · [LIVE54](#live54) · [LIVE55](#live55) · [BRK442](#brk442) · [LAB723](#lab723) · [LABSP830](#labsp830) · [BRK473](#brk473) · [BRK525](#brk525) · [BRK368](#brk368) · [THR882](#thr882)

## BRK240

Foundry 에이전트의 추적·평가·개선

**자연스러운 답변도 업무 맥락을 놓칠 수 있으므로 실행 이력과 평가를 함께 본다.**

2026-11-17 · 공식 녹화 · 평가·보안·통제

### 핵심 내용

- Foundry에서 에이전트의 실행 단계와 도구 호출을 추적하고 개선할 행동·스킬을 검토하는 흐름을 소개했다.
- 39:30 Toyota 예시에서 운전자는 목적지의 충전소를 원했지만 AI는 현재 위치 근처를 답했다. 존재 여부보다 질문 맥락이 어긋난 사례다.
- 43:50 슬라이드는 직원 검증을 Customer Zero, 일반 고객 제공을 다음 단계로 구분했다.

### 확인 범위

Toyota의 외부 고객 배포나 실현 성과를 입증하는 장면은 아니다. Foundry 기능 전체가 같은 출시 단계라는 뜻도 아니다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856609563001Ep0b-1791588070636001Coui)
- [공식 녹화: 30:00·39:30·43:50](https://medius.microsoft.com/Embed/video-nc/350e7c06-2901-4dbc-9559-2dd70e8999c1)

## BRK441

Azure Maia 추론 인프라

**추론 인프라는 칩뿐 아니라 메모리·네트워크·랙 전체의 균형으로 설명한다.**

2026-11-17 · 공식 녹화 · GPU·추론·비용

### 핵심 내용

- 09:00–16:20에는 데이터 이동 비용과 칩·메모리·네트워크의 균형을 다뤘다.
- 18:00–25:55에는 가속기 모듈·보드와 연구소의 랙 시험 영상을 보여줬다.
- Maia 200은 내부 운영 서비스 사용, Maia 300은 2027년 계획으로 소개했다. 전력당 처리량 관련 수치는 공급사의 발표·전망이다.

### 확인 범위

고객 운영 벤치마크가 아니며 비교 GPU, 모델, 정밀도, 지연 목표와 청구 비용이 충분히 공개되지 않았다. 발표 수치만으로 다른 GPU 대비 절감률을 계산할 수 없다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856640352001EpXn-1791588117452001CP9h)
- [공식 녹화](https://medius.microsoft.com/Embed/video-nc/29479dec-c531-4dae-a112-74a383c37766)
- [Azure 공식 아키텍처 설명](https://azure.microsoft.com/en-us/blog/deep-dive-into-azure-maia-300-architecture/)

## BRK548

Replit 개발 에이전트의 운영 구조

**작업 위임 뒤에도 권한 범위, 실행 상태, 변경 승인과 배포 경계를 따로 관리한다.**

2026-11-17 · 공식 녹화·제품 발표 · 업무용 에이전트

### 핵심 내용

- 04:09–04:56에는 Fabric Functions 정보가 빠진 문서를 찾아 클라우드 에이전트에 수정을 요청했다. 결과 PR의 실제 병합·배포까지 확인한 시연은 아니다.
- 06:50–11:20에는 요청자보다 좁은 에이전트 권한, 재시작 후 작업을 이어가기 위한 상태 보관, 코드 실행 환경의 격리를 설명했다.
- 공식 제품 발표는 Fabric 연동을 GA, Azure 앱 게시를 Early Access, 개발·실행을 모두 고객 Azure에 두는 Full BYOC를 향후 계획으로 구분했다.

### 확인 범위

공급사의 내부 생산성 수치에는 비교 기간·분모·대조군이 제시되지 않았다. 다른 조직의 생산성 개선율로 일반화하지 않는다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856656693001E0cK-1791588221349001CeSB)
- [공식 녹화](https://medius.microsoft.com/Embed/video-nc/43ac3abc-86db-47e6-abf7-d7da3c9d7624)
- [Replit 공식 출시 안내](https://replit.com/blog/build-where-your-business-works-replit-at-microsoft-ignite)

## BRKSP630

Azure·NVIDIA 가속 컴퓨팅과 GPU SQL

**에이전트의 긴 문맥과 반복 호출, SQL 동시성 부하를 서로 다른 워크로드로 다뤘다.**

2026-11-17 · 공식 녹화·제품 문서 · GPU·추론·비용

### 핵심 내용

- 장기 실행 에이전트는 문맥·턴·도구 호출이 늘어나므로 KV 캐시 재사용이 중요하다고 설명했다.
- Fabric SQL 시연은 활성 사용자 250명·쿼리 1,000건에서 기준 구성 682.4초, GPU 가속 구성 11.4초를 표시했다. 이는 특정 시연의 완료 시간이다.
- Vera Rubin NVL72 Confidential Bare Metal은 Technology Preview, Fabric Data Warehouse 가속은 Limited Public Preview로 소개됐다.

### 확인 범위

GPU 기종·수량·단가, 캐시 초기 상태와 반복 측정 조건은 미확인이다. SQL 시연의 시간 비율을 추론 성능이나 비용 절감률로 바꾸지 않는다. 다른 슬라이드의 전력·비용 비교도 별개다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787854985876001tT18-1791588339892001ChGq)
- [Microsoft Events 공식 영상](https://www.youtube.com/watch?v=g2wSshatJ90)
- [행사 개별 녹화: 23:15–25:15 SQL 시연](https://medius.microsoft.com/Embed/video-nc/266c0933-b786-4fac-b5cb-38d6d6be2502)
- [Fabric 기능 문서](https://learn.microsoft.com/en-us/fabric/data-warehouse/query-acceleration)

## INV640

Copilot 업무 위임과 조직의 비용 통제

**업무 데이터 연결, 사람의 결정, 비용을 부담하는 조직을 하나의 흐름에서 보여줬다.**

2026-11-17 · 공식 방송·제품 발표 · 업무용 에이전트

### 핵심 내용

- Eli Lilly가 Cowork 사용 경험을 공유했고 후속 시연은 연구 기회를 정리하는 업무를 보여줬다.
- 재무 시연은 자금 부족 전망에서 대안을 비교하고 업무 시스템 갱신·메일·회의 초대를 준비하는 흐름이었다.
- Agent 365는 에이전트 신원·활동·정책과 비용 부담 그룹을 다뤘다. Autopilot은 Frontier 고객 배포 개시, Business Analytics는 Frontier Public 초기 제공으로 설명했다.

### 확인 범위

재무 시연의 조직·금액은 데모 데이터다. 사용 인원은 비용 절감률이 아니며, 향후 제품 계획을 GA로 해석하지 않는다.

공식 방송 11/17 16:23·16:37–16:56 PST. 방송 시계이며 YouTube 재생 시각이 아니다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856657745001EewR-1789751958676001dVT9)
- [Copilot 공식 발표](https://www.microsoft.com/en-us/copilot/blog/2026/11/17/copilot-at-microsoft-ignite-expanding-whats-possible-with-intelligence-built-for-work/)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## INV643

클라우드부터 로컬 PC까지의 AI 실행

**AI 실행 위치와 파일 접근권한, 모델 라우팅을 각각 설계하는 방향을 제시했다.**

2026-11-17 · 공식 방송·제품 발표 · GPU·추론·비용

### 핵심 내용

- 공용 클라우드 연결을 끊은 상태에서 로컬 SharePoint 문서를 연구 에이전트에 연결하는 시연이 있었다.
- 계약서 한 파일에만 접근하도록 에이전트 프로세스를 제한하는 장면을 보여줬다.
- GitHub Copilot Fusion의 Windows 로컬 모델 라우팅을 Preview로 발표했다.

### 확인 범위

로컬 실행 자체가 폐쇄망 적합성·보안·비용 절감을 보장하지 않는다. 단말별 성능과 모델 선택 규칙, 실제 절감액은 확인되지 않았다.

공식 방송 11/17 14:28·14:40·14:48 PST. 방송 시계 기준.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856658187001Etji-1789751959279001dn4k)
- [Windows 공식 발표](https://blogs.windows.com/windowsexperience/2026/11/17/microsoft-ignite-2026-building-windows-for-the-next-era-of-work/)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## KEY01

개막 키노트: AI에 업무를 위임하는 기업

**에이전트가 업무를 진행하되 최종 승인과 실행 통제는 사람과 기존 시스템에 남긴다.**

2026-11-17 · 공식 방송·발표 · 업무용 에이전트

### 핵심 내용

- BNY와 Microsoft의 에이전트가 미국 단기국채 거래 조건을 협상한 파일럿을 소개했다. 양측 트레이더가 최종 조건을 승인한 뒤 기존 시스템으로 집행했다.
- Unilever 정산 시연은 증빙이 부족한 항목을 찾아 추가 자료를 요청하는 초안을 만들었다. 자동 생성한 초안과 승인된 업무 결과를 구분했다.
- Alaska Airlines 정비 기록 예제에서는 기본 모델, 지시문 최적화, 다른 모델의 미세조정을 비교했다. 업무별 평가와 비용을 함께 보는 사례다.

### 확인 범위

단기국채 협상은 파일럿이며 자율적인 거래 집행 사례가 아니다. 정비 예제는 합성 데이터 시연이고 모델·학습 방법이 함께 달라 동일 조건의 일반 성능 비교가 아니다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856726055001EpP1-1789751960282001d6eI)
- [Microsoft Events 공식 추가 게시본 · 11월 19일 16:08 PST](https://www.youtube.com/watch?v=-JSecnudwvY)
- [Microsoft Events 공식 영상](https://www.youtube.com/watch?v=JaTSaJioHV8)
- [BNY 공식 파일럿 발표](https://www.bny.com/corporate/global/en/about-us/newsroom/press-release/bny-and-microsoft-complete-first-agentic-negotiation-of-a-us-treasury-trade.html)
- [Microsoft 공식 키노트 글](https://blogs.microsoft.com/blog/2026/11/17/ignite-2026-building-the-frontier-ecosystem/)

## LIVE50

Brad Smith의 AI 신뢰·통제 인터뷰

**AI 신뢰 원칙을 개발 기준, 교육, 관리 절차와 통제 책임으로 연결했다.**

2026-11-17 · 공식 방송 표본 · 평가·보안·통제

### 핵심 내용

- Brad Smith는 개인정보·보안·이용자 안전 원칙을 실제 개발 조직의 기준과 직원 교육에 반영해야 한다고 말했다.
- 에이전트가 사람의 통제 아래 있는지, 그 통제 책임자가 누구인지가 핵심 질문으로 제시됐다.
- 자율규제의 작동 조건에 관한 견해를 밝혔다. 이후 기술기자 패널로 방송이 전환됐다.

### 확인 범위

정책에 대한 인터뷰 발언이며 새 법적 의무나 고객 성과 발표가 아니다. 자막을 확보하지 못한 패널 구간의 내용은 요약하지 않았다.

공식 방송 11/17 12:33–12:36 PST 인터뷰 표본.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1789669856931001RyDg-1789751969782001dMsq)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## LIVE51

드문 실패 사례와 반복 평가

**평균 점수와 함께 과거의 드문 실패가 다시 발생하는지를 확인하는 사례다.**

2026-11-17 · 공식 방송 표본 · 평가·보안·통제

### 핵심 내용

- NVIDIA는 Azure 자율주행 개발에서 Cosmos Data Factory를 데이터 준비·드문 상황 탐색·평가에 활용하는 방식을 설명했다.
- Porsche 담당자는 새 버전을 배포할 때 과거에 성공하거나 실패한 사건을 다시 시험한다고 말했다.
- 별도 문서 평가 화면은 사람이 AI 점수와 사유를 수정하고 평가 기준 개선에 피드백을 남기는 모습을 보여줬다.

### 확인 범위

공식 편성 시간대와 방송 표본을 대조한 기록이다. LIVE51 시작 제목 자막은 미확보이며 고객의 학습 방식·운영 성능·구매 금액은 확인되지 않았다.

공식 방송 11/17 13:24 평가 화면, 13:27–13:32 인터뷰 표본.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1792114887215001c2Et-1792435863319001e4AW)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## LIVE52

Copilot Autopilot의 업무 수행과 관리자 제어

**업무 문맥 파악, 실행 전 승인, 관리자 사용량·지출 확인을 연결했다.**

2026-11-17 · 공식 방송 표본 · 업무용 에이전트

### 핵심 내용

- Work IQ로 Teams 대화의 우선순위를 파악하고 에이전트가 처리한 파일·대화를 확인했다.
- 구매 요청 요약 메일과 회의 후보 시간을 제시한 뒤, 사용자가 시간을 승인하면 예약 결과를 보여줬다.
- 관리자가 조직 사용량·활성 사용자·지출 정책과 테넌트 설정을 확인하는 화면을 소개했다.

### 확인 범위

제품 시연이며 실제 고객 성과나 모델 학습 사례는 아니다. 이 시연만으로 기능 전체의 GA를 확인하지 않았다.

공식 방송 11/17 15:17–15:22 PST.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1792115043441001qtQw-1792435912618001Tbbz)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## LIVE53

AI FinOps: 비용 추적과 예산 관리

**어떤 에이전트가 비용을 썼는지 찾고 담당 조직이 예산을 관리하는 흐름이다.**

2026-11-17 · 공식 방송·제품 발표 · GPU·추론·비용

### 핵심 내용

- Agent 365 Business Analytics에서 실제·예상 비용과 한도 도달 현황을 보고 지출 그룹별 담당자에게 예산 관리를 맡기는 방법을 설명했다.
- Accenture 담당자가 Copilot 도입을 단계적으로 확대했던 경험을 공유했다.
- Foundry 시연은 비용 증가를 일으킨 에이전트와 실행 추적을 찾아 비용·토큰을 살피고 범위별 예산 설정을 열었다.

### 확인 범위

화면 비용은 추정치·예시이며 실제 청구액과 다를 수 있다. Business Analytics는 Frontier Public, Foundry 비용 화면은 Preview로 표시됐다. 예산 초과의 강제 차단 실행까지 검증한 기록은 아니다.

공식 방송 11/17 17:19–17:29·17:30–17:36·17:49–17:56 PST.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1792115078702001qXwC-1792435947655001FpN5)
- [Microsoft FinOps 공식 발표](https://techcommunity.microsoft.com/blog/finopsblog/ai-for-finops-bringing-the-cost-answer-to-where-decisions-are-made/4571510)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## OD1931

Agent Rewind와 에이전트 변경 복구

**에이전트의 변경 이력을 확인하고 정상 시점으로 되돌리는 기능을 소개했다.**

2026-11-17 · 공식 녹화·제품 발표 · 평가·보안·통제

### 핵심 내용

- Agent Rewind는 활동 급증과 변경 이력을 보고 되돌릴 시점을 선택하는 기능으로 소개됐다.
- 발표 당시 Private Preview이며 초기 복구 범위는 SharePoint 사이트와 OneDrive 계정이다.
- Governance Agent는 정리·보관 작업의 영향을 설명하고 사람의 승인 후 실행하는 흐름을 보여줬다.

### 확인 범위

화면에 Teams·Exchange 활동이 보인다고 해당 서비스까지 초기 복구를 지원하는 것은 아니다. 다른 사내 API까지 일괄 복구한다는 근거도 아니다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1793980351446001iZb0-AAAAAAAAAAAAAAAAAAAA)
- [공식 녹화: 04:30 활동 타임라인](https://medius.microsoft.com/Embed/video-nc/82341d09-657d-42df-9821-6829cf439f40)
- [SharePoint 공식 발표](https://techcommunity.microsoft.com/blog/spblog/microsoft-365-copilot-and-ai-agent-readiness-and-resiliency-with-sharepoint-cont/4573034)

## ODSP2172

Instacart 광고 시스템의 실시간 데이터 저장소

**AI 서빙의 지연은 모델이 읽는 데이터 저장소의 갱신·조회 구조에도 영향을 받는다.**

2026-11-17 · 공식 파트너 녹화·공급사 사례 · 데이터·검색

### 핵심 내용

- Dragonfly가 Instacart의 광고 피처 저장소 이전 사례를 설명했다.
- 데이터를 갱신하면서 읽기 지연을 유지하고 큰 클러스터의 구성을 바꾸는 문제가 핵심이었다.
- 공급사 자료는 노드 348개에서 100개로 변경하고 읽기 지연이 개선됐다고 설명한다.

### 확인 범위

공급사 발표와 사례 문서다. 슬라이드의 하드웨어·클러스터 감소율 표현이 서로 달라 동일한 측정치로 합치지 않는다. 노드 사양·기간·구성 조건과 독립 검증은 미확인이다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787855000923001tdVj-AAAAAAAAAAAAAAAAAAAA)
- [공식 녹화: 03:07–04:12](https://medius.microsoft.com/embed/video-nc/0e89d91f-4b2f-4e9e-beeb-008a2fdf7bd2)
- [Dragonfly 기술 사례](https://www.dragonflydb.io/blog/how-instacart-achieved-50-better-performance-with-70-fewer-nodes)
- [노드 수 비교 출처](https://www.dragonflydb.io/events/growing-pains-at-ai-speed)

## ODSP2215

SharePoint 에이전트의 권한·소유자·활동 관리

**에이전트의 존재뿐 아니라 소유자, 지식 원천, 공유 범위와 실제 사용을 확인한다.**

2026-11-17 · 공식 파트너 녹화 · 평가·보안·통제

### 핵심 내용

- SharePoint 관리자 보고서에서 에이전트가 생성된 사이트와 데이터 수집 상태를 확인했다.
- Agent 365 지도에서 지침·지식 원천·세션과 사용자 활동을 조회했다.
- Syskit Point에서 조직 전체 공유, 소유자 부재, 민감도 레이블 자료에 연결된 에이전트를 추렸다. AI Agents 카드에는 Early Access가 표시됐다.

### 확인 범위

관리 화면의 숫자는 데모 테넌트 예시다. 보고서 내용은 수집 설정에 좌우되며 시연한 기능 전체의 신규 GA를 뜻하지 않는다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787855005459001tYDf-AAAAAAAAAAAAAAAAAAAA)
- [공식 녹화: 08:20–20:55](https://medius.microsoft.com/embed/video-nc/81e57346-6efb-4ab9-b9e6-29797b424672)
- [Agent 365 공식 안내](https://techcommunity.microsoft.com/blog/agent-365-blog/whats-new-in-microsoft-agent-365-ignite-2026/4571753)

## ODSP2235

vLLM·Ray Serve 기반 코딩 모델 서빙

**모델 추론과 요청 라우팅·자동 확장·운영 관측의 역할을 나눠 설명했다.**

2026-11-17 · 공식 파트너 녹화 · GPU·추론·비용

### 핵심 내용

- vLLM은 추론, Ray Serve는 요청 라우팅과 자동 확장을 담당하는 구조를 소개했다.
- Azure 구독의 GPU 노드 풀에 모델을 배포하고 코딩 에이전트를 엔드포인트에 연결하는 과정을 시연했다.
- 요청 수·복제본 수·첫 토큰 지연·토큰 간 지연·KV 캐시를 보며 운영하는 화면을 보여줬다.

### 확인 범위

Ray Serve의 요청 라우팅은 여러 모델 중 하나를 고르는 Model Router와 구별한다. MIG 등 GPU 분할 기술의 우열, H200 실측, 배칭 실험이나 비용 절감률은 제시되지 않았다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787855007581001tVQQ-AAAAAAAAAAAAAAAAAAAA)
- [공식 녹화: 01:03–02:00·03:03–05:28·10:35](https://medius.microsoft.com/embed/video-nc/402b9fa2-5ae7-4a44-b953-f9c086399f19)
- [Anyscale on Azure GA 발표](https://techcommunity.microsoft.com/blog/appsonazureblog/anyscale-on-azure-is-now-generally-available/4562547)

## ODSP2244

VAST의 Azure 데이터 저장·원격 캐시 구조

**데이터 복사본이 늘어날 때 저장 비용과 권한·변경 관리가 함께 복잡해지는 문제를 다뤘다.**

2026-11-17 · 공식 파트너 녹화 · 데이터·검색

### 핵심 내용

- 분석·학습·백업을 위한 데이터 복사와 각 복사본의 접근권한·감사 관리 비용을 설명했다.
- Azure VM에서 연산·저장 기능을 나누고 영구 디스크에 메타데이터, Blob에 변경분을 두는 설계를 소개했다.
- 원격 지점은 첫 읽기 때 데이터를 캐시하고 필요한 데이터를 미리 준비할 수도 있는 흐름을 설명했다.

### 확인 범위

공급사의 아키텍처 설명이다. 고객 운영 성과, 삭제·권한 철회의 실제 전파 시간, 기능별 GA·Preview는 이 영상에서 확인되지 않았다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1788986932031001usBa-AAAAAAAAAAAAAAAAAAAA)
- [공식 녹화: 02:00–05:06·08:18–09:35·11:35–14:10](https://medius.microsoft.com/embed/video-nc/4e4fae49-77ef-48b1-9483-b1a975babdf3)

## THR1014

Foundry IQ의 검색·데이터 권한 연결

**에이전트에 지식을 연결할 때 검색 품질과 원문 접근권한을 함께 전달한다.**

2026-11-17 · 공식 녹화·기술 문서 · 데이터·검색

### 핵심 내용

- 업무에 맞춰 데이터 원천과 검색 방식을 선택하는 계층을 설명했다.
- 기본 검색을 기준으로 시작하고 추가 검색 단계가 답변 품질과 운영비에 주는 변화를 비교하자고 제안했다.
- Entra 사용자·그룹 정보와 지원되는 원천의 권한을 질의에 적용하고 검색 API·MCP로 연결하는 경로를 소개했다.

### 확인 범위

설명과 질의응답 중심이며 고객 성과 벤치마크가 아니다. 지원 데이터 원천·리전·API 버전에 따라 GA와 Preview 범위가 다르다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856599957001EPtN-1791588257351001CeAf)
- [공식 녹화: 08:00–09:59·14:30–17:59](https://medius.microsoft.com/Embed/video-nc/6b7b60d8-8e71-4259-8b9c-03821272c760)
- [Foundry IQ 공식 문서](https://learn.microsoft.com/en-us/azure/foundry/agents/concepts/what-is-foundry-iq)

## BRK247

토큰 경제성: 쓸 만한 답변 한 건의 비용

**토큰 단가와 함께 품질·재시도·캐시 재사용·피크 용량을 봐야 전체 업무 비용을 설명할 수 있다.**

2026-11-18 · 공식 녹화·제품 발표 · GPU·추론·비용

### 핵심 내용

- Foundry 시연은 실행 추적에서 비용 증가 원인을 찾고 동일 평가셋으로 모델·라우터 구성을 비교했다. 예산 제어는 대상·기간·한도·감사 또는 차단 동작을 설정했다.
- 캐시 예제는 공통 지시문을 앞에 두고 날짜·시각을 뒤로 옮겨 프리픽스를 재사용했다. Wolters Kluwer도 평가를 반복하며 공통 맥락을 정리한 경험을 공유했다.
- 실시간 요청과 지연 허용 작업을 구분하고, 예약 처리량·피크 초과 경로·유휴 시간의 평가 작업을 조합했다. Enhans는 업무 판정 기준과 모델 역할 분리를 설명했다.

### 확인 범위

가상 Woodgrove 시연 수치와 고객·공급사의 자체 보고는 별개다. 이를 일반 절감률로 합치지 않는다. 비용 보기·Agent Optimizer·비용 제어·Flex 등은 발표 당시 Preview로 안내됐다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856610647001ED9l-1791588131979001CbhB)
- [Microsoft Events 공식 영상](https://www.youtube.com/watch?v=-vWly99DJNY)
- [공식 개별 녹화](https://medius.microsoft.com/Embed/video-nc/67297ad2-a05f-44b5-96dd-3c742107e1e0)
- [Foundry FinOps 공식 발표](https://techcommunity.microsoft.com/blog/azure-ai-foundry-blog/finops-in-microsoft-foundry-see-your-token-spend-hit-your-quality-bar-for-less-a/4570010)

## BRK272

브라데스코의 AI 기반 시스템 현대화

**운영 서비스의 의존관계를 먼저 파악하고, 함께 이관할 서비스의 명세와 구현을 에이전트로 지원했다.**

2026-11-18 · 공식 녹화·시연 · 도입·조직

### 핵심 내용

- 펠리피 페르난지스 두스 헤이스(Felipe Fernandes dos Reis)는 배포 설정, 관측 데이터, 서비스 목록과 코드에서 호출·공유 데이터·담당팀을 찾고 함께 이관할 서비스를 묶는 과정을 설명했다. 브라데스코(Banco Bradesco S.A.)는 브라질에서 개인과 기업에 금융 서비스를 제공하는 은행이다.
- 브루누 보르지스(Bruno Borges)는 GitHub Copilot으로 재무상담 예약 예제의 의존성을 평가하고 Java 8에서 21로 수정한 브랜치를 실행했다. 마이크로소프트(Microsoft Corporation)는 미국의 업무 소프트웨어·클라우드 회사이며 이 시연을 맡았다.
- 발표는 한 운영 서비스를 은행 표준에 맞추는 명세와 구현에 수동 추정 960분, 에이전트 사용 시 약 33분 또는 44분이 걸렸다고 비교했다. 에이전트의 두 결과에는 명세 25분이 포함된다.

### 확인 범위

비교는 발표자가 제시한 운영 서비스 한 건의 사례다. 수동 기준은 추정치이고, 검수·승인·배포까지 걸린 시간과 반복 표본 수는 공개 설명에서 확인할 수 없었다. 상담 예약 시연에는 실제 데이터베이스를 연결하지 않았다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856614396001ENAG-1791588288203001CJ3J)
- [Microsoft Events 공식 영상](https://www.youtube.com/watch?v=Ztn208_5jpI)
- [행사 개별 녹화: 의존관계 11:30–17:50·시연 19:20–26:30·시간 비교 32:25–33:18](https://medius.microsoft.com/Embed/video-nc/bc0ce035-800d-4aa1-be94-5441b68c8714)
- [브라데스코 공시](https://www.sec.gov/Archives/edgar/data/1160330/000129281426004996/bbdifrs3q26_6k.htm)

## BRK533

AI 투자 성과와 조직의 운영 방식

**도입 건수보다 업무 성과를 정의하고 예산·현업 책임·교육·검증을 연결하자고 제안했다.**

2026-11-18 · 공식 녹화·조사 발표 · 도입·조직

### 핵심 내용

- IDC·Microsoft 연구는 24개국·28개 산업의 응답자 5,204명과 임원 정성 의견 13명을 다뤘다. 성숙도 상위 10%와 하위 30% 집단을 비교했다.
- 발표자는 예산 신청 전에 목표 성과와 지표를 정하고 부서 간 데이터 정의를 맞추자고 설명했다.
- 전사 교육과 에이전트별 책임·협의·보고 대상을 정하고, 모델이나 처리 지역이 달라져도 중요한 판정이 일치하는지 점검하는 운영을 제안했다.

### 확인 범위

집단별 자기보고와 연관성 분석이다. 응답자 수는 기업 수가 아니며 특정 예산·교육 구조가 성과를 일으켰다는 인과 효과를 입증하지 않는다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856654440001Edwg-1791588197643001CkJf)
- [Microsoft Events 공식 영상](https://www.youtube.com/watch?v=VTENQDpJY9A)
- [공식 개별 녹화](https://medius.microsoft.com/Embed/video-nc/461883b6-12e0-4b00-8f46-2a731feaeeb3)
- [공동 연구 공식 소개](https://blogs.microsoft.com/blog/2026/11/12/scaling-ai-value-without-losing-control-lessons-from-frontier-firms/)

## BRKSP610

SEI의 통제 가능한 금융 AI 에이전트 운영

**기존 업무 절차에서 후보를 고르고 위임 권한·검수·업무당 비용을 함께 관리한다.**

2026-11-18 · 공식 녹화 · 평가·보안·통제

### 핵심 내용

- SEI·IBM은 SOP에서 활동·담당·다음 단계를 추출하고 현업이 목표 흐름과 사업 가치를 검토하는 방식을 설명했다.
- 운용보수 계산 사례는 여러 입력과 스프레드시트를 공통 데이터 구조·검증 규칙에 맞추는 과정이었다.
- 거래량과 인프라 비용을 단위비용으로 연결하고, 누가 누구의 위임으로 실행하는지와 중요한 판단의 사람 개입을 분리했다. Project Imagine은 평가·비용·신원·운영·환경 승격을 연결했다.

### 확인 범위

프로젝트 설명과 구성 슬라이드가 근거다. 제시한 시간·단위비용의 표본·품질·검수 범위가 충분히 공개되지 않아 독립 검증된 성과나 일반 개선율로 취급하지 않는다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787854985450001t4D0-1791588247060001CMvR)
- [Microsoft Events 공식 YouTube](https://www.youtube.com/watch?v=-4U2nwth3ag)
- [공식 개별 녹화: 05:32–18:32·22:48–33:50](https://medius.microsoft.com/Embed/video-nc/985de043-4269-4ef0-ac38-57119d369789)

## KEY02

파트너 키노트: 직원 교육과 데이터 연결

**직원이 AI를 배우는 일과 기업 데이터를 연결하는 일을 구분해 소개했다.**

2026-11-18 · 공식 녹화·공급사 사례 · 도입·조직

### 핵심 내용

- Culligan과 Insight는 직원용 Flight Academy 교육과정을 함께 수정·시험한 협업을 설명했다.
- Quadra 사례는 인도 제약 고객의 기업 앱·실험실·설비 센서 등 여러 시스템을 Fabric으로 연결한 내용이었다.
- Partner Center for Sales는 다음 분기 GA 예정으로 발표했다. 고객 사례와 향후 제품 출시 계획은 서로 다른 상태다.

### 확인 범위

직원 교육을 모델 가중치 학습으로 해석하지 않는다. 제약 사례는 공급사 보고이며 고객 실명·표본·비교 기간·독립 검증은 미공개다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856726366001EV17-1789751960677001d6j0)
- [공식 다시보기](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-InstaVOD-Partner.json)
- [Microsoft Events 공식 YouTube](https://www.youtube.com/watch?v=Oe8nJV3yXtk)
- [Quadra 공급사 사례](https://marketplace.microsoft.com/en-us/product/quadra_systems.quadra_manufacturing_accelerator_ms_fabric)

## LIVE54

AI 실험을 운영으로 옮기는 관리와 개발 흐름

**에이전트 소유자·감사 기록을 관리하고 코드 변경 결과를 확인하는 사례를 다뤘다.**

2026-11-18 · 공식 방송·제품 발표 · 평가·보안·통제

### 핵심 내용

- Brown University Health 담당자는 책임 조직이 유망한 현장 프로젝트를 지원하고 Purview·Agent 365로 소유자와 감사 기록을 보는 방식을 설명했다.
- 예약 절차 자동화는 진행 중인 프로젝트로 소개됐다.
- GitHub 공급사 시연은 Copilot Fusion으로 코드 변경을 수행하고 Azure DevOps 저장소 연동과 브라우저 결과 확인을 설명했다. 관련 공식 발표는 연동·브라우저 사용을 Public Preview로 안내했다.

### 확인 범위

의료 성과나 모델 학습 성과를 검증한 기록은 아니다. 루빅스 큐브 코드 시연과 별도 Terminal-Bench 결과를 같은 실험으로 보지 않는다.

공식 방송 11/18 09:35–09:44 고객 인터뷰, 09:51–10:00 코드 시연 PST.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1792115124814001u9y2-1792435994054001eau4)
- [GitHub Copilot 앱 공식 발표](https://github.blog/changelog/2026-11-17-github-copilot-app-microsoft-ignite-releases/)
- [Fusion 공식 발표](https://github.blog/changelog/2026-11-17-github-copilot-fusion-updates-more-availability-benchmarks-and-models/)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## LIVE55

클라우드 AI의 시뮬레이션·격리·업무 비용

**AI 실행 과정의 계산 자원·격리·병목·사람의 승인을 함께 다뤘다.**

2026-11-18 · 공식 방송·제품 발표 · GPU·추론·비용

### 핵심 내용

- Wayve 사례 영상은 GAIA로 위험한 주행 장면을 생성하고 Azure A100을 학습·시뮬레이션에 활용하는 방식을 설명했다.
- Microsoft 인터뷰는 에이전트 코드 격리, 데이터베이스 병목, 전체 업무 비용 관측과 작업에 맞는 모델 선택을 다뤘다.
- Evo 시연은 문서 작성·회의 조율을 요청받아 후보 시간을 제시하고 최종 선택을 사람에게 남겼다. Frontier 공개 프리뷰의 단계적 배포로 소개됐다.

### 확인 범위

주행 모델 사례의 GPU 수량·학습 시간·비교 비용은 미확인이다. 고객 사례, 제품 시연과 향후 개발 계획을 구분한다.

공식 방송 11/18 10:12–10:15·10:33–10:41·10:52·11:07–11:10 PST.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1792115161977001lkVG-1792436025385001wCLr)
- [Wayve 공식 기술·협력 설명](https://wayve.ai/press/stellantis-wayve-scale-ai-driver/)
- [Copilot 공식 발표](https://www.microsoft.com/en-us/copilot/blog/2026/11/17/copilot-at-microsoft-ignite-expanding-whats-possible-with-intelligence-built-for-work/)
- [행사 공식 공용 방송](https://mediastream.microsoft.com/events/players/live/mvp/player.html?path=/events/2026/2611/O2V6/player/json/Config-O2V6-Live.json)

## BRK442

Azure Local과 Foundry Local로 구축하는 주권 AI

**로컬 추론과 검색을 조합하고, 같은 모델에도 업무 역할별로 다른 데이터 출처를 제공한다.**

2026-11-19 · 공식 녹화·제품 발표 · 평가·보안·통제

### 핵심 내용

- 마이크로소프트(Microsoft Corporation)는 미국의 업무 소프트웨어·클라우드 회사다. Azure Local PM Kushmeen Kambow와 Foundry Local PM Anders Zwartjes가 연결·단절 환경에서 로컬 추론과 검색을 구성하는 방법을 소개했다.
- 가상 Woodgrove Bank의 문답 다섯 건을 세 모델에 주고 별도 평가 모델로 유사성·완전성·관련성을 비교했다. 같은 모델을 쓰는 위험 조사 담당자용과 창구 담당자용 에이전트에는 서로 다른 출처를 연결했다. 조사 화면에서는 참조한 자료를 답변 옆에서 확인할 수 있었다.
- 행사 기준 모델 카탈로그·추론·에이전트형 검색과 GitHub Enterprise Local은 정식 제공으로 소개했다. Agent Service와 Guardrails는 Preview였고, Azure Local의 NVIDIA HGX B300 기반 대규모 추론 지원은 2027년 상반기 Preview를 목표로 발표했다.

### 확인 범위

가상의 은행 시연과 제품 발표다. 실제 은행의 도입·권한 검증이나 동일 품질에서의 지연·처리량·비용은 공개 설명에서 확인되지 않았다. 영상은 Microsoft 행사 다시보기다.

### 공식 근거

- [공식 회차](https://ignite.microsoft.com/en-US/sessions/1787856640517001EIKl-1791588245037001C6mG)
- [행사 다시보기: 모델 평가 08:10–11:35 · 역할별 출처 24:00–28:53](https://medius.microsoft.com/Embed/video-nc/24585be0-7bee-4f5c-93ac-a113bd7a3c14)
- [Microsoft 제품 발표](https://techcommunity.microsoft.com/blog/azurearcblog/whats-new-with-sovereign-private-cloud-at-microsoft-ignite-2026/4573886)
- [Microsoft Learn 요구 사항](https://learn.microsoft.com/en-us/azure/azure-sovereign-clouds/private/foundry-local/concept-requirements)

## LAB723

AKS 추론 워크로드의 관측·확장·Ray 실습

**배포 뒤 지연·처리량·자원 제한을 관측하고 파드·노드 확장과 분산 작업을 비교하는 실습이다.**

2026-11-19 · 공식 실습서 기반 · GPU·추론·비용

### 핵심 내용

- 공식 실습서는 환경 확인 → 배포 → 추론 최적화 → 관측·확장 → Ray 작업 순으로 구성된다.
- CPU 프로파일·스레드·CPU 제한과 p50·p95·처리량·throttling을 비교하고, HPA 파드 확장과 NAP 노드 준비를 구분한다.
- Ray 단일·복수 워커를 비교해 분산 오버헤드를 관찰한다. 예제 모델은 ONNX Runtime의 DistilBERT 감성분류이며 T4 GPU 예시를 사용한다.

### 확인 범위

공식 실습서 750f73edddd4 버전의 절차 요약이며 직접 실행 결과는 없다. 생성형 LLM의 KV 캐시·생성 토큰 성능이나 고정 장비의 현금비용 절감으로 전용하지 않는다. 녹화 계획이 없는 실습으로 안내됐다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856876559001h7CZ-1791906698620001aNJy)
- [공식 실습서 고정 버전](https://github.com/microsoft/ignite26-LAB723/blob/750f73edddd470a0919eabd91c8b6de32f1f79e3/instructions/README.md)
- [공식 환경 설명 고정 버전](https://github.com/microsoft/ignite26-LAB723/blob/750f73edddd470a0919eabd91c8b6de32f1f79e3/docs/lab-environment.md)

## LABSP830

vLLM Semantic Router로 추론 경로 선택하기

**하나의 앱 엔드포인트에서 요청을 분류하고 정책 우선순위로 답변 모델을 선택하는 실습이다.**

2026-11-19 · 공식 실습자료 기반 · GPU·추론·비용

### 핵심 내용

- 앱은 vLLM Semantic Router의 `vllm-sr/auto`를 호출한다. 이름표 같은 정확한 신호와 요청의 의미를 반영한 신호를 YAML로 조합해 모델 경로를 고른다.
- D3 Lite로 추론 필요성을 판단하고, 선택 실습에서는 Vela 3 Fast로 이름·이메일·전화번호의 텍스트 구간을 찾는다. 답변 생성은 라우터가 선택한 별도 모델이 맡는다.
- 발표자 해설은 비교와 추천을 함께 요청하는 경우에만 심층 경로를 선택하도록 D3 Lite 질문을 좁히고, `[INCIDENT]`는 정확한 태그로 처리한다. 예시 우선순위는 `[PRIVATE]` 300, `[INCIDENT]` 250, 의미 판단 200, 기본 경로 100이다. 여섯 가지 입력을 두고 선택된 모델을 확인한다.

### 확인 범위

발표자 공개 노트북과 슬라이드로 실습 절차를 확인했다. 예제에서 D3 Lite는 로컬 CPU에서 실행되며 두 답변 모델은 Azure Foundry에 연결된다. 사내망에 적용하려면 민감 요청이 선택하는 경로의 실제 서빙 주소와 네트워크 정책을 확인해야 한다. 노트북의 미리보기 도우미는 대시보드 기록을 위해 실제 짧은 생성 요청도 따로 보낸다. 카탈로그에는 녹화 계획이 없다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1790705089430001luN0-1791911961057001WtJj)
- [발표자 GitHub 실습 브랜치 (Foundry CPU · D3 Lite)](https://github.com/Mahdi-CV/amd-gpu-workshops/tree/workshop/vllm-sr-route-one-agent-v3-foundry-cpu-d3)
- [발표자 노트북 고정 버전](https://github.com/Mahdi-CV/amd-gpu-workshops/blob/51dc74ee2bee9fe35e1335716b03b564560d7e74/notebooks/vllm-sr-route-one-agent-v3/route-one-agent-across-two-models-v3.ipynb)
- [발표 슬라이드 고정 버전](https://github.com/Mahdi-CV/amd-gpu-workshops/blob/51dc74ee2bee9fe35e1335716b03b564560d7e74/notebooks/vllm-sr-route-one-agent-v3/.deploy/vllm-sr-workshop-intro.pptx)
- [발표자 과제 해설 고정 버전](https://github.com/Mahdi-CV/amd-gpu-workshops/blob/51dc74ee2bee9fe35e1335716b03b564560d7e74/notebooks/vllm-sr-route-one-agent-v3/.deploy/SOLUTION-KEY.md)
- [실습 라우터 설정 고정 버전](https://github.com/Mahdi-CV/amd-gpu-workshops/blob/51dc74ee2bee9fe35e1335716b03b564560d7e74/notebooks/vllm-sr-route-one-agent-v3/.deploy/foundry-cpu/router-config.yaml)

## BRK473

금융 에이전트의 실험 권한과 운영 승인

**현업 실험에는 제한된 권한을 주고, 전사 배포에는 별도 심사와 운영 책임을 둔다.**

2026-11-19 · 공식 행사 녹화 · 평가·보안·통제

### 핵심 내용

- 스테이트 팜(State Farm) | 미국 | 자동차·주택 등 개인과 기업에 보험 서비스를 제공한다. | 엔지니어링 매니저 아주어 도턴(Azsure Dorton)이 관리형 환경을 도입하고 에이전트를 운영에 배포한 자사 사례를 소개했다. 09:50 화면에 2026년 11월 자체 집계 기준 운영 에이전트 52개가 표시됐다.
- 16:25에는 연결 범위를 제한한 기본 환경에서 현업이 가치를 검증하고, AI 승인 단계를 거쳐 운영으로 승격하는 절차를 설명했다. 22:00 전후 마무리에서 보안·리스크 담당자의 초기 참여와 반복적인 저위험 업무부터 시작할 것을 제안했다.
- 마이크로소프트(Microsoft Corporation) | 미국 | 업무용 소프트웨어와 클라우드를 제공한다. | 조하르 라즈(Zohar Raz)와 오스틴 라우게슨(Austin Laugesen)이 거버넌스·제품 운영을 설명했다. 33:30 관리형 호스트 화면에서는 사용자 신원에 연결된 데이터 동의를, 40:10 화면에서는 사용자당 구독과 Copilot Credit 사용량 과금을 비교했다.

### 확인 범위

공식 행사 다시보기의 화면과 영어 자막 표본을 확인했다. 52개는 해당 보험사가 발표한 운영 배포 수다. 업무 처리 품질·위험 감소·비용 절감 성과와 기능별 출시 단계는 별도 검증이 필요하다. Microsoft Events 채널의 공식 YouTube 본편은 11월 19일 16:49 PST 공개됐다. 화면·자막 근거와 아래 시각은 행사 다시보기 기준이다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856645220001EUhq-1791588268917001CGsN)
- [공식 행사 다시보기](https://medius.microsoft.com/Embed/video-nc/5fd1a5a1-f386-4f89-a525-5b5c39952c4f)
- [공식 YouTube 본편](https://www.youtube.com/watch?v=VO0pjIubjXE)
- [State Farm 기업 소개](https://www.statefarm.com/about-us/company-overview)

## BRK368

PostgreSQL 운영 환경의 분산과 이관 검증

**샤드를 늘릴 때 연결별 메타데이터 메모리와 실제 복원 시간을 함께 검증한다.**

2026-11-19 · 공식 행사 녹화 · 데이터·DB 운영

### 핵심 내용

- 볼터스 클루버(Wolters Kluwer) | 네덜란드 | 법률·세무 등 전문가에게 정보와 소프트웨어를 제공한다. | 스벤 후베르트(Sven Hubert)가 자사의 PostgreSQL 이관을 설명했다. 14:40–15:20에 스키마 및 파티션 설계, 시험 복원과 반복 이관 검증을 다뤘다.
- 19:40–20:18에는 파티션과 샤드 증가로 연결별 메타데이터 캐시가 커져 메모리가 부족해진 운영 사례를 설명했다. 25:30 결과 화면에 피크 메모리 80% 미만, 평균 SQL 문장 실행 시간 20ms 미만이 표시됐다.
- 마이크로소프트(Microsoft Corporation) | 미국 | 업무 소프트웨어와 클라우드를 제공한다. | 가이 바워먼(Guy Bowerman)과 다니알 부카리(Danyal Bukhari)가 운영 기능을 설명했다. 38:20–39:05에 Database Agent Preview의 진단→검토용 PR 흐름과 향후 Fabric Database Hub 연계를 소개했다.

### 확인 범위

공식 행사 다시보기 화면과 영어 자막 표본을 대조했다. 메모리와 실행 시간은 한 고객의 발표 수치이며 동시 부하와 비교 조건은 충분히 공개되지 않았다. PR 병합이나 운영 DB 변경 실행은 확인되지 않았다. 공식 YouTube 본편은 확인 대기다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856629108001E3Up-1791588323549001CZ65)
- [공식 행사 다시보기](https://medius.microsoft.com/Embed/video-nc/f15a59e7-e2c1-4c03-b39f-6244732c2cff)
- [볼터스 클루버 기업 정보](https://www.wolterskluwer.com/en/contact-us)

## THR882

DB 장애 근거 수집과 승인 기반 복구

**장애 근거와 대응 초안은 에이전트가 모으고 운영자가 변경을 검토한다.**

2026-11-19 · 공식 행사 녹화 · 데이터·DB 운영

### 핵심 내용

- 마이크로소프트(Microsoft Corporation) | 미국 | 업무 소프트웨어와 클라우드를 제공한다. | 브라이언 홀트(Brian Holt)가 Database Agent의 진단·권고 흐름을 소개했다. 05:25 화면은 지표, 로그, 쿼리 실행계획, 배포를 모아 근거와 다음 조치를 구분했다.
- 13:20의 모의 서버에서 연결 고갈 사례를 살폈다. 화면은 운영자가 직접 세션을 확인해야 하는 조건과 롤백 안내를 표시했다.
- 20:30과 23:30의 화면에서 이슈 등록과 자동 복구는 향후 제공 기능으로 표시됐다. 자동 복구는 시나리오별 선택, 저위험 조치 한정, 자동 재시작 제외, 결과 확인과 기록을 조건으로 설명했다.

### 확인 범위

공식 행사 영상의 화면과 슬라이드를 확인했다. 확인한 영어 자막 구간은 비어 있었다. 모의 시연에서 실 DB 수정이나 운영 장애 복구 결과는 검증되지 않았다. 공식 YouTube 본편은 확인 대기다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856579574001Ettf-1791588274282001CUNE)
- [공식 행사 다시보기](https://medius.microsoft.com/Embed/video-nc/4f0b46b4-8e3b-4539-adc3-8ae01a6d2835)

## BRK525

공신력 있는 데이터로 만드는 금융 리스크 조기경보

**에이전트가 출처가 있는 위험 신호를 모으고, 검토자가 판단과 승인에 책임을 진다.**

### 핵심 내용

- 마이크로소프트(Microsoft Corporation) | 미국 | 업무용 소프트웨어와 클라우드를 제공한다. | 헤만트 순다라라지(Hemanth Sundararaj)와 아미트 판찰(Amit Panchal)이 금융 에이전트 참조 구조를 소개했다. 17:10 화면에서 데이터, 지식, 업무 앱과 공통 통제 계층을 함께 제시했다.
- 무디스 애널리틱스(Moody’s Analytics, Inc.; Moody’s Corporation 그룹) | 미국 | 기업 신용과 위험을 평가할 때 쓰는 데이터와 분석을 제공한다. | 디미트리오스 파파나스타시우(Dimitrios Papanastasiou)가 공동 발표자로 조기경보를 설명했다. 21:35 화면의 공동 시연은 Copilot과 Excel에서 여러 국가의 거시 지표와 국가신용 위험을 정리하고 출처를 표시했다.
- 메르세데스-벤츠 그룹(Mercedes-Benz Group AG) | 독일 | 승용차와 밴을 생산하는 자동차 그룹이다. | 29:00 조기경보 슬라이드에서 신용 분석 대상으로 등장했다. 데이터 수집과 초안 작성에 이어 민감한 신용 판단에는 사람이 관여해야 한다는 견해가 40:30 이후 질의응답에 나왔다.

### 확인 범위

공식 행사 다시보기 화면과 영어 자막 표본을 확인했다. 출처 연결과 조기경보는 공동 발표와 시연으로 확인됐다. 분석 대상 기업의 도입, 자체 모델 학습, 운영 성과, 기능별 출시 상태는 별도 확인이 필요하다. 이 회차의 공식 YouTube 본편은 미확인이다.

### 공식 근거

- [공식 세션](https://ignite.microsoft.com/en-US/sessions/1787856653112001EXqY-1791588307345001C7zd)
- [공식 행사 다시보기](https://medius.microsoft.com/Embed/video-nc/22c4c2a1-4acf-4091-b3c8-dc4eaacd6a5f)
- [무디스 발표자 소개](https://ignite.microsoft.com/en-US/speakers/177730559163ignite27-1791219976569001gWDi)
- [마이크로소프트 기업 정보](https://www.microsoft.com/en-us/investor/contact-information)
- [무디스 기업 정보](https://www.moodys.com/web/en/us/help-support/offices.html)
- [메르세데스-벤츠 그룹 기업 정보](https://group.mercedes-benz.com/contact/)

[개별 요약](sessions/2026-11-19/BRK525.md)
