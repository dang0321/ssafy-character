# 피움 · 세미 — 실제 이미지 생성·수정 프롬프트 기록

정리일: 2026-09-09  
사용 도구: ChatGPT(Codex) 내장 `image_gen` / `image_gen__imagegen`  
방식: 텍스트 기반 초기 생성 후, 기존 시안과 사용자 제공 로고 이미지를 참조하는 반복 편집.

아래 영문 블록은 이 대화에서 **이미지 도구에 실제 전달한 프롬프트 원문**입니다. 사용자의 한국어 아이디어와 수정 요청을 어시스턴트가 도구 입력용으로 구성했습니다. 단계 소개와 파일 대응표는 기록을 위해 추가한 설명입니다. 결과가 반환되지 않은 초기 개별 3종 요청은 포함하지 않았습니다. 5·6단계는 요청 일부가 충분히 반영되지 않아 추가 수정한 중간 결과입니다.

## 1. 초기 세 캐릭터 비교 시안 생성

- 입력 이미지: 없음.
- 출력: `로컬 보관: 01_initial_three_concepts.png`
- 피움·세미·이음을 한 장에 생성한 단계. 이후 이음은 제외했습니다.

```text
Create one landscape comparison concept sheet showing THREE DISTINCT original adorable minimalist mascot proposals for Korean SSAFY software and AI academy. Flat 2D illustration, crisp thick uniform navy outlines, solid pastel sky-blue and cream fills, white background, abundant space, no gradients, no 3D, no shadows, no detail clutter, no clothes, no logos. Three equally sized columns with ONE large full-body character in each, aligned baseline, very simple tiny dot eyes and small smile, short limbs, sophisticated cute sticker style suitable for young adult students. Small clean Korean names below respective characters, only text '피움', '세미', '이음'. LEFT 피움: plump warm cream seed creature, head/body integrated pear-like shape, tiny blue feet and tiny hands, a pair of blue sprout leaves on top subtly shaped like rounded < and > angle brackets, curious head tilt and raised little hand. CENTER 세미: living semicolon ; creature formed of TWO separated major shapes: small cream circular head floating just above a larger sky-blue comma body, visible narrow white gap between them. Face on circular head only. Comma body tapers to a short curled lower-right tip, small hands and tiny feet. Cheerfully proud. It must read as semicolon rather than a bird. RIGHT 이음: one horizontally broad sky-blue oval pebble creature with face integrated in body, two tiny feet, distinctive short curved C-shaped arms with cream rounded ends opened welcomingly on both sides. These soft hook-shaped hands can link with friends. No ears, antennae, sprout or tail on this one. Every mascot must have a distinctly different easily recognized silhouette while all three share the exact same illustration style and consistent stroke weight. Keep each design simple enough to doodle from memory. Show just the three mascots and their names, no diagrams, no annotation text, no extras.
```

## 2. 두 캐릭터로 축소하고 명찰 추가

- 입력 이미지 1: `로컬 보관: 01_initial_three_concepts.png`
- 출력: `로컬 보관: 02_name_badges.png`
- 이 단계의 ‘싸피움’ 이름과 몸의 명찰은 이후 사용자 피드백으로 변경·제거했습니다.

```text
Edit the supplied mascot comparison image into a polished SECOND-ROUND comparison sheet with exactly TWO revised mascots. The original image is the design identity reference and edit target. Keep the original appealing soft simple 2D illustration style, navy thick smooth outline, cream and sky blue palette, tiny dot eyes, small smiles, organic rounded shapes, short limbs, clean white background. Preserve the identity of the LEFT seed character and CENTER semicolon character. Remove the right oval mascot entirely. Recompose into two equal spacious columns, left seed and right semicolon, each with one large full-body main character aligned to the same ground level. No extra characters or small studies. Refine rather than reinvent. LEFT: rename the original 피움 to '싸피움' in clear Korean text beneath it. Retain its unified plump cream seed/pear silhouette, blue feet and small blue hands, tilted friendly face. Keep exactly two blue sprout leaves resembling rounded < and > coding brackets on thin navy stems, but make the pair about 15 percent smaller overall than the reference, and intentionally one leaf slightly smaller than the other to symbolize different learners growing together. Add ONE small rounded rectangular sky-blue academy name badge below its face on its upper torso, with clean highly legible dark navy uppercase text exactly 'SSAFY'. Badge should be subtle, about a quarter of torso width, no lanyard, no clothing or extra emblems. One hand raised in a warm curious greeting. RIGHT: keep name '세미' beneath it in clear Korean text. Retain the recognizable two-part semicolon silhouette: cream circular floating head above blue comma-shaped body with curled tip and two tiny feet. Narrow the head-body gap to a fine visible strip of white, making the character feel more unified; don't connect head and body and don't lose the semicolon reading. Make head gently tilted and curious, retain its sweet simple face and raised small hands. Add matching small rounded rectangular cream name badge on the upper part of the blue comma torso, dark navy uppercase text exactly 'SSAFY'. The two badges use the same graphic language. Keep all proportions close to reference; no robot visor, no circuits, no mechanical parts, no hat or clothing, no extra leaves on 세미. Overall result should show two friendly SSAFY academy mascot candidates with a clear visible academy identity and very minimal details. Only text is the two names '싸피움' and '세미' under the characters and 'SSAFY' on each badge. Do not add titles, slogans or descriptive paragraphs. Use flat solid fills, no texture and no complex shading.
```

