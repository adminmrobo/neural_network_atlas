# 표지 지시문 — 신경망 구조 도감 · 초파리 로봇 대전 (정사각 1280×1280, 5장)

| 항목 | 내용 |
|---|---|
| 판 | 정사각 S판 1280×1280 (1:1). 사용자 지정 규격이라 스킬의 L판(16:9) 대신 씀 |
| 장수 | 5장: 목차 `cover_00` + 1~4쪽 `cover_01`~`cover_04` |
| 참고 이미지 | 캐릭터 팩(`adminmrobo/fruitfly-lab-expressions` @ea5da3f)의 `doc_e08`, `asst_e13`, `fly_e10`, `robo_e13` 4장을 함께 올림 |
| 공통 금지 | 그림 안 글자·숫자·로고, 무기, 실존 브랜드, 기존 게임·애니메이션 로봇을 닮은 기체, 결과(승패) 암시 |

## 돌려받는 방법

1. Genspark에서 아래 5개 블록을 차례로 붙여 넣어 그림을 만든다. 같은 대화에서 연달아 만들면 그림체가 맞는다.
2. 파일 이름을 키 그대로 바꾼다: `cover_00.png`, `cover_01.png`, `cover_02.png`, `cover_03.png`, `cover_04.png` (JPG·WebP도 됨).
3. 다섯 장을 ZIP 하나로 묶어 보낸다. 일부만 보내도 된다(있는 것만 반영).
4. 받으면: 비율(1:1)·크기(1280 이상 권장)·글자 유무·네 캐릭터 외형을 확인 → WebP로 변환(장당 250 KB 이하 목표) → `assets/img/cover_0N.webp`로 넣고 → 해당 HTML의 표지 자리와 목차 썸네일을 교체 → 390·768·1280 폭에서 확인한다.

## cover_00 — 목차 · 신경망 구조 도감 · 초파리 로봇 대전 (목차)

| 항목 | 내용 |
|---|---|
| 들어가는 곳 | `index.html` 맨 위 표지 |
| 장소 | 밤의 연구실 한가운데. 왼쪽 절반은 도감 서가(큰 책과 벽의 신경망 구조 그림), 오른쪽 절반은 작은 로봇 격납고 |
| 주제 은유 | 책장에서 꺼낸 신경망 그림이 빛줄기가 되어 격납고의 초파리 로봇 머리로 이어진다 — 배우고(도감) 넣어 본다(대전) |
| 네 캐릭터 포즈 | 박사: 가운데 뒤에서 두 팔을 벌려 두 공간을 소개 / 조수: 왼쪽 서가 앞에서 큰 책을 펼쳐 듦 / 초파리 연구원: 왼쪽 아래에서 오른쪽을 보며 손가락으로 로봇을 가리킴 / Money-Robo: 오른쪽 격납고에서 왼쪽을 보며 금화를 반짝 들어 보임 |
| 대체 글 (alt) | 밤의 연구실 왼쪽은 신경망 도감 서가, 오른쪽은 초파리 로봇 격납고이고, 네 캐릭터가 두 공간 사이에 모인 목차 표지 |

**Genspark에 붙여 넣기 ↓**
```
정사각형 그림 1장을 만들어 줘.
- 크기 1280×1280 픽셀 (1:1)
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, Money-Robo)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 8% 안쪽에, 왼쪽 아래 구석은 어둡고 단순하게
아래 영어 프롬프트를 그대로 써 줘.

Square illustration, 1280 x 1280 pixels, 1:1.
Match the art style, proportions and colors of the attached reference images exactly
(if there are no reference images: 16-bit RPG style pixel art, bold dark outline, 2-3 tone shading, small highlights).
Cozy night laboratory mood, purple light, soft magenta and green fluorescent accents.
Scene: a night laboratory split into two halves: on the left a tall bookshelf wing with a giant open book and a wall chart made only of colorful circles connected by thin lines, on the right a small robot hangar with a small original robot shaped like a fruit fly (round blue armor, big red compound-eye visor, gold stripe, transparent wings, six short legs), not resembling any existing anime or game robot standing under a spotlight; a soft beam of light flows from the open book to the robot's head.
All four characters together:
  chibi scientist, round glasses, black hair with one white streak, white lab coat over black vest and tie, at the back center with both arms open, introducing both halves;
  girl researcher, pink hair in two round buns with a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, in front of the bookshelf on the left, holding a big open book with blank pages;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, on the left facing right, pointing at the robot;
  round white floating robot, short antenna, black face screen with yellow pixel eyes, blue chest light, no legs, oval shadow below, on the right facing left, holding up a shiny gold coin.
Light falls on the beam of light between the book and the robot.
Mood: curious, friendly rivalry, the moment before the result.
Composition: keep every face and hand inside the central safe area (8% margin on all sides); keep the bottom-left corner (25% wide, 15% tall) dark and simple.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same four characters, same art style and composition, still 1:1 square. Change only: {고칠 점}. Still no text.`

