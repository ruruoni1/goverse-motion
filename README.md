# GOVERSE Motion — 무료 모션 자막 제작기

SRT 자막이나 LRC 가사를 불러와 브라우저에서 움직이는 자막 영상을 만들고 MP4로 저장하는 무료 도구입니다. SRT의 시작·종료 시각과 자막 사이의 공백을 유지합니다.

**[웹사이트에서 바로 사용하기](https://ruruoni1.github.io/goverse-motion/)** · [자세한 한국어 사용법](README.ko.md)

## 사용 방법

1. 웹사이트를 열고 **SRT/LRC 불러오기**에서 자막 파일을 선택합니다. 가사를 직접 입력해도 됩니다.
2. 필요하면 음원을 불러오거나 **탭으로 동기화**하여 각 줄의 시작 시각을 맞춥니다.
3. **자동으로 만들기**를 눌러 움직임과 디자인을 만들고, 미리보기에서 확인합니다.
4. 화면비와 화질을 선택해 MP4로 내보냅니다.

프로젝트는 JSON 파일로 저장하고 다시 열 수 있습니다. 자막과 음원은 브라우저 안에서 처리됩니다. 자세한 기능과 SRT·LRC 형식의 차이는 [한국어 사용법](README.ko.md)에 정리했습니다.

## 직접 빌드하기

저장소 루트에서 다음 명령을 실행합니다.

```sh
python build.py
```

한국어 웹사이트용 `index.html`과 `sitemap.xml`이 생성됩니다. 웹사이트는 GitHub Pages에서 저장소 루트의 `index.html`을 제공합니다.

## 기반 프로젝트와 저작권

GOVERSE Motion은 [JIZURA](https://github.com/852wa/JIZURA)를 바탕으로 만든 포크입니다. 원본의 모션 그래픽 엔진을 유지하면서 한국어 화면과 SRT 자막 작업 흐름을 더했습니다. 원본 프로젝트의 기여자와 라이선스는 [원본 저장소](https://github.com/852wa/JIZURA), [LICENSE](LICENSE), [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md)에서 확인할 수 있습니다.

동영상에 사용한 자막·가사·음원의 권리는 각각의 권리자에게 있습니다.