## 3. 명찰 제거, 피움으로 이름 복원, 노트북·키보드 추가

- 입력 이미지 1 — 편집 대상: `로컬 보관: 02_name_badges.png`
- 입력 이미지 2 — 로고 참고: `로컬 보관: user_supplied_ssafy_logo.png`
- 출력: `로컬 보관: 03_laptop_keyboard_original.png`
- 사용자가 제공한 의류 부착 로고의 글자·색·테두리를 소품에 응용했습니다.

```text
Edit image 1, the two-mascot concept sheet. Image 2 is ONLY the reference for the SSAFY lettering/logo to place on new handheld accessories. Produce one clean landscape comparison sheet of the same two characters on a white background. Preserve their original identity, body proportions, face, tiny feet, leaf shapes, cream and blue colors, smooth thick navy outline and cute minimal 2D aesthetic. Keep their entire bodies visible with ample white space in two equal columns. REQUIRED EDITS: Completely REMOVE both rectangular chest badges and all lettering on their bodies; restore uninterrupted cream seed body on the left and uninterrupted blue comma body on the right. Change the left Korean caption from 싸피움 to exactly '피움'; right caption remains exactly '세미'. LEFT 피움: give it a small slim closed laptop held naturally in ONE hand at its outer side, leaning diagonally with the broad lid facing the viewer. Show a subtle hinge and double edge so it reads as a closed laptop rather than a book or sign. One little blue mitten hand wraps visibly around the laptop's lower side edge to support it; other hand can keep greeting. Laptop light cool gray/cream shell, navy outline, no keyboard visible because closed. On the center of the visible laptop lid place the SSAFY logo modeled on image 2: lively rounded irregular sky-blue uppercase 'SSAFY' lettering, thin white inner edging and thick near-black outline with slight offset black backing. Use the reference letter forms especially the wavy two S shapes. Omit the decorative radiating dashes around the logo for simplicity. Keep logo small enough to feel like a laptop sticker. RIGHT 세미: give it a small compact computer KEYBOARD held in ONE hand at its outer side, slightly diagonal with the key face clearly toward the viewer. A slim wide cream rounded keyboard with a few neat rows of simple rounded square keycaps outlined in navy, and a recognizable long spacebar. It must be recognizably a keyboard, not another laptop or tablet. Place a small 'SSAFY' wordmark in the style of image 2 on a reserved patch at ONE SIDE of the key face, integrated beside the keys on the right portion, not as a large center label covering all the keys. Blue lettering, dark outline, simplify as necessary for readability. Semis one cream mitten hand visibly grips a short edge of the keyboard; its other hand remains raised empty. Props roughly half the width of each character body, held next to their bodies, not huge, not covering faces or silhouettes. Reposition arms minimally as required for plausible one-handed grips. Keep each character with EXACTLY TWO hands and TWO feet. No chest logo, no chest badge, no clothes, no neck lanyard, no extra accessories, no decorative background. Preserve the semicolon's distinct head and comma body and the seed's pair of coding-bracket sprouts. Only text: '피움' and '세미' below figures and reference-style 'SSAFY' on the laptop and on one side of the keyboard. Main goal: these look like friendly learners carrying personal tools, with understated SSAFY connection through accessory branding.
```

## 4. 소품 크기 축소와 둥근 외형 조정

- 입력 이미지: `로컬 보관: 03_laptop_keyboard_original.png`
- 출력: `로컬 보관: 04_smaller_accessories.png`
- 프롬프트의 ‘75 percent’는 요청한 목표 비율이며, 결과를 정밀 측정한 수치는 아닙니다.

