# 제작 이력

기록 기준일: 2026-09-09. 아래 순서는 이 대화에서 성공적으로 반환된 이미지와 사용자의 디자인 피드백을 기준으로 합니다.

## 기본형

| 단계 | 작업 | 결과 |
|---|---|---|
| 1 | 씨앗 피움, 세미콜론 세미, 연결 캐릭터 이음 제안 | [초기 3종](../assets/process/01_initial_three_concepts.png) |
| 2 | 이음 제외, 피움·세미 발전, SSAFY 이름표 추가 | [이름표 시안](../assets/process/02_name_badges.png) |
| 3 | 이름표 제거, 이름을 피움으로 복원, 노트북·키보드에 로고 응용 | [소품 추가](../assets/process/03_laptop_keyboard_original.png) |
| 4 | 소품을 작게 줄이고 모서리를 둥글게 수정 | [작은 소품](../assets/process/04_smaller_accessories.png) |
| 5 | 노트북의 회색·외형 복원, 키보드 로고 확대 요청 | [색·로고 수정](../assets/process/05_color_logo_revision.png) |
| 6 | 노트북 옆면·모서리 보완, 자판 열 제거 재요청 | [외형 보완](../assets/process/06_laptop_edge_revision.png) |
| 7 | 키보드 자판을 4개씩 2줄과 스페이스바로 단순화, 로고 공간 확보 | [현재 기본형](../assets/basic.png) |

5·6단계에서는 요청한 자판 열 제거가 충분히 반영되지 않아 재수정했습니다. 최종 단계에서는 아래쪽 자판도 정리되어 로고 오른쪽 영역을 넓게 확보한 구성이 되었습니다.

최종 기준은 **피움의 작은 회색 노트북**, **세미의 작은 키보드와 확대된 SSAFY 로고**, **명찰 없는 몸**, **피움·세미라는 이름**입니다.

## 응용형

사용자가 제안한 ‘팔을 벌리고 활짝 웃기’, ‘뒤쪽 불꽃과 함께 열정적으로 코딩하기’에 ‘문제를 해결한 유레카!’를 더해 두 캐릭터 각각 3종을 제작했습니다.

- [피움 응용형 1차](../assets/pium-actions-v1.png)
- [세미 응용형 1차](../assets/semi-actions-v1.png)

응용형은 현재 1차 시안이며, 제출용 개별 이미지로 확정·분리한 상태는 아닙니다.

## 참고 자료와 검증

- [사용자 제공 SSAFY 의류 로고](../assets/process/user_supplied_ssafy_logo.png): 소품의 로고 형태·색·테두리 참고.
- 원본 생성 파일은 그대로 보존하고, 이 저장소에는 별도 복사본을 담았습니다.
- [이미지 목록과 SHA-256](../assets/manifest.json): 저장소 이미지의 크기와 파일 동일성 확인용 기록.
- 프롬프트는 생성 결과가 반환된 기본형 7단계와 응용형 2회 호출의 실제 원문을 보관했습니다.

[기본형 프롬프트](../prompts/basic-generation.md) · [응용형 프롬프트](../prompts/application-generation.md) · [저장소 첫 화면](../README.md)
