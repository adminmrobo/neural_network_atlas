**[한국어](#ko) · [English](#en) · [中文](#zh) · [日本語](#ja) · [Oʻzbekcha](#uz) · [Русский](#ru) · [Tiếng Việt](#vi)**

---

<a id="ko"></a>

# 신경망 구조 도감 · 초파리 로봇 대전

신경망 구조 42가지를 도감으로 정리하고, 초파리만 한 로봇의 뇌에 하나씩 넣었을 때의 사양과 성능을 RPG 대전으로 비교하는 4쪽짜리 해설입니다.
박사·조수·초파리 연구원·Money-Robo 네 캐릭터가 진행합니다.

- 글: 안상선 ((주)M-Robo 대표)
- 온라인으로 보기: `https://adminmrobo.github.io/neural-network-atlas/` (저장소 이름에 맞게 고칠 것)
- 시작 쪽: [`index.html`](index.html)

## 언어

이 시리즈는 한국어 원본과 외국어판 6개로 볼 수 있다.

- 고르는 방법: 화면 최상단 메뉴의 🌐 언어 선택 상자나 오른쪽 아래 🌐 배너에서 고른다. 고른 언어는 브라우저에 기억된다.
- 자동 전환: 한국어 페이지에 처음 들어오면, 브라우저 언어가 지원 언어일 때 그 언어판으로 옮겨 간다. 번역판 주소로 들어오면 그대로 연다.
- 주소 끝에 `?lang=en`처럼 붙이면 그 언어로 바로 연다.
- 언어판 파일은 `이름.언어코드.html` 꼴이다.

<!-- i18n:langtable -->
| 언어 | 파일 이름 | 바로 보기 |
|---|---|---|
| 한국어 | `index.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [바로 보기](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## 구성

| 쪽 | 파일 | 제목 | 내용 |
|---|---|---|---|
| 목차 | [`index.html`](index.html) | 신경망 구조 도감 · 초파리 로봇 대전 | 네 쪽 안내, 읽는 순서, 주요 출처 |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.html) | 신경망 구조 도감 ① 원본 차트의 27가지 | 원본 신경망 구조 차트의 27가지를 여섯 묶음으로 다시 그리고, 무엇을 하는지와 강점·약점을 담담하게 정리합니다. |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.html) | 신경망 구조 도감 ② 그 뒤에 나온 15가지 | 차트 뒤에 나온 트랜스포머, 확산 모델, 맘바, 그래프 신경망 등 15가지와 초파리 뇌 배선도로 만든 모형을 소개합니다. |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.html) | 초파리 로봇 대전 ① 이식 규칙과 사양표 | 42가지를 같은 저울에 올리는 규칙을 공개합니다. 사양표, 규칙표, 계산 따라 하기, 전원 체급, 능력치 실험실. |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.html) | 초파리 로봇 대전 ② RPG로 보는 신경망 매치 | 격납고에서 신경망을 골라 초파리 로봇에 넣고 필살기 장면을 봅니다. 체급 사다리, 대결, 42가지 성적표. |

1·2쪽은 구조 해설(점수·전투 없음), 3·4쪽은 비교 규칙과 대전입니다. 모든 쪽 맨 위의 이동 띠로 오갈 수 있습니다.
4쪽 격납고는 주소 끝에 `#m-모델ID`를 붙이면 그 모델이 바로 열립니다. 예: `4_fruitfly_robot_match.html#m-lstm`

## 보는 방법

- 온라인: GitHub Pages 주소로 접속합니다.
- 내 컴퓨터: 저장소를 내려받아 `index.html`을 더블클릭합니다. 서버나 설치가 필요 없습니다.

## 폴더 구조

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## GitHub Pages 설정

1. 이 폴더의 파일을 저장소 맨 위(루트)에 올립니다.
2. 저장소 **Settings → Pages**에서 **Source: Deploy from a branch**, 브랜치 `main`, 폴더 `/ (root)`를 고르고 저장합니다.
3. 몇 분 뒤 `https://<계정>.github.io/<저장소>/`에서 열립니다. 이 README 위쪽의 주소를 실제 주소로 고칩니다.

## 기술 메모

- 각 쪽은 HTML 파일 하나에 CSS·JS를 모두 담았습니다. 외부 라이브러리와 외부 요청이 없습니다.
- 캐릭터 표정 그림(`assets/img/chars/`)과 표지 그림(`assets/img/`)은 네 쪽이 함께 쓰는 파일입니다. HTML만 따로 옮기면 그림 대신 픽셀 캐릭터가 보이므로 `assets/` 폴더째 옮기세요.
- 표지 그림이 없으면 캐릭터 네 명이 선 대체 표지가 보입니다.
- 브라우저 저장소(localStorage 등)를 쓰지 않습니다.
- 각 쪽 맨 끝의 "온톨로지·서지 꾸러미"에서 지식 그래프(JSON-LD, Turtle, CSV)와 참고문헌(CSL-JSON, BibTeX, RIS)을 ZIP으로 받을 수 있습니다.

## 표지 그림 작업 순서

1. `docs/COVER_PROMPTS_square.md`의 블록 5개를 Genspark에 붙여 넣어 1280×1280 그림을 만듭니다(참고 이미지: 캐릭터 기본 그림 4장).
2. 파일 이름을 `cover_00.png` ~ `cover_04.png`로 바꿔 ZIP으로 묶습니다.
3. 받은 그림을 WebP로 바꿔 `assets/img/`에 넣고, 각 쪽의 표지 자리(`<!-- lab-cover -->` 표시 사이)와 목차 썸네일을 교체합니다.

## 수업에 쓰기

- 각 쪽 첫 화면에 학습 목표 세 줄과 예상 시간(1쪽 약 25분, 2쪽 20분, 3쪽 20분, 4쪽 25분)이 있습니다.
- `docs/TEACHER_GUIDE.md`에 2회차 수업 구성, 오개념과 바로잡는 말, 과제·평가 예시가 있습니다.
- 확인 퀴즈는 1쪽 12, 2쪽 10, 3쪽 8, 4쪽 8문항이며 점수는 저장되지 않습니다.

## 읽을 때 주의

- 3·4쪽의 능력치 가운데 ATK·HIT는 판단값, SPD·EN·MEM은 계산 방식으로 매긴 등급입니다. 전원 체급·보스 HP·피해 계산식은 설명용 규칙이며 실측값이 아닙니다.
- 초파리 커넥톰 뇌 모형은 과제를 풀도록 만든 모델이 아니어서 대전 순위에서 뺐습니다.
- 3쪽의 '등급을 현장 감각으로 옮기면' 표와 4쪽의 '현장 조건으로 후보 거르기'는 예시 데이터입니다. 실제 장비 선정에는 실측이 필요합니다.

## 주요 출처

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. 외 (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. 외 (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. 외 (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- 모델별 제안 논문은 각 쪽의 참고문헌 꾸러미에 있습니다.

## 인용

> 안상선 (2026). 신경망 구조 도감 · 초파리 로봇 대전. (각 쪽 제목과 쪽 번호를 덧붙임)

## 라이선스

(채워 넣을 것) — 본문·코드·캐릭터 그림의 라이선스를 정해 적어 주세요.
캐릭터 그림 출처: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

이 저장소는 인용한 연구들과 그 저자, HHMI Janelia, Google, Cambridge, Mojang/Microsoft와 관련이 없습니다.

---

<a id="en"></a>

# Neural Network Atlas · Fruit Fly Robot Battle

A four-page explainer that organizes 42 neural network structures in an atlas, then compares their specs and performance in an RPG battle as each one is placed into a robot brain the size of a fruit fly.
Led by four characters: the Doctor, the Assistant, the Fruit Fly Researcher, and Money-Robo.

- Written by: Ahn Sangsun (CEO, M-Robo Inc.)
- View online: `https://adminmrobo.github.io/neural-network-atlas/` (adjust to match the repository name)
- Start page: [`index.html`](index.en.html)

## Languages

This series is available in the Korean original and six translated versions.

- How to choose: pick from the 🌐 language selector in the top menu or the 🌐 banner at the bottom right. The chosen language is remembered in the browser.
- Auto switch: on the first visit to the Korean page, if the browser language is supported, it moves to that language version. If you enter through a translated address, it opens as is.
- Add `?lang=en` (or another language code) to the end of the address to open that language directly.
- Language files follow the pattern `name.langcode.html`.

<!-- i18n:langtable -->
| Languages | File name | View |
|---|---|---|
| 한국어 | `index.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [View](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## Contents

| Pages | Files | Title | Content |
|---|---|---|---|
| Contents | [`index.html`](index.en.html) | Neural Network Atlas · Fruit Fly Robot Battle | Guide to the four pages, reading order, main sources |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.en.html) | Neural Network Atlas ① 27 from the original chart | Redraws the 27 structures in the original neural network chart in six groups, and calmly summarizes what each does and its strengths and weaknesses. |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.en.html) | Neural Network Atlas ② 15 that came after | Introduces 15 structures after the chart, including Transformer, diffusion models, Mamba, and graph neural networks, plus a model built from the fruit fly brain wiring diagram. |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.en.html) | Fruit Fly Robot Battle ① install rules and spec sheet | Makes public the rules for putting 42 structures on the same scale: spec sheet, rule table, step-by-step calculation, power classes, and stat lab. |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.en.html) | Fruit Fly Robot Battle ② Neural Network Match, RPG Style | Choose a neural network in the hangar, install it in the fruit fly robot, and watch its special-move scene. Power ladder, duel, and the 42-structure scorecard. |

Pages 1 and 2 are structural explainers (no scores or battles); pages 3 and 4 are comparison rules and battles. You can move between pages with the navigation strip at the top of each page.
On page 4, adding `#m-modelID` to the end of the address opens that model directly. Example: `4_fruitfly_robot_match.html#m-lstm`

## How to view

- Online: open the GitHub Pages address.
- On your computer: download the repository and double-click `index.html`. No server or installation needed.

## Folder structure

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## GitHub Pages setup

1. Upload the files in this folder to the top (root) of the repository.
2. In the repository **Settings → Pages**, choose **Source: Deploy from a branch**, branch `main`, folder `/ (root)`, and save.
3. In a few minutes it opens at `https://<계정>.github.io/<저장소>/`. Change the address at the top of this README to the actual address.

## Technical notes

- Each page packs its CSS and JS into a single HTML file. There are no external libraries or external requests.
- Character expression images (`assets/img/chars/`) and cover images (`assets/img/`) are files shared by all four pages. If you move only the HTML, pixel characters appear instead of images, so move the whole `assets/` folder.
- If cover images are missing, a placeholder cover showing the four characters standing appears.
- Does not use browser storage (localStorage, etc.).
- From the 'Ontology & bibliography package' at the end of each page, you can download the knowledge graph (JSON-LD, Turtle, CSV) and references (CSL-JSON, BibTeX, RIS) as a ZIP.

## Cover image workflow

1. Paste the 5 blocks in `docs/COVER_PROMPTS_square.md` into Genspark to create 1280×1280 images (reference images: the 4 basic character images).
2. Rename the files to `cover_00.png` through `cover_04.png` and bundle them as a ZIP.
3. Convert the received images to WebP, put them in `assets/img/`, and replace the cover placeholders on each page (between the `<!-- lab-cover -->` markers) and the contents thumbnails.

## Using in class

- Each page's first screen has three learning-goal lines and an estimated time (page 1 about 25 min, page 2 20 min, page 3 20 min, page 4 25 min).
- `docs/TEACHER_GUIDE.md` has the structure of the second class session, misconceptions and corrections, and examples of assignments and assessments.
- Check quizzes have 12 questions on page 1, 10 on page 2, 8 on page 3, and 8 on page 4. Scores are not saved.

## Notes for reading

- Among the stats on pages 3 and 4, ATK and HIT are judged values, and SPD, EN, and MEM are grades set by calculation method. Power classes, boss HP, and damage formulas are explanatory rules, not measured values.
- The fruit fly connectome brain model was excluded from the battle rankings because it was not built to solve tasks.
- The 'Translating the grades into field sense' table on page 3 and 'Filter candidates by field conditions' on page 4 are example data. Real equipment selection requires measurement.

## Main sources

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. et al. (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. et al. (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. et al. (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- The original proposal papers for each model are in the references package on each page.

## Citation

> Ahn Sangsun (2026). Neural Network Atlas · Fruit Fly Robot Battle. (Page titles and page numbers added for each page.)

## License

(to be filled in) — please specify the license for the text, code, and character art.
Character art source: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

This repository is not affiliated with the cited studies or their authors, HHMI Janelia, Google, Cambridge, or Mojang/Microsoft.

---

<a id="zh"></a>

# 神经网络结构图鉴 · 果蝇机器人对战

这是一份四页的解说，将 42 种神经网络整理为图鉴，并把它们逐一放进果蝇大小的机器人脑中，用 RPG 对战比较规格与性能。
由博士、助手、果蝇研究员、Money-Robo 四个角色主持。

- 作者: Ahn Sangsun（M-Robo 公司 CEO）
- 在线查看: `https://adminmrobo.github.io/neural-network-atlas/` （请按仓库名修改）
- 起始页: [`index.html`](index.zh.html)

## 语言

本系列提供韩语原版及 6 种外语版本。

- 选择方法：在页面最上方菜单的 🌐 语言选择框或右下角 🌐 横幅中选择。所选语言会保存在浏览器中。
- 自动切换：首次进入韩语页面时，若浏览器语言为支持的语言，会切换到该语言版本。通过译本地址进入则直接打开。
- 在地址末尾加上 `?lang=en` 这样的参数即可直接以该语言打开。
- 语言版文件名格式为 `名称.语言代码.html`。

<!-- i18n:langtable -->
| 语言 | 文件名 | 直接查看 |
|---|---|---|
| 한국어 | `index.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [直接查看](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## 构成

| 页 | 文件 | 标题 | 内容 |
|---|---|---|---|
| 目录 | [`index.html`](index.zh.html) | 神经网络结构图鉴 · 果蝇机器人对战 | 四页导览、阅读顺序、主要出处 |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.zh.html) | 神经网络结构图鉴 ① 原始图表的27种 | 将原始神经网络结构图表中的27种分为六组重新绘制，平实地整理各自的用途以及优缺点。 |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.zh.html) | 神经网络结构图鉴 ② 其后出现的 15 种 | 介绍图表之后出现的Transformer、扩散模型、Mamba、图神经网络等15种，以及用果蝇大脑布线图制作的模型。 |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.zh.html) | 果蝇机器人对战 ① 植入规则与规格表 | 公开把42种放上同一天平的规则。规格表、规则表、跟着计算、电源级别、能力值实验室。 |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.zh.html) | 果蝇机器人对战 ② 用 RPG 看神经网络对决 | 在机库中选择神经网络植入果蝇机器人，观看必杀技场面。电源级别阶梯、对决、42种成绩单。 |

第 1·2 页为结构解说（无评分、无战斗），第 3·4 页为比较规则与对战。每页最上方的导航条可互相切换。
第 4 页机库可在网址末尾加上 `#m-模型ID` 直接打开该模型。例：`4_fruitfly_robot_match.html#m-lstm`

## 查看方法

- 在线：访问 GitHub Pages 地址。
- 本机：下载仓库后双击 `index.html`。无需服务器或安装。

## 文件夹结构

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## GitHub Pages 设置

1. 将此文件夹中的文件上传到仓库最上层（root）。
2. 在仓库 **Settings → Pages** 中选择 **Source: Deploy from a branch**，分支 `main`，文件夹 `/ (root)`，然后保存。
3. 几分钟后将在 `https://<계정>.github.io/<저장소>/` 打开。把本 README 上方的地址改成实际地址。

## 技术说明

- 每页都将 CSS·JS 全部包含在一个 HTML 文件中。没有外部库与外部请求。
- 角色表情图（`assets/img/chars/`）与封面图（`assets/img/`）是四页共用的文件。若只单独移动 HTML，图会变成像素角色，因此请连同 `assets/` 文件夹一起移动。
- 若没有封面图，会显示四个角色的线稿替代封面。
- 不使用浏览器存储（localStorage 等）。
- 每页末尾的“本体·文献包”可以以 ZIP 下载知识图谱（JSON-LD、Turtle、CSV）与参考文献（CSL-JSON、BibTeX、RIS）。

## 封面图制作步骤

1. 将 `docs/COVER_PROMPTS_square.md` 中的 5 个代码块粘贴到 Genspark，生成 1280×1280 图（参考图：角色基础图 4 张）。
2. 将文件名改为 `cover_00.png` ～ `cover_04.png`，然后打包为 ZIP。
3. 将收到的图片转为 WebP 放入 `assets/img/`，并替换各页的封面位置（`<!-- lab-cover -->` 标记之间）及目录缩略图。

## 用于授课

- 每页开头有三行学习目标及预计时间（第 1 页约 25 分钟，第 2 页 20 分钟，第 3 页 20 分钟，第 4 页 25 分钟）。
- `docs/TEACHER_GUIDE.md` 中有第 2 次课的构成、误解与纠正用语、作业与评价示例。
- 确认测验分别为第 1 页 12 题、第 2 页 10 题、第 3 页 8 题、第 4 页 8 题，分数不会保存。

## 阅读注意

- 第 3·4 页的能力中，ATK·HIT 为判断值，SPD·EN·MEM 为按计算方式评定的等级。电源级别、首领 HP、伤害计算式均为说明用规则，并非实测值。
- 果蝇连接组脑模型并非为完成任务而设计，因此已从对战排名中去掉。
- 第 3 页的“将等级转换为现场感觉”表与第 4 页的“按现场条件筛选候选”均为示例数据。实际设备选型需要实测。

## 主要出处

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. 等 (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. 等 (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. 等 (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- 各模型的原始论文见各页的参考文献包。

## 引用

> Ahn Sangsun (2026). 神经网络结构图鉴 · 果蝇机器人对战. （可附加各页标题与页码）

## 许可协议

（待填写）— 请确定并写明正文、代码、角色图的许可协议。
角色图出处: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

本仓库与所引用的研究及其作者、HHMI Janelia、Google、Cambridge、Mojang/Microsoft 均无关联。

---

<a id="ja"></a>

# ニューラルネットワーク構造図鑑 · ショウジョウバエロボット対戦

ニューラルネットワーク構造42種を図鑑にまとめ、ショウジョウバエほどの大きさのロボットの脳に一つずつ入れたときの仕様と性能を、RPG形式の対戦で比べる4ページの解説です。
博士・助手・ショウジョウバエ研究員・Money-Robo の四人のキャラクターが進行します。

- 文: Ahn Sangsun (株式会社M-Robo 代表)
- オンラインで見る: `https://adminmrobo.github.io/neural-network-atlas/`（リポジトリ名に合わせて変更してください）
- 開始ページ: [`index.html`](index.ja.html)

## 言語

このシリーズは韓国語の原本と、外国語版6つで読めます。

- 選び方: 画面最上部のメニューの 🌐 言語選択ボックス、または右下の 🌐 バナーから選びます。選んだ言語はブラウザに記憶されます。
- 自動切り替え: 韓国語のページに初めて入ると、ブラウザの言語が対応言語の場合、その言語版へ移動します。翻訳版のアドレスから入った場合は、そのまま開きます。
- アドレスの末尾に `?lang=en` のように付けると、その言語で直接開きます。
- 言語版のファイルは `名前.言語コード.html` の形式です。

<!-- i18n:langtable -->
| 言語 | ファイル名 | すぐ見る |
|---|---|---|
| 한국어 | `index.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [すぐ見る](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## 構成

| ページ | ファイル | タイトル | 内容 |
|---|---|---|---|
| 目次 | [`index.html`](index.ja.html) | ニューラルネットワーク構造図鑑 · ショウジョウバエロボット対戦 | 4ページの案内、読む順序、主な出典 |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.ja.html) | ニューラルネットワーク構造図鑑 ① 元のチャートの27種 | 元のニューラルネットワーク構造チャートの27種を六つのまとまりに描き直し、何をするのか、強みと弱みを淡々と整理します。 |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.ja.html) | ニューラルネットワーク構造図鑑 ② その後に登場した15種 | チャートの後に登場した Transformer、拡散モデル、Mamba、グラフニューラルネットワークなど15種と、ショウジョウバエの脳配線図から作ったモデルを紹介します。 |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.ja.html) | ショウジョウバエロボット対戦 ① 移植ルールと仕様表 | 42種を同じ天秤に載せるルールを公開します。仕様表、規則表、計算をたどる、電源クラス、能力値実験室。 |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.ja.html) | ショウジョウバエロボット対戦 ② RPGで見るニューラルネットワーク対戦 | 格納庫でニューラルネットワークを選んでショウジョウバエロボットに入れ、必殺技のシーンを見ます。電源クラスのはしご、対決、42種の成績表。 |

1・2ページは構造の解説（点数・戦闘なし）、3・4ページは比較ルールと対戦です。どのページ上部の移動バーからも行き来できます。
4ページの格納庫は、アドレスの末尾に `#m-モデルID` を付けると、そのモデルがすぐ開きます。例: `4_fruitfly_robot_match.html#m-lstm`

## 見方

- オンライン: GitHub Pages のアドレスにアクセスします。
- 自分のパソコン: リポジトリをダウンロードして `index.html` をダブルクリックします。サーバーやインストールは不要です。

## フォルダ構成

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## GitHub Pages の設定

1. このフォルダのファイルを、リポジトリの最上位（ルート）にアップロードします。
2. リポジトリの **Settings → Pages** で、**Source: Deploy from a branch**、ブランチ `main`、フォルダ `/ (root)` を選んで保存します。
3. 数分後に `https://<계정>.github.io/<저장소>/` で開きます。このREADME上部のアドレスを実際のアドレスに書き換えます。

## 技術メモ

- 各ページは HTML ファイル1つに CSS・JS をすべて含めています。外部ライブラリや外部へのリクエストはありません。
- キャラクターの表情画像（`assets/img/chars/`）と表紙画像（`assets/img/`）は四ページが共有するファイルです。HTML だけを別の場所へ移すと、画像の代わりにピクセルキャラクターが見えるので、`assets/` フォルダごと移してください。
- 表紙画像がない場合は、キャラクター四人が並ぶ代替表紙が表示されます。
- ブラウザのストレージ（localStorage など）は使っていません。
- 各ページ末尾の「オントロジー・書誌パッケージ」から、知識グラフ（JSON-LD, Turtle, CSV）と参考文献（CSL-JSON, BibTeX, RIS）を ZIP でダウンロードできます。

## 表紙画像の作業手順

1. `docs/COVER_PROMPTS_square.md` の5つのブロックを Genspark に貼り付けて、1280×1280 の画像を作ります（参考画像: キャラクターの基本画像4枚）。
2. ファイル名を `cover_00.png` 〜 `cover_04.png` に変え、ZIP にまとめます。
3. 受け取った画像を WebP に変換して `assets/img/` に入れ、各ページの表紙の場所（`<!-- lab-cover -->` の印の間）と目次のサムネイルを差し替えます。

## 授業で使う

- 各ページの最初の画面に、学習目標3行と予想時間（1ページ約25分、2ページ20分、3ページ20分、4ページ25分）があります。
- `docs/TEACHER_GUIDE.md` には、2回目の授業構成、誤概念と正し方、課題・評価の例があります。
- 確認クイズは1ページ12問、2ページ10問、3ページ8問、4ページ8問で、点数は保存されません。

## 読むときの注意

- 3・4ページの能力値のうち、ATK·HITは判断値、SPD·EN·MEMは計算方式で付けた等級です。電源クラス・ボスHP・ダメージの計算式は説明用のルールで、実測値ではありません。
- ショウジョウバエのコネクトーム脳モデルは課題を解くように作られたモデルではないため、対戦の順位からは外しました。
- 3ページの「等級を現場の感覚に置き換えると」の表と、4ページの「現場条件で候補を絞る」は例示データです。実際の機器選定には実測が必要です。

## 主な出典

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. 他 (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. 他 (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. 他 (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- モデルごとの提案論文は、各ページの参考文献パッケージにあります。

## 引用

> Ahn Sangsun (2026). ニューラルネットワーク構造図鑑 · ショウジョウバエロボット対戦. (各ページのタイトルとページ番号を付記)

## ライセンス

(記入予定) — 本文・コード・キャラクター画像のライセンスを決めて記載してください。
キャラクター画像の出典: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

このリポジトリは、引用した研究とその著者、HHMI Janelia、Google、Cambridge、Mojang/Microsoftとは関係ありません。

---

<a id="uz"></a>

# Neyron tarmoqlar atlasi · Meva pashshasi robotlari jangi

Neyron tarmoq tuzilmalarining 42 turini atlas qilib jamlab, meva pashshasidek robotning miyasiga birin-ketin joylaganda xususiyatlari va unumdorligini RPG jangi bilan solishtiradigan 4 sahifalik izohli material.
Doktor, Yordamchi, Meva pashshasi tadqiqotchisi va Money-Robo — toʻrt qahramon olib boradi.

- Matn: Ahn Sangsun (M-Robo kompaniyasi rahbari)
- Onlayn koʻrish: `https://adminmrobo.github.io/neural-network-atlas/` (repozitoriy nomiga qarab tuzating)
- Boshlanish sahifasi: [`index.html`](index.uz.html)

## Til

Bu turkumni koreyscha asl nusxada va 6 ta xorijiy tildagi nashrda koʻrish mumkin.

- Tanlash usuli: ekranning eng yuqori menyusidagi 🌐 til tanlash oynasi yoki pastki oʻngdagi 🌐 bannerdan tanlang. Tanlangan til brauzerda eslab qolinadi.
- Avtomatik oʻtish: koreyscha sahifaga birinchi marta kirganda, brauzer tili qoʻllab-quvvatlanadigan til boʻlsa, oʻsha til nashriga oʻtadi. Tarjima nashri manzili bilan kirsangiz, oʻshani ochadi.
- Manzil oxiriga `?lang=en` kabi qoʻshsangiz, oʻsha tilda darhol ochiladi.
- Til nashri fayllari `nom.til_kodi.html` shaklida.

<!-- i18n:langtable -->
| Til | Fayl nomi | Darhol koʻrish |
|---|---|---|
| 한국어 | `index.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [Darhol koʻrish](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## Tarkib

| Sahifa | Fayllar | Sarlavha | Mazmun |
|---|---|---|---|
| Mundarija | [`index.html`](index.uz.html) | Neyron tarmoqlar atlasi · Meva pashshasi robotlari jangi | Toʻrt sahifa qoʻllanmasi, oʻqish tartibi, asosiy manbalar |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.uz.html) | Neyron tarmoqlar atlasi ① Asl jadvaldagi 27 tur | Asl neyron tarmoq tuzilmalari jadvalidagi 27 turni oltita guruhga qayta chizib, nima qilishini hamda kuchli va zaif tomonlarini xotirjam jamlaydi. |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.uz.html) | Neyron tarmoqlar atlasi ② Undan keyin paydo boʻlgan 15 tur | Jadvaldan keyin paydo boʻlgan Transformer, diffuziya modeli, Mamba, graf neyron tarmoq kabi 15 tur va meva pashshasi miyasining sim sxemasidan yasalgan modelni tanishtiradi. |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.uz.html) | Meva pashshasi robotlari jangi ① Oʻrnatish qoidalari va xususiyatlar jadvali | 42 turni bir tarozida tortish qoidalarini ochib beradi. Xususiyatlar jadvali, qoidalar jadvali, hisobni bosqichma-bosqich, quvvat toifasi, koʻrsatkichlar laboratoriyasi. |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.uz.html) | Meva pashshasi robotlari jangi ② RPG uslubidagi neyron tarmoqlar bellashuvi | Angarda neyron tarmoq tanlab, meva pashshasi robotiga joylab, maxsus zarba sahnasini koʻradi. Quvvat toifalari narvoni, bellashuv, 42 turning natijalar jadvali. |

1·2-sahifalar tuzilma izohi (ball·jang yoʻq), 3·4-sahifalar solishtirish qoidalari va jang. Barcha sahifalarning eng yuqoridagi oʻtish chizigʻi orqali oʻtish mumkin.
4-sahifadagi angarni manzil oxiriga `#m-modelID` qoʻshsangiz, oʻsha model darhol ochiladi. Masalan: `4_fruitfly_robot_match.html#m-lstm`

## Koʻrish usullari

- Onlayn: GitHub Pages manziliga kiriladi.
- Oʻz kompyuterimda: repozitoriyni yuklab olib, `index.html` ni ikki marta bosasiz. Server yoki oʻrnatish kerak emas.

## Papka tuzilmasi

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## GitHub Pages sozlamasi

1. Bu papkadagi fayllarni repozitoriyning eng yuqorisiga (ildiz) yuklang.
2. Repozitoriy **Settings → Pages** da **Source: Deploy from a branch**, branch `main`, papka `/ (root)` ni tanlab saqlang.
3. Bir necha daqiqadan soʻng `https://<계정>.github.io/<저장소>/` manzilida ochiladi. Ushbu README yuqorisidagi manzilni haqiqiy manzilga oʻzgartiring.

## Texnik eslatma

- Har bir sahifa bitta HTML faylga CSS·JS ni toʻliq joylagan. Tashqi kutubxona va tashqi soʻrov yoʻq.
- Qahramonlar ifodasi rasmlari (`assets/img/chars/`) va muqova rasmlari (`assets/img/`) toʻrt sahifa birga ishlatadigan fayllar. HTML ni alohida koʻchirsangiz rasm oʻrniga piksel qahramonlar koʻrinadi, shuning uchun `assets/` papkasini birga koʻchiring.
- Muqova rasmi boʻlmasa, toʻrt qahramon turgan zaxira muqova koʻrinadi.
- Brauzer xotirasi (localStorage va h.k.) ishlatilmaydi.
- Har bir sahifaning eng oxiridagi «Ontologiya va bibliografiya toʻplami»dan bilimlar grafi (JSON-LD, Turtle, CSV) va adabiyotlar roʻyxati (CSL-JSON, BibTeX, RIS) ni ZIP qilib olish mumkin.

## Muqova rasmi ish tartibi

1. `docs/COVER_PROMPTS_square.md` dagi 5 ta blokni Genspark ga qoʻyib, 1280×1280 rasm yaratiladi (maʼlumot rasmlari: qahramonlarning asosiy rasmlari 4 ta).
2. Fayl nomlarini `cover_00.png` ~ `cover_04.png` ga oʻzgartirib ZIP qilinadi.
3. Olingan rasmlarni WebP ga aylantirib `assets/img/` ga qoʻyiladi va har bir sahifaning muqova oʻrni (`<!-- lab-cover -->` belgilari orasi) hamda mundarija miniatyurasi almashtiriladi.

## Darsda ishlatish

- Har bir sahifaning birinchi ekranida uchta oʻquv maqsadi va taxminiy vaqt (1-sahifa taxminan 25 daqiqa, 2-sahifa 20 daqiqa, 3-sahifa 20 daqiqa, 4-sahifa 25 daqiqa) bor.
- `docs/TEACHER_GUIDE.md` da 2 seanslik dars tuzilmasi, notoʻgʻri tushunchalar va ularni tuzatish soʻzlari, topshiriq·baholash misollari bor.
- Tekshiruv testlari 1-sahifada 12, 2-sahifada 10, 3-sahifada 8, 4-sahifada 8 ta savol boʻlib, ball saqlanmaydi.

## Oʻqishda eʼtibor bering

- 3·4-sahifalardagi koʻrsatkichlardan ATK·HIT baholangan qiymat, SPD·EN·MEM hisoblash usuli bilan qoʻyilgan daraja. Quvvat toifalari, boss HP si va zarar formulasi tushuntirish uchun qoidalar boʻlib, oʻlchangan qiymat emas.
- Meva pashshasi konnektomi asosidagi miya modeli vazifa yechish uchun yasalgan model emas, shuning uchun jang reytingidan chiqarilgan.
- 3-sahifadagi «Darajalarni amaliyot hissiga oʻtkazsak» jadvali va 4-sahifadagi «Maydon shartlari bilan nomzodlarni saralash» misol maʼlumotlar. Haqiqiy uskuna tanlashda oʻlchov kerak.

## Asosiy manbalar

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. va boshq. (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. va boshq. (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. va boshq. (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- Modellar boʻyicha taklif qilingan maqolalar har bir sahifaning adabiyotlar toʻplamida.

## Iqtibos

> Ahn Sangsun (2026). Neyron tarmoqlar atlasi · Meva pashshasi robotlari jangi. (Har bir sahifa sarlavhasi va sahifa raqami qoʻshiladi)

## Litsenziya

(toʻldirilishi kerak) — matn·kod·qahramon rasmlari litsenziyasini belgilab yozing.
Qahramon rasmlari manbasi: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

Ushbu repozitoriy keltirilgan tadqiqotlar va ularning mualliflari, HHMI Janelia, Google, Cambridge, Mojang/Microsoft bilan bogʻliq emas.

---

<a id="ru"></a>

# Атлас нейросетей · Битва роботов-дрозофил

Пояснение на 4 страницах: 42 архитектуры нейросетей собраны в атлас, а их характеристики и производительность при установке по одной в мозг робота размером с дрозофилу сравниваются в RPG-битве.
Ведущие — четыре персонажа: Доктор, ассистент, Исследователь-дрозофила и Money-Robo.

- Автор: Ан Сансон (Ahn Sangsun) (генеральный директор M-Robo)
- Смотреть онлайн: `https://adminmrobo.github.io/neural-network-atlas/` (исправьте в соответствии с названием репозитория)
- Стартовая страница: [`index.html`](index.ru.html)

## Язык

Серию можно смотреть в корейском оригинале и в 6 иноязычных версиях.

- Как выбрать: выберите язык в списке 🌐 в верхнем меню экрана или на баннере 🌐 справа внизу. Выбранный язык запоминается в браузере.
- Автоматическое переключение: при первом заходе на корейскую страницу, если язык браузера поддерживается, открывается версия на этом языке. Если зайти по адресу переведённой версии, она открывается как есть.
- Если добавить в конец адреса, например, `?lang=en`, страница сразу откроется на этом языке.
- Файлы языковых версий имеют вид `имя.код_языка.html`.

<!-- i18n:langtable -->
| Язык | Имя файла | Открыть сразу |
|---|---|---|
| 한국어 | `index.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [Открыть сразу](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## Состав

| Страница | Файлы | Название | Содержание |
|---|---|---|---|
| Оглавление | [`index.html`](index.ru.html) | Атлас нейросетей · Битва роботов-дрозофил | Путеводитель по четырём страницам, порядок чтения, основные источники |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.ru.html) | Атлас нейросетей ① 27 архитектур исходной схемы | Перерисовывает 27 архитектур исходной схемы нейросетей в шести группах и спокойно описывает, что они делают, их сильные и слабые стороны. |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.ru.html) | Атлас нейросетей ② 15 архитектур, появившихся позже | Знакомит с 15 архитектурами, появившимися после схемы, — трансформером, диффузионной моделью, Mamba, графовой нейронной сетью и др. — и с моделью, построенной по схеме проводки мозга дрозофилы. |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.ru.html) | Битва роботов-дрозофил ① Правила установки и таблица характеристик | Раскрывает правила, по которым 42 архитектуры ставятся на одни весы: таблица характеристик, таблица правил, расчёт по шагам, классы питания, лаборатория характеристик. |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.ru.html) | Битва роботов-дрозофил ② Матчи нейросетей в стиле RPG | Выберите в ангаре нейросеть, установите её в робота-дрозофилу и посмотрите сцену коронного приёма. Лестница классов питания, поединок, табель 42 моделей. |

Страницы 1 и 2 — разбор структур (без очков и боёв), страницы 3 и 4 — правила сравнения и битва. Переходить между страницами можно по ленте навигации вверху каждой страницы.
В ангаре на странице 4, если добавить в конец адреса `#m-ID_модели`, эта модель откроется сразу. Пример: `4_fruitfly_robot_match.html#m-lstm`

## Как смотреть

- Онлайн: заходите по адресу GitHub Pages.
- На своём компьютере: скачайте репозиторий и дважды щёлкните `index.html`. Сервер и установка не нужны.

## Структура папок

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## Настройка GitHub Pages

1. Загрузите файлы из этой папки в корень репозитория.
2. В **Settings → Pages** репозитория выберите **Source: Deploy from a branch**, ветку `main` и папку `/ (root)` и сохраните.
3. Через несколько минут сайт откроется по адресу `https://<계정>.github.io/<저장소>/`. Исправьте адрес в верхней части этого README на реальный.

## Технические заметки

- Каждая страница — один HTML-файл со всеми CSS и JS. Внешних библиотек и внешних запросов нет.
- Картинки с выражениями лиц персонажей (`assets/img/chars/`) и обложки (`assets/img/`) — общие файлы четырёх страниц. Если перенести один только HTML, вместо картинок будут видны пиксельные персонажи, поэтому переносите папку `assets/` целиком.
- Если картинок обложек нет, показывается запасная обложка, на которой стоят четыре персонажа.
- Браузерное хранилище (localStorage и т. п.) не используется.
- В «Пакете онтологии и библиографии» в конце каждой страницы можно скачать ZIP с графом знаний (JSON-LD, Turtle, CSV) и списком литературы (CSL-JSON, BibTeX, RIS).

## Порядок работы над обложками

1. Вставьте 5 блоков из `docs/COVER_PROMPTS_square.md` в Genspark и создайте картинки 1280×1280 (референсы: 4 базовых изображения персонажей).
2. Переименуйте файлы в `cover_00.png` ~ `cover_04.png` и упакуйте в ZIP.
3. Преобразуйте полученные картинки в WebP, поместите в `assets/img/` и замените место обложки на каждой странице (между метками `<!-- lab-cover -->`) и миниатюры в оглавлении.

## Использование на занятиях

- На первом экране каждой страницы есть три строки учебных целей и ожидаемое время (страница 1 — около 25 минут, страница 2 — 20, страница 3 — 20, страница 4 — 25).
- В `docs/TEACHER_GUIDE.md` есть структура занятий на 2 встречи, типичные заблуждения и слова для их исправления, примеры заданий и оценивания.
- Контрольные викторины: 12 вопросов на странице 1, 10 на странице 2, 8 на странице 3, 8 на странице 4; результаты не сохраняются.

## Что учесть при чтении

- Из характеристик на страницах 3 и 4 ATK·HIT — экспертные оценки, а SPD·EN·MEM — градации, выставленные по способу вычислений. Классы питания, HP босса и формула урона — правила для пояснения, а не измеренные значения.
- Модель мозга по коннектому дрозофилы не создана для решения задач, поэтому из рейтинга битвы исключена.
- Таблица «Если перевести градации в практические масштабы» на странице 3 и «Отбор кандидатов по условиям на месте» на странице 4 — примерные данные. Для реального выбора оборудования нужны измерения.

## Основные источники

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. и др. (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. и др. (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. и др. (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- Статьи с предложением каждой модели есть в пакете литературы на каждой странице.

## Цитирование

> Ан Сансон (Ahn Sangsun) (2026). Атлас нейросетей · Битва роботов-дрозофил. (добавьте название и номер страницы)

## Лицензия

(заполнить) — определите и впишите лицензию на текст, код и изображения персонажей.
Источник изображений персонажей: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

Этот репозиторий не связан с цитируемыми исследованиями и их авторами, HHMI Janelia, Google, Cambridge и Mojang/Microsoft.

---

<a id="vi"></a>

# Bách khoa cấu trúc mạng nơ-ron · Đại chiến robot ruồi giấm

Đây là bài giải thích bốn trang: sắp xếp 42 cấu trúc mạng nơ-ron thành bách khoa, rồi so sánh thông số và hiệu năng của từng cấu trúc khi lần lượt lắp vào bộ não của robot nhỏ cỡ con ruồi giấm bằng trận đối đầu kiểu RPG.
Bốn nhân vật Tiến sĩ, Trợ lý, Nhà nghiên cứu Ruồi giấm và Money-Robo dẫn dắt.

- Tác giả: Ahn Sangsun (Giám đốc điều hành M-Robo)
- Xem trực tuyến: `https://adminmrobo.github.io/neural-network-atlas/` (hãy sửa cho khớp với tên kho)
- Trang bắt đầu: [`index.html`](index.vi.html)

## Ngôn ngữ

Loạt bài này có thể xem bằng bản gốc tiếng Hàn và 6 bản ngoại ngữ.

- Cách chọn: chọn ở hộp chọn ngôn ngữ 🌐 trên thanh menu trên cùng của màn hình hoặc ở biểu ngữ 🌐 phía dưới bên phải. Ngôn ngữ đã chọn được trình duyệt ghi nhớ.
- Tự động chuyển: khi lần đầu vào trang tiếng Hàn, nếu ngôn ngữ trình duyệt là ngôn ngữ được hỗ trợ thì sẽ chuyển sang bản ngôn ngữ đó. Nếu vào bằng địa chỉ bản dịch thì mở nguyên như vậy.
- Thêm `?lang=en` vào cuối địa chỉ thì mở thẳng bằng ngôn ngữ đó.
- Tệp bản ngôn ngữ có dạng `tên.mã-ngôn-ngữ.html`.

<!-- i18n:langtable -->
| Ngôn ngữ | Tên tệp | Xem ngay |
|---|---|---|
| 한국어 | `index.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.html) |
| English | `index.en.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.en.html) |
| 中文 | `index.zh.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.zh.html) |
| 日本語 | `index.ja.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.ja.html) |
| Oʻzbekcha | `index.uz.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.uz.html) |
| Русский | `index.ru.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.ru.html) |
| Tiếng Việt | `index.vi.html` | [Xem ngay](https://adminmrobo.github.io/neural-network-atlas/index.vi.html) |
<!-- /i18n:langtable -->

## Cấu thành

| Trang | Tệp | Tiêu đề | Nội dung |
|---|---|---|---|
| Mục lục | [`index.html`](index.vi.html) | Bách khoa cấu trúc mạng nơ-ron · Đại chiến robot ruồi giấm | Hướng dẫn bốn trang, thứ tự đọc, các nguồn chính |
| 1 | [`1_neural_network_atlas_chart.html`](1_neural_network_atlas_chart.vi.html) | Bách khoa cấu trúc mạng nơ-ron ① 27 cấu trúc của biểu đồ gốc | Vẽ lại 27 cấu trúc của biểu đồ cấu trúc mạng nơ-ron gốc thành sáu nhóm, và sắp xếp một cách điềm đạm xem chúng làm gì cùng điểm mạnh·điểm yếu. |
| 2 | [`2_neural_network_atlas_after.html`](2_neural_network_atlas_after.vi.html) | Bách khoa cấu trúc mạng nơ-ron ② 15 cấu trúc ra đời sau đó | Giới thiệu 15 cấu trúc ra đời sau biểu đồ như Transformer, mô hình khuếch tán, Mamba, mạng nơ-ron đồ thị cùng mô hình làm từ sơ đồ đi dây não ruồi giấm. |
| 3 | [`3_fruitfly_robot_rules.html`](3_fruitfly_robot_rules.vi.html) | Đại chiến robot ruồi giấm ① Quy tắc cấy ghép và bảng thông số | Công bố quy tắc đặt 42 cấu trúc lên cùng một cái cân. Bảng thông số, bảng quy tắc, tính từng bước, hạng nguồn điện, phòng thí nghiệm chỉ số. |
| 4 | [`4_fruitfly_robot_match.html`](4_fruitfly_robot_match.vi.html) | Đại chiến robot ruồi giấm ② Trận đấu mạng nơ-ron kiểu RPG | Chọn mạng nơ-ron trong nhà chứa máy, lắp vào robot ruồi giấm rồi xem cảnh tuyệt chiêu. Bậc thang hạng nguồn, đối đầu, bảng thành tích 42 mô hình. |

Trang 1·2 là giải thích cấu trúc (không có điểm số·chiến đấu), trang 3·4 là quy tắc so sánh và đại chiến. Có thể đi lại bằng thanh di chuyển ở trên cùng mỗi trang.
Ở nhà chứa máy trang 4, thêm `#m-ModelID` vào cuối địa chỉ thì mô hình đó mở ngay. Ví dụ: `4_fruitfly_robot_match.html#m-lstm`

## Cách xem

- Trực tuyến: truy cập bằng địa chỉ GitHub Pages.
- Trên máy của bạn: tải kho về rồi nhấp đúp `index.html`. Không cần máy chủ hay cài đặt.

## Cấu trúc thư mục

```
index.html                         목차
1_neural_network_atlas_chart.html  1쪽 · 신경망 구조 도감 ①
2_neural_network_atlas_after.html  2쪽 · 신경망 구조 도감 ②
3_fruitfly_robot_rules.html        3쪽 · 초파리 로봇 대전 ①
4_fruitfly_robot_match.html        4쪽 · 초파리 로봇 대전 ②
assets/img/                        표지 그림 (cover_00~04.webp, 받은 뒤 채움)
assets/img/chars/                  캐릭터 표정 그림 (네 쪽이 함께 씀)
docs/COVER_PROMPTS_square.md       정사각 표지 5장의 Genspark 지시문
docs/TEACHER_GUIDE.md              강의자 가이드 (2회차 구성, 오개념, 과제 예시)
docs/IMG_01_neural_network_atlas.md  이미지 제작 명세서
docs/KG_00_registry.json           지식 그래프 ID 등록부
.nojekyll                          GitHub Pages가 파일을 그대로 쓰게 함
```

## Thiết lập GitHub Pages

1. Tải các tệp của thư mục này lên ngay đầu kho (gốc).
2. Trong **Settings → Pages** của kho, chọn **Source: Deploy from a branch**, nhánh `main`, thư mục `/ (root)` rồi lưu.
3. Sau vài phút, trang sẽ mở tại `https://<계정>.github.io/<저장소>/`. Sửa địa chỉ ở đầu README này thành địa chỉ thực tế.

## Ghi chú kỹ thuật

- Mỗi trang chứa toàn bộ CSS·JS trong một tệp HTML. Không có thư viện ngoài và yêu cầu ra ngoài.
- Hình biểu cảm nhân vật (`assets/img/chars/`) và hình bìa (`assets/img/`) là tệp dùng chung của cả bốn trang. Nếu chỉ chuyển riêng HTML thì sẽ thấy nhân vật pixel thay cho hình, nên hãy chuyển nguyên cả thư mục `assets/`.
- Nếu không có hình bìa thì sẽ thấy bìa thay thế có bốn nhân vật đứng.
- Không dùng bộ nhớ của trình duyệt (localStorage, v.v.).
- Ở "Gói bản thể học · thư mục" cuối mỗi trang, bạn có thể tải đồ thị tri thức (JSON-LD, Turtle, CSV) và tài liệu tham khảo (CSL-JSON, BibTeX, RIS) dưới dạng ZIP.

## Thứ tự làm hình bìa

1. Dán 5 khối của `docs/COVER_PROMPTS_square.md` vào Genspark để tạo hình 1280×1280 (hình tham khảo: 4 hình cơ bản của nhân vật).
2. Đổi tên tệp thành `cover_00.png` ~ `cover_04.png` rồi nén thành ZIP.
3. Đổi hình nhận được sang WebP rồi đặt vào `assets/img/`, thay phần chỗ bìa của mỗi trang (giữa các dấu `<!-- lab-cover -->`) và hình thu nhỏ ở mục lục.

## Dùng trong giờ học

- Màn hình đầu của mỗi trang có ba dòng mục tiêu học tập và thời gian dự kiến (trang 1 khoảng 25 phút, trang 2 20 phút, trang 3 20 phút, trang 4 25 phút).
- `docs/TEACHER_GUIDE.md` có cấu trúc buổi học lần 2, các hiểu lầm và lời đính chính, ví dụ bài tập·đánh giá.
- Câu hỏi quiz xác nhận gồm trang 1: 12, trang 2: 10, trang 3: 8, trang 4: 8 câu, và điểm không được lưu.

## Lưu ý khi đọc

- Trong các chỉ số ở trang 3·4, ATK·HIT là giá trị đánh giá, còn SPD·EN·MEM là hạng chấm theo cách tính toán. Hạng nguồn điện, HP trùm và công thức tính sát thương là quy tắc minh họa, không phải giá trị đo thực.
- Mô hình não theo connectome ruồi giấm không phải mô hình được làm để giải nhiệm vụ nên đã bị loại khỏi thứ hạng đại chiến.
- Bảng 'Chuyển các hạng sang cảm nhận thực tế' ở trang 3 và 'Lọc ứng viên theo điều kiện hiện trường' ở trang 4 là dữ liệu ví dụ. Việc chọn thiết bị thật cần đo thực tế.

## Nguồn chính

- Leijnen, S. & van Veen, F. (2020). The Neural Network Zoo. *Proceedings*, 47(1), 9. https://doi.org/10.3390/proceedings2020047009
- Berg, S. et al. (2026). Sexual dimorphism in the complete connectome of the Drosophila male central nervous system. *Cell*.
- Shiu, P. K. et al. (2024). A Drosophila computational brain model reveals sensorimotor processing. *Nature*, 634, 210–219. https://doi.org/10.1038/s41586-024-07763-9
- Lappalainen, J. K. et al. (2024). Connectome-constrained networks predict neural activity across the fly visual system. *Nature*, 634, 1132–1140.
- Các bài báo đề xuất của từng mô hình nằm trong gói tài liệu tham khảo của mỗi trang.

## Trích dẫn

> Ahn Sangsun (2026). Bách khoa cấu trúc mạng nơ-ron · Đại chiến robot ruồi giấm. (thêm tiêu đề và số trang của từng trang)

## Giấy phép

(cần điền) — hãy chọn và ghi giấy phép cho nội dung, mã và hình nhân vật.
Nguồn hình nhân vật: `adminmrobo/fruitfly-lab-expressions` (commit ea5da3f).

Kho lưu trữ này không liên quan đến các nghiên cứu được trích dẫn và tác giả của chúng, HHMI Janelia, Google, Cambridge hay Mojang/Microsoft.
