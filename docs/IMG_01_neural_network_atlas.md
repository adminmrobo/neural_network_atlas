# 01번 「신경망 구조 도감 · 초파리 로봇 대전」 이미지 제작 명세서 (1~4쪽 묶음)

| 항목 | 내용 |
|---|---|
| 페이지 | 1_neural_network_atlas_chart.html · 2_neural_network_atlas_after.html · 3_fruitfly_robot_rules.html · 4_fruitfly_robot_match.html |
| 표지 배치 (갱신) | 2026-11-01: 정사각 1280×1280 표지 5장(목차 + 1~4쪽 각각)으로 바꿈. 지시문은 docs/COVER_PROMPTS_square.md. 아래의 16:9 표지 항목은 이전 안 |
| 표지 배치 (이전) | 1쪽에 `cover_01` 전체 표지, 2·3·4쪽은 같은 그림을 낮은 띠(`cover_ch1`, 16:5 자르기)로 재사용. 새로 그리지 않음 |
| 모드 / 주 앵커 | 교과서 / A 생물 (①②③⑥⑦칸), 보조 D 일상 (④⑤칸 — 어텐션·생성은 초파리 대응 없음) |
| 시즌 | 기본 + "로봇 격납고" 장면 구절: *small robot hangar inside the night lab* |
| 대결 | 날아오는 그림자 보스, 커넥톰 모형 vs 트랜스포머. 체급별: 초파리 몸 F (192 대 0, 트랜스포머 탑재 불가) · 드론 F (192 대 60) · 노트북 R (192 대 300) · 서버 R (192 대 540). 기본 표시는 초파리 몸 F, 차이 0.96 |
| 새로 그릴 그림 | P1 3장 · P2 3장 · P3 2장 |
| 재사용 | 표정 23키 + 컷인 1키 (캐릭터 팩 @ea5da3f, base64로 이미 넣음) |
| 그림이 없을 때 | 페이지는 캐릭터 팩 표정 + 픽셀 초파리 로봇 + CSS 배경으로 이미 완성 상태 |

## 1. 그림체와 고정 외형
- 스타일: SKILL 18-3 (16비트 RPG 픽셀아트, 굵은 외곽선, 2~3단계 명암)
- 캐릭터 고정 외형: SKILL 18-4 표 그대로
- 초파리 로봇(새 소품, 고정): 둥근 파란 장갑, 빨간 겹눈 바이저, 금색 줄, 투명 날개, 짧은 다리 여섯. **기존 게임·애니메이션 기체를 닮지 않게.**
- 장소 영어 묘사: *small robot hangar inside a night laboratory, a fluorescence microscope bench at one side, cables on the floor, soft spotlight from above*

## 2. 필요한 그림 전체

| # | 키 | 판 | 크기 | 상태 | 우선 | 들어가는 곳 | 대신 쓰는 그림 |
|---|---|---|---|---|---|---|---|
| 0 | cover_00~cover_04 | S (정사각) | 1280×1280 | 새로 (COVER_01_neural_network_atlas.md) | P1 | 1쪽 맨 위 글 표지, 2~4쪽 띠 | 캐릭터 팩 4인 + CSS 배경 |
| 1 | bg_01 | F | 1920×720 | 새로 | P3 (표지 있음) | 히어로 오른쪽 배경 | 픽셀 초파리 로봇 (코드) |
| 2 | mech_fly | E | 1200×800 | 새로 | P1 | 4쪽 격납고 전투 장면 왼쪽 기체, 3·4쪽 히어로 | 픽셀 지도 MECH (코드) |
| 3 | cut_01_cutin | G | 960×540 | 새로 | P1 | 전투 컷인 띠 | fly_cutin (팩 fly_e16 192px) |
| 4 | boss_set_01 | G | 960×540 | 새로 | P2 | 과제 보스 8종 (한 장에 2×4 배치, 잘라 씀) | 코드로 그린 보스 |
| 5 | sc_01_outro | E | 1200×800 | 새로 | P2 | 아웃트로 | 없음 (말풍선만) |
| 6 | thumb_01 | I | 600×400 | 새로 (cover_01 자르기) | P2 | 목차 카드 | 색 카드 |
| 7 | og_01 | K | 1200×630 | 새로 | P3 | 공유 미리보기 | 없음 |
| — | doc_front, doc_think, doc_judge, doc_magic, doc_scale | A | 팩 96px | 재사용 (doc_scale은 팩에 저울 없음 → doc_e13 기본) | — | 히어로·판정·아웃트로 | doc_front |
| — | asst_smile, asst_firm, asst_ledger, asst_spark, asst_shock | B | 팩 96px | 재사용 (asst_ledger는 팩에 장부 없음 → asst_e07) | — | 숫자 발표 | asst_smile |
| — | fly_clip, fly_point, fly_arms, fly_coffee, fly_cry, fly_magnify | C | 팩 96px | 재사용 | — | 대결 전·후 | fly_clip |
| — | robo_smile, robo_coin, robo_happy, robo_sigh, robo_meh, robo_wow, robo_blush | D | 팩 96px | 재사용 | — | 대결 전·후 | robo_smile |
| — | 전투 효과 13종, 보스 8종, 구조도 42개 | — | — | 코드 | — | Canvas·SVG | — |