## cover_01 — 1쪽 · 신경망 구조 도감 ① 원본 차트의 27가지

| 항목 | 내용 |
|---|---|
| 들어가는 곳 | `1_neural_network_atlas_chart.html` 맨 위 표지 + 목차 썸네일 |
| 장소 | 밤의 연구실 도감 서가. 벽 한 면을 가득 채운 큰 차트(동그라미와 선만, 글자 없음) |
| 주제 은유 | 벽 차트에서 동그라미 몇 개가 떠올라 작은 카드처럼 하나씩 넘겨진다 — 차트를 한 장씩 살펴보는 도감 |
| 네 캐릭터 포즈 | 박사: 가운데 뒤에서 지휘봉 없이 손바닥으로 벽 차트를 가리킴 / 조수: 오른쪽에서 떠오른 카드를 받아 정리 / 초파리 연구원: 왼쪽에서 오른쪽을 보며 돋보기로 카드 하나를 들여다봄 / Money-Robo: 오른쪽 위에 떠서 왼쪽을 보며 카드 묶음을 세는 몸짓 |
| 대체 글 (alt) | 네 캐릭터가 동그라미와 선으로 된 큰 신경망 구조 차트 앞에서 카드처럼 떠오른 구조도를 하나씩 살펴보는 표지 |

**Genspark에 붙여 넣기 ↓**
```
정사각형 그림 1장을 만들어 줘.
- 크기 1280×1280 픽셀 (1:1)
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, Money-Robo)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 8% 안쪽에, 왼쪽 아래 구석은 어둡고 단순하게
아래 영어 프롬프트를 그대로 써 줘.

Square illustration, 1280 x 1280 pixels, 1:1.
Match the art style, proportions and colors of the attached reference images exactly
(if there are no reference images: 16-bit RPG style pixel art, bold dark outline, 2-3 tone shading, small highlights).
Cozy night laboratory mood, purple light, soft magenta and green fluorescent accents.
Scene: a calm night laboratory library wing; one entire wall is covered by a giant chart made only of colored circles (yellow, green, orange, blue, pink) connected by thin gray lines, arranged in many small groups, with no writing; several small groups float off the wall as glowing cards.
All four characters together:
  chibi scientist, round glasses, black hair with one white streak, white lab coat over black vest and tie, at the back center, open palm pointing at the wall chart;
  girl researcher, pink hair in two round buns with a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, on the right, receiving a floating card and sorting it into a neat stack;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, on the left facing right, looking at one card through a magnifying glass;
  round white floating robot, short antenna, black face screen with yellow pixel eyes, blue chest light, no legs, oval shadow below, floating at the upper right facing left, counting a small stack of cards.
Light falls on the wall chart and the floating cards.
Mood: curious, friendly rivalry, the moment before the result.
Composition: keep every face and hand inside the central safe area (8% margin on all sides); keep the bottom-left corner (25% wide, 15% tall) dark and simple.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same four characters, same art style and composition, still 1:1 square. Change only: {고칠 점}. Still no text.`

## cover_02 — 2쪽 · 신경망 구조 도감 ② 그 뒤에 나온 15가지

| 항목 | 내용 |
|---|---|
| 들어가는 곳 | `2_neural_network_atlas_after.html` 맨 위 표지 + 목차 썸네일 |
| 장소 | 도감 서가 옆에 새로 생긴 전시실. 작은 전시대 다섯 곳 |
| 주제 은유 | 전시대마다 새 구조의 은유 — 형광펜 빛줄기가 뻗은 문장 카드(어텐션), 김 서린 유리창을 닦아 드러나는 풍경(확산), 점과 선이 빛나는 그물(그래프), 마지막 전시대의 초파리 뇌 배선 점구름(커넥톰) |
| 네 캐릭터 포즈 | 박사: 가운데 뒤에서 새 전시실 문을 활짝 염 / 조수: 김 서린 유리창을 천으로 닦음 / 초파리 연구원: 왼쪽에서 오른쪽을 보며 초파리 뇌 점구름 전시대를 가리킴 / Money-Robo: 오른쪽에서 왼쪽을 보며 형광펜 빛줄기 전시대에 감탄 |
| 대체 글 (alt) | 새 전시실에서 형광펜 빛줄기, 김 서린 유리창, 빛나는 그물, 초파리 뇌 배선 점구름 전시대를 네 캐릭터가 둘러보는 표지 |

