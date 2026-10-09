# 슈퍼 모모타로 전철 DX 한글 패치 사이트

8비트 레트로풍의 한글 패치 배포 페이지입니다. 도트 글꼴, 게임 메뉴 형태의 테두리, 픽셀 그림자와 카드 배치를 사용합니다. 제목과 타이틀 화면, 다운로드와 첫 공개 안내, 게임 소개와 적용 방법을 정리했습니다.

## 현재 상태

- 사이트 소스는 `site/` 폴더에 있습니다.
- GitHub Pages 활성화 및 자동 배포 설정은 하지 않았습니다.
- v0.95 다운로드 버튼은 `site/downloads/Super_Momotarou_Dentetsu_DX_Korean_v0.95.xdelta`에 직접 연결됩니다. ZIP은 제공하지 않습니다.
- 원본 ROM, 한글화 ROM, 저장 파일, 내부 검수 자료는 포함하지 않습니다.
- 제작자 이름은 **볼티지**입니다.
- 현재 디자인은 `site/retro-cards.css`를 사용합니다. 이전 디자인 파일은 페이지에서 로드하지 않습니다.
- 데스크톱과 390px 모바일의 메뉴 이동, FAQ 펼침, 이미지 로드와 가로 넘침을 확인했습니다.

## 로컬 미리보기

```sh
python -m http.server 4174 --bind 127.0.0.1 --directory site
```

브라우저에서 `http://127.0.0.1:4174/`을 엽니다.

제작자 이름, 안내 문구, 배포 버전은 `site/index.html`에서 변경할 수 있습니다. 디자인은 `site/retro-cards.css`에 있습니다. 공개 전까지 `noindex,nofollow` 설정을 유지합니다.

## 글꼴

[Galmuri](https://github.com/quiple/galmuri)의 Galmuri11 글꼴을 사용합니다. SIL Open Font License 1.1 원문은 `site/assets/Galmuri-OFL.md`에 포함되어 있습니다.

게임 화면은 개발 중 촬영한 스크린샷이며 최종 배포본의 화면을 보장하지 않습니다. 원작의 권리는 각 권리자에게 있습니다.