대결 결과 F(초파리 몸·드론) → 결과 후 표정 `fly_arms`, `robo_sigh`. 노트북 R(차이 0.54)·서버 R(차이 1.74)은 10%p 이상이라 `fly_cry`, `robo_happy`. 판정 `doc_judge`, 발표 `asst_ledger` (5-8절 표와 일치).

## 3. 새로 그릴 그림 상세

### 3-1. `mech_fly` — 초파리 로봇 기체 (전투 왼쪽)
| 항목 | 내용 |
|---|---|
| 판 · 크기 | E판 비율을 쓰되 투명 배경 단독 기체, 1200×800 (정수배 가능) |
| 배경 | 투명 (안 되면 #00ff00 단색) |
| 구도 | 기체 하나가 가운데, 오른쪽을 보고 서 있음, 화면 높이의 80% |
| 표정·몸짓 | 겹눈 바이저가 빛남, 날개를 살짝 펼침, 공격 전 준비 자세(팔을 앞으로) |
| 소품 | 가슴의 파란 표시등, 등 뒤 작은 배터리 칸 (눈금 없음) |
| 빛·분위기 | 윗쪽 스포트라이트, 발밑 초록 형광 |
| 피할 것 | 무기, 칼, 총, 실존 게임 기체 닮음, 글자 |
| 대체 글 (alt) | 장식 (전투 캔버스 안) — `alt=""` |
| 대신 쓰는 그림 | 픽셀 지도 MECH |

**프롬프트 (복사해서 사용)**
```
16-bit RPG style pixel art, bold dark outline, 2–3 tone shading, small highlights, consistent with the reference images, cozy night laboratory mood, purple light, soft magenta and green fluorescent accents, single character, transparent background, centered with a small margin, facing right, full body, a small original robot shaped like a fruit fly with round blue armor, a big red compound-eye visor, a gold stripe, transparent wings slightly spread and six short legs, a blue chest light, arms forward in a ready pose, green fluorescent glow under its feet, not resembling any existing anime or game robot, no text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands
```

### 3-2. `cut_01_cutin` — 필살기 컷인
| 항목 | 내용 |
|---|---|
| 판 · 크기 | G · 960×540 |
| 배경 | 그림 전체, 비스듬한 노란 띠 위 어두운 띠 (오른쪽 60%는 비워 둠 — 기술 이름이 HTML·캔버스로 얹힘) |
| 구도 | 초파리 연구원이 왼쪽 40%에서 오른쪽을 보며 조종석에 앉아 한 손을 앞으로 뻗음, 가슴 위 |
| 표정·몸짓 | 자신만만한 눈 (`fly_arms` 계열), 집중선 |
| 소품 | 조종 손잡이 두 개(글자 없는 버튼), 헬멧 전선이 바람에 날림 |
| 빛·분위기 | 노란 섬광, 속도선 |
| 피할 것 | 승패 암시, 글자, 실존 게임의 컷인 구도 그대로 따라 하기 |
| 대체 글 (alt) | 장식 — `alt=""` |
| 대신 쓰는 그림 | fly_cutin (팩 fly_e16 192px) |

**프롬프트 (복사해서 사용)**
```
16-bit RPG style pixel art, bold dark outline, 2–3 tone shading, small highlights, consistent with the reference images, cozy night laboratory mood, purple light, soft magenta and green fluorescent accents, 16:9 illustration panel, a diagonal yellow band with a dark inner band across the frame, anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, seated in a small cockpit on the left 40% of the frame facing right, one hand stretched forward, confident eyes, speed lines and a yellow flash behind, the right 60% of the frame left empty and simple, no text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands
```

### 3-3. `boss_set_01` — 과제 보스 8종
| 항목 | 내용 |
|---|---|
| 판 · 크기 | G · 960×540, 2행 4열 칸에 하나씩 |
| 배경 | 칸마다 단색 #00ff00 (잘라 쓴 뒤 지움) |
| 구도 | 각 보스가 왼쪽을 보며 칸 가운데, 칸 높이의 75% |
| 표정·몸짓 | 무섭지 않고 귀여운 얼굴, 작은 점 눈 |
| 소품 | ① 숫자 칸이 뭉친 바위 거인(칸에 글자 없음) ② 말랑한 흐린 슬라임 ③ 꼬리가 길게 이어진 구슬 뱀 ④ 하얀 빈 캔버스 유령 ⑤ 조각이 빠진 퍼즐 정령 ⑥ 매듭진 노란 실뭉치 ⑦ 커지며 다가오는 그림자 덩어리 ⑧ 벽이 뒤섞인 상자 미로 |
| 빛·분위기 | 보스마다 고유색(코드의 ENEMY.col과 같게) |
| 피할 것 | 피, 이빨, 공포 표현, 글자 |
| 대체 글 (alt) | 과제 보스 목록 칸의 `aria-label`에 보스 이름을 이미 씀 |
| 대신 쓰는 그림 | 코드로 그린 보스 |

**프롬프트 (복사해서 사용)**
```
16-bit RPG style pixel art, bold dark outline, 2–3 tone shading, small highlights, cozy night laboratory mood, purple light, sprite sheet of eight cute non-scary boss monsters in a 2 by 4 grid, each on a solid flat #00ff00 cell background, each facing left with small dot eyes: a rock golem made of stacked blank tiles, a soft blurry blue slime, a long bead snake whose tail fades into the distance, a white blank-canvas ghost, a puzzle spirit with two missing pieces, a tangled yellow ball of yarn, a growing dark shadow blob with small amber eyes, a box maze with shuffled walls, no text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands
```

### 3-4. `sc_01_outro` — 아웃트로 (결과 F 기준)
| 항목 | 내용 |
|---|---|
| 판 · 크기 | E · 1200×800 |
| 구도 | 앞·크게: 초파리 연구원(팔짱)과 작은 초록 모듈을 넣은 초파리 로봇. 뒤에 주판봇이 큰 보라 모듈을 안고 머리를 긁으며 인정하는 몸짓, 박사는 가운데 뒤, 조수는 오른쪽에서 점검표 |
| 피할 것 | 조롱, 패자를 작게 짓밟는 구도, 글자 |
| 대체 글 (alt) | 초파리 연구원이 작은 뇌 모듈을 넣은 로봇 옆에서 팔짱을 끼고, 주판봇이 큰 모듈을 안고 머쓱해하는 연구실 장면 |
| 대신 쓰는 그림 | 없음 (말풍선만) |

**프롬프트 (복사해서 사용)**
```
16-bit RPG style pixel art, bold dark outline, 2–3 tone shading, small highlights, consistent with the reference images, cozy night laboratory mood, purple light, soft magenta and green fluorescent accents, 3:2 landscape scene, medium brightness, small robot hangar inside a night laboratory, in front and larger: anthropomorphic fruit fly researcher with big red compound eyes and a blue helmet with a gold stripe, arms crossed proudly, next to a small original fly-shaped robot with a softly glowing green module in its open head hatch; behind on the right: JUPANBOT (AbaBot), a boxy beige retro CRT-monitor robot with rounded corners and thick dark brown outlines, a large dark green screen on the front where the face is drawn only with simple mint-green pixel blocks, a short thin antenna on a small square base topped with one tiny red-brown abacus bead, gray segmented arms with rounded gray mitten hands, two small dark gray tank treads instead of legs hugging a large purple module and scratching its head with a sheepish smile; chibi scientist with round glasses and black hair with one white streak at the back center giving a small nod; girl researcher with pink hair in two round buns and a navy streak at the right holding a blank striped checklist, friendly mood, no text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands, no white round robot head, no yellow or golden eyes, no floating robot, no gold coins
```

### 3-5. `bg_01` · `thumb_01` · `og_01`
- `bg_01` (P3): 표지가 생기면 표지를 잘라 쓴다. 따로 그린다면 3-1 프롬프트의 장소 묘사 + *wide 8:3 background, left side simple and calm for title text, details on the right, no characters*.
- `thumb_01` (P2): cover_01를 3:2로 가운데 기준 자르기.
- `og_01` (P3): cover_01를 1200×630으로 자르기, 초파리 로봇과 모듈이 가운데.

## 4. 일관성 지침
- 참고 이미지: 캐릭터 팩 `character_pack_ea5da3f` (`preview_all_96.png`, 192px WebP)
- 같은 캐릭터는 같은 세션에서, 시드 고정 가능하면 고정
- 표정만 바꿀 때: *same character, same size and position, only change the facial expression and pose to ...*
- 초파리 로봇은 `mech_fly`를 먼저 만들고, 표지·아웃트로에 그 그림을 참고 이미지로 함께 넣는다

## 5. 넘겨받은 뒤 처리
1. 크기·투명 배경 확인, #00ff00 제거 (`build_character_pack.py --ingest ./받은그림 --plates mech_fly=E,cut_01_cutin=G,boss_set_01=G`)
2. WebP 압축, 페이지 그림 합계 표지 제외 400 KB 이하 (현재 표정 팩 158 KB)
3. `SPRITE` 객체에 키를 채우면 코드 그림 대신 쓰인다 (`fly_cutin` 자리는 이미 연결됨, `mech_fly`·보스는 캔버스 그리기 함수에 연결 필요)
4. 표지는 SKILL 18-15 절차

## 6. 체크리스트
- [x] HTML의 `data-img` 키(cover_01, bg_01, 표정 키)가 명세서에 있음
- [x] 대결 결과 후 표정이 5-8절과 일치 (F → fly_arms·robo_sigh, 서버 R·차이 10%p 이상 → fly_cry·robo_happy)
- [x] 결과 전 그림에 승패 암시 없음
- [x] 모든 프롬프트에 금지 구절, 실존 기체 닮지 않게
- [x] P1 3장 (표지 제외 2장)
- [x] 그림 안 글자 없음

## 7. 매니페스트
```json
{
  "page": "01_neural_network_atlas",
  "anchor": "A:robot-hangar",
  "season": "default",
  "duel": {"result": "F", "gap": 0.96, "by_tier": {"fly": "F", "drone": "F", "laptop": "R", "server": "R"}},
  "images": [
    {"key":"cover_01","plate":"L","size":[1920,1080],"status":"new","priority":"P1","slot":"cover","fallback":"pack-four+css","alt":"밤의 연구실 로봇 격납고에서 네 캐릭터가 초파리 로봇에 넣을 뇌 모듈을 고르는 표지"},
    {"key":"mech_fly","plate":"E","size":[1200,800],"status":"new","priority":"P1","slot":"arena-left","fallback":"pixel-MECH","alt":""},
    {"key":"cut_01_cutin","plate":"G","size":[960,540],"status":"new","priority":"P1","slot":"arena-cutin","fallback":"fly_cutin","alt":""},
    {"key":"boss_set_01","plate":"G","size":[960,540],"status":"new","priority":"P2","slot":"arena-right","fallback":"code-boss","alt":""},
    {"key":"sc_01_outro","plate":"E","size":[1200,800],"status":"new","priority":"P2","slot":"outro","fallback":"none","alt":"초파리 연구원이 작은 뇌 모듈을 넣은 로봇 옆에서 팔짱을 끼고, 주판봇이 큰 모듈을 안고 머쓱해하는 연구실 장면"},
    {"key":"thumb_01","plate":"I","size":[600,400],"status":"new","priority":"P2","slot":"index-card","fallback":"cover_01-crop","alt":"신경망 구조 도감 · 초파리 로봇 대전 썸네일"},
    {"key":"bg_01","plate":"F","size":[1920,720],"status":"new","priority":"P3","slot":"hero-bg","fallback":"pixel-MECH","alt":"로봇 격납고가 있는 밤의 연구실"},
    {"key":"og_01","plate":"K","size":[1200,630],"status":"new","priority":"P3","slot":"og","fallback":"none","alt":"신경망 구조 도감 · 초파리 로봇 대전 공유 이미지"},
    {"key":"fly_cutin","plate":"C","size":[192,192],"status":"reuse","source":"pack fly_e16","slot":"arena-cutin","alt":""},
    {"key":"doc_scale","plate":"A","size":[96,96],"status":"reuse-near","source":"pack doc_e13 (저울 없음)","slot":"draw","alt":""},
    {"key":"asst_ledger","plate":"B","size":[96,96],"status":"reuse-near","source":"pack asst_e07 (장부 없음)","slot":"duel-after","alt":""}
  ]
}
```