```text
Make a precise local revision to this two-mascot concept sheet. The user likes both mascots and asks ONLY to make the held laptop and keyboard smaller and softer, less rigid. Preserve the character designs, expressions, body silhouettes, leaves, semicolon anatomy, colors, face locations, feet, free raised hands, white background, two-column layout, Korean labels '피움' and '세미' EXACTLY. Keep the bodies plain with NO name badge or torso text. Change only the two accessories and minimally adjust their holding hands for proper grip. Scale BOTH laptop and keyboard to approximately 75 percent of their current linear dimensions (clearly smaller, but still readable); maintain each accessory at the corresponding outer side of its character, naturally held in ONE hand. Restore any body areas uncovered by the smaller props cleanly. Laptop: a cute compact CLOSED laptop, broad rear lid toward viewer, warm pale cream/gray fill, strongly rounded corners, gently bowed organic edges, a tiny soft double-rim and hinge detail so it still reads as laptop. Rounded like a charming illustrated toy, not metallic hardware or a stiff book, but NOT an inflated pillow or bag. Keep it slim. Preserve the lively sky-blue black-and-white outlined 'SSAFY' sticker on its lid. Keyboard: compact soft capsule-rounded rectangle, gently curved edges and corners, fewer simplified pillowy rounded-square keycaps, readable rows and one long rounded spacebar. No sharp rectangular corners or rigid perfect grid look. Still unambiguously a keyboard, not a game controller, cushion or phone. Preserve a small lively blue 'SSAFY' wordmark on the upper-right side of its key face beside the keys. Match original logo style. Use the same smooth navy outlines and soft minimal flat 2D illustration style as the characters, restrained cream and light blue. Accessories must complement the mascots without dominating them, and must not cover faces. No new accessories, no extra fingers or hands, no new text. Return the entire revised comparison image.
```

## 5. 노트북 외형·색 복원 및 키보드 로고 확대

- 입력 이미지 1 — 작은 소품 크기의 편집 대상: `로컬 보관: 04_smaller_accessories.png`
- 입력 이미지 2 — 노트북 외형·색 참고: `로컬 보관: 03_laptop_keyboard_original.png`
- 출력: `로컬 보관: 05_color_logo_revision.png`
- 결과에서 자판 한 열 제거가 충분히 반영되지 않아 후속 편집을 진행했습니다.

```text
Precise accessory-only edit of IMAGE 1. Image 1 is the current approved SMALL accessory size and the EDIT TARGET. IMAGE 2 is an older version supplied ONLY as a reference for the laptop's original exterior geometry and neutral light gray color; do NOT revert to its larger accessory sizes. Return the full landscape two-character sheet. PRESERVE from image 1 both mascot designs and all their colors exactly, background, layout, expressions, sprouts, semicolon anatomy, body outlines, hands, feet, Korean captions '피움' and '세미', and current small overall accessory dimensions and locations. Change only these specific details: (1) PIUM LAPTOP: Keep the SMALL laptop dimensions from image 1, but restore the original laptop exterior from image 2, scaled down to fit the current size. Use the reference's straighter lid edges, modest small-radius corners, slightly trapezoidal perspective, and the distinct offset second slab visible along the right side and lower edge, with the same thin gray sidewall and navy separation line suggesting the closed laptop's lid and base. A compact closed laptop with real lid/base thickness, NOT a tablet/iPad with a single rounded screen border, NOT a soft padded square, NOT a screen-facing tablet. Restore the lid fill to the ORIGINAL neutral very pale cool gray/silver from image 2; remove image 1's warm beige tint from the laptop only. Preserve the centered blue-white-black SSAFY sticker and its size/style. Do not enlarge the laptop or change the character's cream body color. (2) SEMI KEYBOARD: Keep keyboard SMALL size, exterior silhouette, angle, cream fill, spacebar and held position exactly from image 1. Remove ONE VERTICAL COLUMN of ordinary small square keycaps directly to the LEFT of the existing SSAFY logo, across the normal key rows in that adjacent column. Use this freed area to enlarge the existing SSAFY logo about 35 percent linearly, extending LEFTWARD into the removed-key space; keep the full logo inside the keyboard face, fully readable and clear of Semi's holding hand. Maintain remaining keys and spacebar in their original positions rather than shrinking keys or making more keys. Result should have visibly one fewer key column immediately beside logo and noticeably larger logo. Preserve the original playful blue uppercase SSAFY lettering with white edging and thick dark border, accurate spelling S S A F Y. No logo elsewhere, no added badges or props. This is a narrow localized revision, not a redraw or redesign.
```

## 6. 노트북 모서리 보완 및 자판 개수 재지정

