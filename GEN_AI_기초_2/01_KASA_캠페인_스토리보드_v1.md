# GenAI 기초 2: 멀티모달 콘텐츠 제작

> **진행 상태: 기획 v1 / 아직 생성형 AI로 제작한 시각·영상·오디오 결과 없음.** 
> 
> 캠페인: **우주에 닿았다. 이제, 우주를 연다.**
> 
> 우주항공청(KASA)을 주제로 한 **학습용 비공식 캠페인**으로, 실제 KASA의 공식 제작·승인을 받은 광고가 아님.

## 1. 과제 요구사항

- 제출물: **스토리보드 PDF 1개**, **광고 MP4 1개(10초 이내)**.
- AI 이미지 생성 도구 ≥1종, 비디오 생성/변환 도구 ≥1종, 오디오 생성 도구 ≥1종 **실제 사용**.
- 모든 시각 및 청각 소스는 생성형 AI로 제작. 실제 누리호 발사 촬영/뉴스 영상과 스톡 영상은 최종 광고 소스로 미사용.
- 모든 씬에 번호·길이·목표 메시지·화면 구성·카피/내레이션·도구와 목적·입력 프롬프트 원문·출력 결과 요약·생성 결과 파일명 포함.
- **최소 1개 씬에서 실제 프롬프트 수정 전/후**와 결과 변화·수정 이유 기록.
- 광고에 서사 구조 또는 뚜렷한 가치 메시지 포함. **마지막 3~5초**는 브랜드명/로고/슬로건/CTA 인지 장치 포함.
- 이미지/비디오/오디오 도구별 대체 후보 확보; 크레딧 부족 시 씬 수 축소, 정지 이미지+짧은 모션, 공통 스타일 레퍼런스 활용.
- 편집기는 컷 편집·자막·기초 색보정·레벨 조정 등 통합 용도만 사용.
- 참고: 공지에는 '초 이상 10초 이내'로 최소 길이가 누락돼 있고 예시에는 42초가 있지만, **최종 결과물의 명시된 최대 길이는 10초**.

## 2. 브랜드 아이덴티티 · 캠페인 정의

| 항목 | 내용 |
|---|---|
| 브랜드 | 대한민국 **우주항공청(KASA)**를 주제로 한 비공식 학습 캠페인 |
| 배경 | 누리호 발사 성과 이후 대한민국 우주산업 및 탐사 비전을 상상 |
| 타깃 | 일반 국민, 청년 과학기술 인재, 우주산업 관계자 |
| 목적 | 국가 우주개발 성과와 다음 목표에 대한 인지도·기대감 형성 |
| 톤앤매너 | 장엄함, 미래지향적, 정밀함, 신뢰감, 시네마틱 |
| 색상 | Deep Navy `#071525`, Space Black `#05070C`, Earth Blue `#3988D6`, Warm Gold `#E9B96A` |
| 차별점(USP) | 발사체·위성 활용·민간 산업·우주탐사를 하나의 국가 우주개발 비전으로 연결 |
| **핵심 메시지** | **누리호의 성과를 발판으로 대한민국은 독자적인 우주산업과 새로운 우주탐사의 시대를 열어간다.** |

### 최종 영상 콘셉트

**「우주에 닿았다. 이제, 우주를 연다.」**

- 기획 구조: **성취 → 확장 → 미래 선언**
- 길이 **9.0초**, 화면 **16:9**, 목표 해상도 **1920×1080**(제약 시 720p 이상), **30 fps / H.264 + AAC** 목표.
- 음향: 엔진 점화음 → 시네마틱 음악 상승 → 여운이 있는 브랜드 엔드카드.

## 3. 9초 스토리보드 v1

### SCENE 01 | 성취 | 0.0–2.5초

- **목표 메시지:** 대한민국의 독자적인 우주 발사 역량을 보여준다.
- **화면 구성:** 누리호를 *연상시키는 AI 생성* 한국형 발사체. 어두운 해안 발사장, 황금빛 강렬한 엔진 화염, 로우앵글, 상승을 추적하는 카메라. **화면 카피 있음.**
- **화면 카피:** `우리는 우주에 닿았다.`
- **오디오:** AI로 제작할 깊은 엔진 점화음 + 짧은 시네마틱 임팩트.
- **도구 및 목적:** 이미지 생성 AI로 키 비주얼, 이미지→영상 AI로 발사체 상승 모션, 오디오 생성 AI로 점화음. 아래 도구 선정표의 후보 사용 예정.

