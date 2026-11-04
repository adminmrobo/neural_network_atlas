> 이전 안(16:9). 현재는 docs/COVER_PROMPTS_square.md를 쓴다.

# 표지 지시문 — 01 신경망 구조 도감 · 초파리 로봇 대전

| 항목 | 내용 |
|---|---|
| 키 · 판 | cover_01 · L (16:9, 1920 이상) |
| 장소 (앵커) | A 생물 앵커 변형: 밤의 연구실 안쪽의 작은 로봇 격납고. 형광 현미경 실험대가 한쪽에 남아 있다 |
| 주제 은유 | 격납고 가운데 초파리 모양의 작은 로봇이 서 있고, 머리 덮개가 열린 자리 위로 여러 색의 빛나는 "뇌 모듈" 카드(동그라미와 선만 그려진 도식, 글자 없음)가 떠 있다. 어느 모듈을 넣을지 고르는 순간 |
| 네 캐릭터 포즈 | 박사: 가운데 뒤에서 두 손에 보랏빛 불꽃, 떠 있는 모듈들을 가리킴 / 조수: 오른쪽 옆에서 빈 줄무늬 점검표를 들고 로봇의 배터리 칸을 확인 / 초파리 연구원: 왼쪽에서 오른쪽을 보며 작고 은은하게 빛나는 초록 모듈 하나를 손에 듦 / 주판봇: 오른쪽에서 왼쪽을 보며 가장 크고 밝은 보라 모듈을 두 팔로 안음 |
| 대체 글 (alt) | 밤의 연구실 로봇 격납고에서 박사, 조수, 초파리 연구원, 주판봇이 초파리 로봇에 넣을 뇌 모듈을 고르는 표지 |
| 앞 표지와 다른 점 | 블록·게임 화면 없이, 로봇 격납고와 떠 있는 모듈 카드가 주인공. 대결 구도는 같지만 결과 암시 없음 |

**참고 이미지 (함께 올리기):** 네 캐릭터 기본 그림 4장 — 캐릭터 팩(`adminmrobo/fruitfly-lab-expressions` @ea5da3f)의 `doc_e08`, `asst_e13`, `fly_e10`, `robo_e13` (192px 또는 원본 PNG).

**Genspark에 붙여 넣기 ↓**
```
웹페이지 맨 위에 거는 표지 그림 1장을 만들어 줘.
- 비율 16:9, 가로 1920px 이상
- 첨부한 참고 이미지의 네 캐릭터(박사, 조수, 초파리 연구원, 주판봇)를 같은 그림체·같은 외형으로, 넷 모두 등장
- 그림 안에 글자·숫자·로고를 넣지 말 것
- 얼굴과 손은 가장자리에서 떨어진 가운데 영역에, 왼쪽 아래 구석은 어둡고 단순하게
- 로봇은 특정 게임·애니메이션의 기체를 닮지 않은, 초파리 모양의 작고 둥근 오리지널 로봇
아래 영어 프롬프트를 그대로 써 줘.

Website top cover illustration, wide 16:9.
Match the art style, proportions and colors of the attached reference images exactly
(if there are no reference images: 16-bit RPG style pixel art, bold dark outline, 2–3 tone shading, small highlights).
Cozy night laboratory mood, purple light, soft magenta and green fluorescent accents.
Scene: a small robot hangar inside a night laboratory, a fluorescence microscope bench at one side, cables on the floor, soft spotlight from above.
In the center stands a small original robot shaped like a fruit fly (round blue armor, big red compound-eye visor, transparent wings, six short legs), its head hatch open; above it float several glowing brain-module cards showing only circles and connecting lines, in different colors and sizes.
All four characters together:
  chibi scientist, round glasses, black hair with one white streak, white lab coat over black vest and tie, at the back center with purple sparks in both hands, pointing at the floating modules;
  girl researcher, pink hair in two round buns with a navy streak, blue eyes, white lab coat over lavender hoodie, jeans, standing at the right side checking a blank striped checklist next to the robot's battery panel;
  anthropomorphic fruit fly researcher, black body, big red compound eyes, blue helmet with a gold stripe and pink and blue cables, white lab coat, transparent wings, on the left facing right, holding one small softly glowing green module;
  JUPANBOT (AbaBot), a boxy beige retro CRT-monitor robot with rounded corners and thick dark brown outlines, a large dark green screen on the front where the face is drawn only with simple mint-green pixel blocks, a short thin antenna on a small square base topped with one tiny red-brown abacus bead, gray segmented arms with rounded gray mitten hands, two small dark gray tank treads instead of legs, on the right facing left, hugging the largest and brightest purple module with both arms.
Visual metaphor of the topic: choosing which brain to install in a tiny robot, small efficient module versus big powerful module, no text.
Composition: keep every face and hand inside the central safe area (12% margin left and right, 10% top, 18% bottom);
keep the bottom-left corner dark and simple; the light falls on the open head hatch of the fly robot.
Mood: curious, friendly rivalry, the moment before the result.
No text, no letters, no numbers, no logos, no weapons, no cigarettes, no alcohol, no blood, no real brands, no white round robot head, no yellow or golden eyes, no floating robot, no gold coins, not resembling any existing anime or game robot.
```

**고칠 때 (같은 대화에서):** `Same four characters, same art style and composition. Change only: {고칠 점}. Still no text.`

## 점검 (SKILL 18-15-1)
- [x] 네 캐릭터의 18-4 영어 묘사, 좌우 방향, 안전 영역, 금지 구절
- [x] 결과 암시 없음 (두 모듈 모두 빛남, 누가 이길지 보이지 않음)
- [x] 무기 없음 — 로봇 전투는 페이지 안 연출로만, 표지는 격납고 장면
- [x] HTML에 `data-img="cover_01"` 자리와 대체 표지(캐릭터 팩 4인 + CSS 배경) 있음