- 입력 이미지 1 — 편집 대상: `로컬 보관: 05_color_logo_revision.png`
- 입력 이미지 2 — 노트북 참고: `로컬 보관: 03_laptop_keyboard_original.png`
- 출력: `로컬 보관: 06_laptop_edge_revision.png`
- 이 결과에서도 자판이 5열로 남아 최종 단계에서 키보드 내부 구성을 다시 지정했습니다.

```text
Apply TWO surgical corrections to IMAGE 1 while keeping everything else identical. Image 2 is ONLY a reference for laptop corner shape. 1. Keyboard key count: currently image 1 has FIVE small square keys in its top row left of the big SSAFY logo and FIVE keys in the middle row. DELETE THE RIGHTMOST KEY in EACH of these TWO rows. The final keyboard must visibly contain exactly FOUR square keys in its top row and exactly FOUR square keys in its middle row. Do not squeeze, redistribute, replace or add any keys. Preserve those remaining four keys at the same size and positions. Leave the erased area clean cream as breathing room alongside the ALREADY ENLARGED SSAFY logo. Keep the bottom spacebar row and holding hand unchanged. Preserve logo's current large size and style. 2. Laptop: retain CURRENT SMALL size and current cool light silver-gray fill. Make its lid a straight-edged four-corner quadrilateral with small corner radii closely matching image 2's laptop, NOT image 1's inflated rounded rectangular tablet-like shape. Restore the distinct blue-gray offset base slab visible on right edge, a compact closed clamshell laptop. Make the outer top-left and lower-right corners less rounded than image 1. Don't enlarge it. Preserve sticker, hands and hold position. Everything else fully unchanged: both characters, face, colors, sprouts, body shape, keyboard body dimensions, layout, background and Korean labels. Return full image.
```

## 7. 최종 키보드 자판 단순화와 로고 공간 확보

- 입력 이미지: `로컬 보관: 06_laptop_edge_revision.png`
- 출력: **`../assets/basic.png`**
- 최종 결과: 키보드 왼쪽에 4개씩 2줄의 작은 자판과 스페이스바, 오른쪽에 확대된 SSAFY 로고.

```text
Edit ONLY the small keyboard held by the right blue semicolon mascot. Keep the rest of the entire picture exactly identical, including left mascot with gray small closed laptop, right mascot, hands, lettering underneath, sizes, colors and background. Replace the keyboard FACE LAYOUT with this simpler layout, preserving its case outline, size and diagonal angle: LEFT HALF has two rows of FOUR rounded square keycaps each (8 small keycaps total in those two rows), with one long spacebar below. RIGHT HALF is an open cream branding zone carrying the large existing blue/black SSAFY logo. Clear out the keys currently nearest the logo so the logo has substantial clean breathing room and takes up the right half above the holding hand. There MUST NOT be five small keys per row: draw only FOUR per row. Keep the few bottom corner keys if needed. Keep key size similar to current, leave visibly EMPTY SPACE between keys and logo rather than filling the space with new keys. Large readable 'SSAFY' logo should extend left into the cleared space. This requested simplification is the primary change and must be clearly visible. Do not return the unchanged five-column key layout. No other changes. Full two-character comparison image.
```

## 로컬 참조 이미지와 원래 생성 파일 대응

| 파일 또는 로컬 보관 자료 | 원래 생성 파일명 |
|---|---|
| `로컬 보관: 01_initial_three_concepts.png` | `exec-61914243-81da-457a-8dc9-65fa6b2547ae.png` |
| `로컬 보관: 02_name_badges.png` | `exec-fb2e1c3e-1a32-4ce9-bb5a-46e05ce6ff89.png` |
| `로컬 보관: 03_laptop_keyboard_original.png` | `exec-9ddd3449-25ea-4266-b845-7df43cf0ddeb.png` |
| `로컬 보관: 04_smaller_accessories.png` | `exec-8d938176-d650-47de-aaeb-44d5958c2742.png` |
| `로컬 보관: 05_color_logo_revision.png` | `exec-e52e72ed-452b-453f-8eee-1d5c615a1567.png` |
| `로컬 보관: 06_laptop_edge_revision.png` | `exec-774a8a89-9339-4e30-a8fb-0055e5f8f016.png` |
| `../assets/basic.png` | `exec-0068366d-2fec-49c6-bb3d-1ccad328f941.png` |
| `로컬 보관: user_supplied_ssafy_logo.png` | `codex-clipboard-49132ef5-947f-48ff-9cac-249e36597516.png` |


기본형과 응용형 결과 이미지는 저장소에 포함했습니다. 기본형 중간 시안과 사용자 제공 로고 참고 원본은 로컬에 보관하며, 이 저장소에는 업로드하지 않았습니다. 위 입력 이미지 표기는 실제 제작 과정을 설명하기 위한 기록입니다.