**Genspark에 붙여 넣기 ↓**
```
정사각형 그림 1장을 만들어 줘.
- 크기 1280×1280 픽셀 (1:1)
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, Money-Robo)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 8% 안쪽에, 왼쪽 아래 구석은 어둡고 단순하게
아래 영어 프롬프트를 그대로 써 줘.

Square illustration, 1280 x 1280 pixels, 1:1.
Match the art style, proportions and colors of the attached reference images exactly
(if there are no reference images: 16-bit RPG style pixel art, bold dark outline, 2-3 tone shading, small highlights).
Cozy night laboratory mood, purple light, soft magenta and green fluorescent accents.
Scene: a new exhibition room next to the library wing with five small display stands: a row of blank sentence cards crossed by highlighter-colored light beams, a foggy glass pane half wiped clean revealing a clear landscape, a glowing web of dots and lines, a small glowing loop, and on the last stand a magenta and green point cloud shaped like a fruit fly brain.
All four characters together:
  chibi scientist, round glasses, black hair with one white streak, white lab coat over black vest and tie, at the back center opening the double doors of the new room;
  girl researcher, pink hair in two round buns with a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, wiping the foggy glass pane with a cloth;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, on the left facing right, pointing at the fruit fly brain point cloud;
  round white floating robot, short antenna, black face screen with yellow pixel eyes, blue chest light, no legs, oval shadow below, on the right facing left, amazed by the highlighter light beams.
Light falls on the fruit fly brain point cloud on the last stand.
Mood: curious, friendly rivalry, the moment before the result.
Composition: keep every face and hand inside the central safe area (8% margin on all sides); keep the bottom-left corner (25% wide, 15% tall) dark and simple.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same four characters, same art style and composition, still 1:1 square. Change only: {고칠 점}. Still no text.`

## cover_03 — 3쪽 · 초파리 로봇 대전 ① 이식 규칙과 사양표

| 항목 | 내용 |
|---|---|
| 들어가는 곳 | `3_fruitfly_robot_rules.html` 맨 위 표지 + 목차 썸네일 |
| 장소 | 격납고 옆 정비 작업대 |
| 주제 은유 | 놋쇠 저울 위에 크기가 다른 뇌 모듈 둘, 글자 없는 눈금판 다섯 개, 크기가 점점 커지는 배터리 네 개 — 같은 저울에 올리기 위한 규칙 |
| 네 캐릭터 포즈 | 박사: 가운데 뒤에서 초파리 로봇 설계도(선만, 글자 없음)를 펼쳐 듦 / 조수: 오른쪽에서 줄자로 배터리 크기를 잼 / 초파리 연구원: 왼쪽에서 오른쪽을 보며 돋보기로 저울 눈금을 확인 / Money-Robo: 오른쪽에서 왼쪽을 보며 큰 보라 모듈을 저울에 올리려 함 |
| 대체 글 (alt) | 정비 작업대에서 네 캐릭터가 놋쇠 저울, 눈금판, 크기가 다른 배터리 네 개로 초파리 로봇 이식 규칙을 정하는 표지 |