**이미지 생성 프롬프트 초안 v1**
```text
A cinematic low-angle view of a Korean orbital launch vehicle inspired by the Nuri rocket, lifting off from a coastal launch complex at twilight. Powerful golden exhaust plume, deep navy sky, realistic aerospace engineering details, dramatic volumetric lighting, photorealistic, premium national space campaign aesthetic, widescreen 16:9 composition, no text, no logos.
```

**비디오 생성/변환 프롬프트 초안**
```text
The rocket rises slowly and powerfully, with expanding exhaust and atmospheric smoke. Smooth upward camera tracking, physically plausible movement, cinematic realism. Keep rocket structure consistent with the reference image.
```

- **출력 결과 요약:** 아직 생성하지 않음. 생성 후 실제 관찰 결과 한 줄 추가.
- **파일명(예정):** `KASA_S01_image_v1.png`, `KASA_S01_motion_v1.mp4`.

### SCENE 02 | 확장 | 2.5–5.5초

- **목표 메시지:** 대한민국의 우주개발이 발사 성공을 넘어 위성 활용과 산업으로 확장된다.
- **화면 구성:** 지구 궤도 위 금속 질감의 소형위성, 푸른 지구 곡면과 황금빛 대기, 부드러운 오비트 카메라. **화면 카피 있음.**
- **화면 카피:** `이제, 더 먼 미래로.`
- **오디오:** AI 제작 신시사이저/오케스트라 음악으로 상승 전환.
- **도구 및 목적:** 이미지 생성 AI로 위성/지구 장면 확정, 비디오 AI로 카메라 모션, 오디오 AI로 전환 음악.

**이미지 생성 프롬프트 초안 v1**
```text
A highly realistic small Earth observation satellite orbiting above the curved blue Earth, illuminated by a golden sunrise. Detailed solar panels, precise metallic textures, deep black space, cinematic wide shot, premium aerospace institutional campaign visual, deep navy and blue color palette, 16:9, no text, no logos.
```

**비디오 생성/변환 프롬프트 초안**
```text
Slow cinematic orbital camera movement around the satellite. The Earth moves subtly in the background with a delicate atmospheric glow. Keep the satellite shape, scale, and solar panels consistent throughout the shot.
```

- **출력 결과 요약:** 아직 생성하지 않음. 생성 후 실제 관찰 결과 한 줄 추가.
- **파일명(예정):** `KASA_S02_image_v1.png`, `KASA_S02_motion_v1.mp4`.

### SCENE 03 | 미래 선언 | 5.5–9.0초

- **목표 메시지:** 대한민국이 다음 우주 시대를 개척한다는 미래 비전을 각인한다.
- **화면 구성:** 달 지평선에서 바라본 푸른 지구, 서서히 전진하는 카메라, 넓은 네거티브 스페이스. 마지막 3.5초 전부 브랜드 인지 구간. **타이틀 및 브랜드명 있음.**
- **화면 카피:** `대한민국, 우주의 다음 장을 열다.`
- **브랜드 서명:** `우주항공청 | KASA`
- **오디오:** AI 제작 음악 클라이맥스와 잔향.
- **도구 및 목적:** 이미지 AI로 미래 비전 키 비주얼, 비디오 AI로 느린 전진 모션, 오디오 AI로 엔딩 사운드.

**이미지 생성 프롬프트 초안 v1**
```text
A breathtaking cinematic view from the lunar surface, looking toward a luminous blue Earth rising above the Moon's horizon. Dramatic golden sunlight, deep navy and black space, photorealistic lunar terrain, majestic and hopeful atmosphere, minimalist composition, generous negative space for a final brand title, 16:9, no text, no logos.
```

