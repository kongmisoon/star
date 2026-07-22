# Anna Wedding Director
### AI 기반 브랜드 광고 패키지 · 스토리보드(기획) 문서

---

## 1. 브랜드 아이덴티티

| 항목 | 내용 |
|---|---|
| **브랜드명** | Anna Wedding Director |
| **타겟 고객** | 결혼을 앞둔 25~35세 예비 신부. 웨딩 준비 전 과정을 믿고 맡길 파트너를 찾는 사람들, 특히 획일적인 패키지보다 자신만의 취향이 반영된 결과물을 원하는 고객 |
| **톤앤매너** | 따뜻하고 진심 어린(Warm & Sincere) + 조용한 럭셔리(Quiet Luxury). 화려함을 과시하기보다, 신부 한 사람 한 사람에게 집중하는 다정하고 신뢰감 있는 분위기 |
| **차별점 (USP)** | ① 해외 최신 시즌 드레스 소싱 ② 한국 최고 수준 스튜디오·메이크업 아티스트와의 협업 네트워크 ③ 드레스 선택부터 스튜디오 촬영, 메이크업까지 전 일정 '동행'하며 요구 사항을 세심하게 반영하는 1:1 웨딩 디렉팅 |

---

## 2. 캠페인 목표 및 핵심 메시지

| 항목 | 내용 |
|---|---|
| **광고 목적** | 인지(Awareness) 확대 + 상담 신청 전환(Conversion) 유도 |
| **핵심 메시지** | "당신의 가장 빛나는 순간, Anna가 처음부터 끝까지 함께합니다." |
| **영상 길이** | 9초 (10초 이내 규정 충족) |
| **화면 비율** | 기본 9:16(숏폼/릴스) · 보너스로 16:9, 1:1 추가 제작 권장 |

---

## 3. 사용 도구 목록 (주 도구 / 대체 도구)

| 구분 | 주 도구 | 대체 도구 | 사용 목적 |
|---|---|---|---|
| 이미지 생성 | Midjourney v6 | Adobe Firefly | 신부·드레스·스튜디오 장면의 기준 비주얼 생성, 캐릭터·화풍 고정용 sref(스타일 레퍼런스) 설정 |
| 비디오 생성/변환 | Runway Gen-3 (Image to Video) | Kling AI, Pika | 정지 이미지에 패닝·줌 등 자연스러운 모션 부여, 씬 간 카메라 무빙 통일 |
| 음성(내레이션) 합성 | ElevenLabs | Typecast | 차분하고 다정한 여성 내레이션 톤 생성, 전 씬 동일 보이스로 톤앤매너 일관 유지 |
| 배경음악(BGM) | Suno AI | Udio | 피아노 중심의 따뜻한 무드 트랙 생성, 마지막 CTA 구간에서 감정 고조 |
| 통합 편집 | CapCut | Premiere Pro | 컷 편집, 자막(슬로건) 삽입, 오디오 레벨 조정 — 신규 비주얼/오디오 생성 없이 통합 용도로만 사용 |

---

## 4. 씬(Scene) 구성

총 4개 씬 · 기승전결(문제 제시 → 전환 → 해결/제안 → 브랜드 각인) 구조로 구성. 마지막 3초 구간에 로고와 슬로건, CTA를 배치하여 브랜드 인지 장치를 충족한다.

### SCENE 1 · 0:00–0:02 · 2초
**목표 메시지:** 웨딩 준비의 막막함 — 공감 형성

| 항목 | 내용 |
|---|---|
| **화면 구성** | 구도: 클로즈업 → 미디엄샷 / 피사체: 예비 신부(20대 후반, 자연스러운 표정) / 배경: 어수선한 다이어리·잡지·샘플 원단이 놓인 테이블 / 텍스트: 없음 |
| **내레이션/카피** | "결혼 준비, 어디서부터 시작해야 할지 막막하셨나요" |
| **사용 도구** | 이미지: Midjourney (인물·오브젝트 생성) → 비디오: Runway Gen-3 (미세한 줌인 모션 적용) / 목적: 신부의 고민을 사실적이고 공감가는 톤으로 시각화 |
| **입력 프롬프트** | `cinematic close-up of a young Korean bride-to-be sitting at a table covered with wedding magazines and fabric swatches, soft window light, contemplative expression, warm neutral tones, shallow depth of field, photorealistic --ar 9:16 --sref [고정 스타일 코드]` |
| **출력 요약** | 따뜻한 창가 조명 아래, 고민하는 신부의 자연스러운 표정 컷 확보 |
| **파일명** | scene01_bride_thinking_v2.mp4 |

**▸ 프롬프트 수정 전 / 후 (Scene 1 예시)**

| 구분 | 내용 | 수정 이유 |
|---|---|---|
| **수정 전** | "a bride looking at wedding magazines, worried face" | 표정이 과장된 '걱정'으로 표현되어 브랜드 톤(따뜻함)과 상충, 배경/조명 정보 부재로 결과물마다 톤이 들쭉날쭉했음 |
| **수정 후** | "contemplative expression, soft window light, warm neutral tones, shallow depth of field, photorealistic --sref [고정 스타일 코드]" | 감정을 '걱정'이 아닌 '고민·설렘'으로 완화하고, 조명·색감·심도 등 구체 조건과 스타일 레퍼런스를 고정해 이후 전 씬과 톤앤매너를 통일시키기 위함 |

---

### SCENE 2 · 0:02–0:045 · 2.5초
**목표 메시지:** '동행'이라는 차별점 전달 — 전환

