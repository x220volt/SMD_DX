# 슈퍼 모모타로 전철 DX 한글 패치 사이트

8비트 도트 스타일의 비공식 한글 패치 배포 사이트 초안입니다.

## 현재 상태

- 사이트 소스는 `site/` 폴더에 있습니다.
- GitHub Pages 활성화 및 자동 배포 설정은 하지 않았습니다.
- 패치 다운로드는 준비 중으로 표시됩니다.
- 원본 ROM, 한글화 ROM, 패치 파일, 저장 파일, 내부 검수 자료는 포함하지 않습니다.
- 제작자 이름은 **볼티지**입니다.

## 로컬 미리보기

```sh
python -m http.server 4173 --bind 127.0.0.1 --directory site
```

브라우저에서 `http://127.0.0.1:4173/`을 엽니다.

제작자 이름, 안내 문구, 배포 버전은 `site/index.html`에서 변경할 수 있습니다. 디자인은 `site/pixel.css`에 있습니다. 공개 전까지 `noindex,nofollow` 설정을 유지합니다.

## 글꼴

[Galmuri](https://github.com/quiple/galmuri)의 Galmuri11 글꼴을 사용합니다. SIL Open Font License 1.1 원문은 `site/assets/Galmuri-OFL.md`에 포함되어 있습니다.

게임 화면은 개발 중 촬영한 스크린샷이며 최종 배포본의 화면을 보장하지 않습니다. 원작의 권리는 각 권리자에게 있습니다.