**비디오 생성/변환 프롬프트 초안**
```text
Very slow cinematic forward camera movement across the lunar horizon. Earth remains clearly visible and stable. Subtle sunlight bloom, elegant restrained movement, premium space agency campaign aesthetic. Hold a steady composition for the final title.
```

- **출력 결과 요약:** 아직 생성하지 않음. 생성 후 실제 관찰 결과 한 줄 추가.
- **파일명(예정):** `KASA_S03_image_v1.png`, `KASA_S03_motion_v1.mp4`.

## 4. 생성 AI 도구 계획

| 분야 | 1차 후보 | 대체 후보 | 선택 이유 | 실제 사용 |
|---|---|---|---|---|
| 이미지 | ChatGPT 이미지 생성 | Adobe Firefly | 통일된 키 비주얼·장면 구성 생성 | 미실행 |
| 영상 | Higgsfield | Runway | 키 비주얼의 짧은 카메라/피사체 모션 변환 | 미실행 |
| 오디오 | ElevenLabs | Suno | 시네마틱 효과음/배경음악 생성 | 미실행 |

각 도구의 **사용 날짜·요금제(무료/유료)·크레딧·생성횟수·선정 이유·실제 출력**은 사용 후 기록할 것. 접근성·크레딧 정책·사용 권한은 확정 전 별도 점검.

## 5. 프롬프트 수정 전후 실험 계획 (씬 1)

- **수정 전 프롬프트:** `A rocket launching into space, cinematic, realistic.`
- **예상 한계(실측 아님):** 로켓 형상·구도·빛·배경·일관성에 대한 제약이 부족함.
- **수정 후 프롬프트:** 위 SCENE 01의 상세 이미지 프롬프트.
- **수정 이유:** 한국형 로켓을 연상시키는 형태, 해안 발사장, 로우앵글, 황금색 엔진 화염, 공통 딥네이비 무드, 불필요한 텍스트/로고 배제를 상세히 명시해 제어력 강화.
- **수정 전 실제 결과:** 미생성. 추후 파일과 한 줄 관찰 기록 추가.
- **수정 후 실제 결과:** 미생성. 추후 파일과 한 줄 관찰 기록 추가.
- **비교 결론:** **아직 확인 불가**. 전후 결과를 실험한 뒤에만 개선 여부 판단.

## 6. 편집 · 윤리 · 검증

- 컷 편집, 자막, 간단한 색보정, 오디오 레벨 조정 용도로만 일반 영상 편집기 사용.
- 뉴스·공식 채널의 **실제 촬영된 누리호 발사 영상은 최종 광고에 넣지 않음**. 실제 자료는 참고자료로만 검토.
- 공식 KASA 로고는 이용 조건과 과제의 AI 시각 소스 요건을 확인한 뒤 사용 결정. 확인 전에는 `우주항공청 | KASA` 텍스트를 엔드카드에 배치.
- **공식 기관의 실제 광고로 오인되지 않도록** 비공식 학습 프로젝트임을 설명 또는 표시.
- 달·심우주 장면은 **미래 비전**이며 실제 성과로 오인될 설명을 넣지 않음.
- 최종 파일 예정: `KASA_NextSpaceEra_Final_v1.mp4`. 파일 재생·길이·해상도·프레임레이트·코덱·오디오·브랜드 인지 구간 체크.

## 7. 진행 체크리스트

- [x] 공지/필수 제출물/감점 제약 분석
- [x] KASA 캠페인 방향·메시지 확정
- [x] 3씬/9초 스토리보드 v1 작성
- [x] 씬별 이미지·영상 프롬프트 초안 기록
- [ ] 실제 AI 이미지 생성 및 파일 보관
- [ ] SCENE 01 프롬프트 수정 전/후 생성·비교
- [ ] AI 비디오 생성·변환 및 파일 보관
- [ ] AI 오디오 생성 및 파일 보관
- [ ] 편집 및 영상 사양 검증
- [ ] 스토리보드 최종 PDF 완성
- [ ] 광고 MP4 제출본 완성

**주의:** 이 문서는 기획안이며, 스토리보드에 요구되는 '생성 결과 요약'은 실제 미디어 생성 후 업데이트해야 제출 조건을 충족함.