| 항목 | 내용 |
|---|---|
| **화면 구성** | 구도: 투샷(2-shot), 좌우 배치 / 피사체: 신부 + Anna(웨딩 디렉터), 드레스 룸 / 배경: 해외 시즌 드레스가 걸린 쇼룸 / 텍스트: 없음 |
| **내레이션/카피** | "Anna는 드레스 선택부터, 촬영까지 처음부터 함께합니다" |
| **사용 도구** | 이미지: Midjourney (동일 인물 cref 고정) → 비디오: Runway Gen-3 (패닝 모션) / 목적: '동행'이라는 서비스 차별점을 시각적으로 전환(문제→해결의 다리) 역할로 배치 |
| **입력 프롬프트** | `two women in a bright wedding dress showroom, one trying on an elegant imported gown, the other gently adjusting the veil with a warm caring gesture, soft golden light, editorial photography style --ar 9:16 --cref [신부 얼굴 레퍼런스] --sref [고정 스타일 코드]` |
| **출력 요약** | 신부와 Anna가 함께 드레스를 살피는 다정한 동행 장면 확보 |
| **파일명** | scene02_dress_fitting_v1.mp4 |

---

### SCENE 3 · 0:045–0:07 · 2.5초
**목표 메시지:** 완성된 결과물로 신뢰·설득 — 해결/제안

| 항목 | 내용 |
|---|---|
| **화면 구성** | 구도: 풀샷 → 클로즈업 몽타주 / 피사체: 완성된 신부(메이크업·드레스), 촬영 스태프 / 배경: 프로페셔널 스튜디오, 조명 장비 / 텍스트: 없음 |
| **내레이션/카피** | "한국 최고의 아티스트들과, 당신만의 화보를 완성합니다" |
| **사용 도구** | 이미지: Midjourney (cref 고정) → 비디오: Runway Gen-3 (슬로우 줌아웃, 플래시 이펙트) / 목적: 결과물의 '완성도'를 보여주는 하이라이트 구간으로 신뢰감 극대화 |
| **입력 프롬프트** | `full studio shot of a bride in a couture wedding gown, flawless makeup, professional photographer and lighting crew around her, camera flash freezing the moment, luxurious editorial atmosphere --ar 9:16 --cref [신부 얼굴 레퍼런스] --sref [고정 스타일 코드]` |
| **출력 요약** | 플래시가 터지는 순간의 완성된 신부 화보 컷 확보 |
| **파일명** | scene03_studio_shoot_v1.mp4 |

---

### SCENE 4 · 0:07–0:09 · 2초
**목표 메시지:** 브랜드 각인 및 CTA

| 항목 | 내용 |
|---|---|
| **화면 구성** | 구도: 중앙 정렬 타이틀 컷 / 피사체: 로고 + 슬로건 텍스트 / 배경: 스튜디오 톤과 이어지는 뉴트럴 베이지 그라데이션 / 텍스트: 있음 (로고, 슬로건, CTA) |
| **내레이션/카피** | "Anna Wedding Director — 상담 예약은 프로필 링크에서" |
| **사용 도구** | 이미지: Midjourney (배경 텍스처) + 편집 도구(CapCut) 자막 삽입 / 목적: 규정된 '마지막 3~5초 브랜드 인지 장치(로고·슬로건·CTA)' 충족 |
| **입력 프롬프트** | `minimal beige gradient background, soft bokeh light particles, elegant and warm atmosphere for wedding brand outro, negative space for text overlay --ar 9:16 --sref [고정 스타일 코드]` |
| **출력 요약** | 로고·슬로건·CTA 자막을 얹기 좋은 여백형 배경 확보 |
| **파일명** | scene04_outro_logo_v1.mp4 |

---

## 5. 오디오 구성

| 구분 | 도구 | 내용 |
|---|---|---|
| **내레이션** | ElevenLabs | 차분하고 다정한 여성 보이스, 전 씬 동일 보이스 ID 고정으로 톤 일관성 유지. 프롬프트: "calm, warm, sincere female voice, gentle pacing, Korean" |
| **BGM** | Suno AI | 피아노+스트링 중심의 따뜻한 무드 트랙, 마지막 2초 구간에서 감정 고조되도록 다이나믹 설계. 프롬프트: "warm emotional piano and strings, wedding brand film, gentle build-up, 9 seconds, uplifting ending" |

---

## 6. 캐릭터·스타일 일관성 유지 전략

- **--cref (Character Reference)**: Scene 1에서 생성한 신부 얼굴 이미지를 기준으로 Scene 2, 3에 동일하게 고정 적용하여 인물 동일성 유지
- **--sref (Style Reference)**: 전 씬 공통 스타일 코드를 고정하여 색감·조명·에디토리얼 톤을 통일 (웜톤 베이지·골드 계열)
- **화면 비율 고정**: 전 씬 9:16으로 통일 제작 후, 보너스 과제로 16:9 / 1:1 파생 버전 제작
- **보이스 ID 고정**: ElevenLabs 보이스 클론 ID를 전 구간 동일하게 사용해 오디오 톤 미스매치 방지

---

## 7. 제작 리스크 대응 전략

- **크레딧 부족 시**: 6씬 → 4씬으로 축소하고 메시지 밀도를 높이는 전략을 채택 (본 스토리보드에 이미 반영)
- **정지 이미지 활용**: 영상 변환 크레딧이 부족할 경우 Scene 3, 4는 정지 이미지 + 줌·패닝 모션으로 대체 가능
- **도구 접근성 대응**: 비디오 생성 도구가 대기열로 막힐 경우 Kling AI 또는 Pika로 즉시 전환, 오디오는 Udio 또는 Typecast로 대체 가능하도록 사전 계획

---

*Anna Wedding Director · AI 브랜드 광고 스토리보드 · 최종 영상 9초 / 9:16*