**Genspark에 붙여 넣기 ↓**
```
정사각형 그림 1장을 만들어 줘.
- 크기 1280×1280 픽셀 (1:1)
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, Money-Robo)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 8% 안쪽에, 왼쪽 아래 구석은 어둡고 단순하게
아래 영어 프롬프트를 그대로 써 줘.

Square illustration, 1280 x 1280 pixels, 1:1.
Match the art style, proportions and colors of the attached reference images exactly
(if there are no reference images: 16-bit RPG style pixel art, bold dark outline, 2-3 tone shading, small highlights).
Cozy night laboratory mood, purple light, soft magenta and green fluorescent accents.
Scene: a maintenance workbench beside a small robot hangar: a brass balance scale holding a small green brain module and a large purple brain module, five round gauge dials with blank faces, four battery cells in a row from tiny to large, and a blueprint of a small original robot shaped like a fruit fly (round blue armor, big red compound-eye visor, gold stripe, transparent wings, six short legs), not resembling any existing anime or game robot drawn only with lines.
All four characters together:
  chibi scientist, round glasses, black hair with one white streak, white lab coat over black vest and tie, at the back center holding up the line-only blueprint;
  girl researcher, pink hair in two round buns with a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, on the right measuring the battery cells with a tape measure;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, on the left facing right, checking the scale with a magnifying glass;
  round white floating robot, short antenna, black face screen with yellow pixel eyes, blue chest light, no legs, oval shadow below, on the right facing left, about to place the big purple module on the scale.
Light falls on the brass balance scale.
Mood: curious, friendly rivalry, the moment before the result.
Composition: keep every face and hand inside the central safe area (8% margin on all sides); keep the bottom-left corner (25% wide, 15% tall) dark and simple.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same four characters, same art style and composition, still 1:1 square. Change only: {고칠 점}. Still no text.`

## cover_04 — 4쪽 · 초파리 로봇 대전 ② RPG로 보는 신경망 매치

| 항목 | 내용 |
|---|---|
| 들어가는 곳 | `4_fruitfly_robot_match.html` 맨 위 표지 + 목차 썸네일 |
| 장소 | 로봇 격납고. 바닥에 RPG 전투 무대처럼 빛나는 격자 |
| 주제 은유 | 머리 덮개가 열린 초파리 로봇 위로 여러 색의 뇌 모듈이 떠 있고, 무대 건너편에는 귀여운 그림자 보스 실루엣 — 어느 뇌를 넣어 싸울지 고르는 순간 |
| 네 캐릭터 포즈 | 박사: 가운데 뒤에서 두 손에 보랏빛 불꽃 / 조수: 오른쪽 옆에서 글자 없는 줄무늬 점검표를 듦 / 초파리 연구원: 왼쪽에서 오른쪽을 보며 작게 빛나는 초록 모듈 하나를 손에 듦 / Money-Robo: 오른쪽에서 왼쪽을 보며 가장 큰 보라 모듈을 두 팔로 안음 |
| 대체 글 (alt) | 격납고의 빛나는 격자 무대에서 네 캐릭터가 초파리 로봇에 넣을 뇌 모듈을 고르고, 건너편에 그림자 보스가 기다리는 표지 |

**Genspark에 붙여 넣기 ↓**
```
정사각형 그림 1장을 만들어 줘.
- 크기 1280×1280 픽셀 (1:1)
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, Money-Robo)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 8% 안쪽에, 왼쪽 아래 구석은 어둡고 단순하게
아래 영어 프롬프트를 그대로 써 줘.

Square illustration, 1280 x 1280 pixels, 1:1.
Match the art style, proportions and colors of the attached reference images exactly
(if there are no reference images: 16-bit RPG style pixel art, bold dark outline, 2-3 tone shading, small highlights).
Cozy night laboratory mood, purple light, soft magenta and green fluorescent accents.
Scene: a robot hangar whose floor glows with an RPG battle grid; in the center stands a small original robot shaped like a fruit fly (round blue armor, big red compound-eye visor, gold stripe, transparent wings, six short legs), not resembling any existing anime or game robot with its head hatch open, several glowing brain-module cards (circles and lines only) floating above it; across the grid waits a cute, non-scary dark shadow blob boss with small amber eyes.
All four characters together:
  chibi scientist, round glasses, black hair with one white streak, white lab coat over black vest and tie, at the back center with purple sparks in both hands;
  girl researcher, pink hair in two round buns with a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, at the right side holding a blank striped checklist;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, on the left facing right, holding one small softly glowing green module;
  round white floating robot, short antenna, black face screen with yellow pixel eyes, blue chest light, no legs, oval shadow below, on the right facing left, hugging the largest and brightest purple module with both arms.
Light falls on the open head hatch of the fly robot.
Mood: curious, friendly rivalry, the moment before the result.
Composition: keep every face and hand inside the central safe area (8% margin on all sides); keep the bottom-left corner (25% wide, 15% tall) dark and simple.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands.
```

**고칠 때 (같은 대화에서):** `Same four characters, same art style and composition, still 1:1 square. Change only: {고칠 점}. Still no text.`
