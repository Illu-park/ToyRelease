# ToyRelease

가볍게 만들어 쓰는 Windows 데스크톱 도구 모음의 배포 저장소다. 소스는 공개하지 않고 실행 파일만 [Releases](../../releases)로 배포한다.

| 도구 | 설명 | 최신 버전 |
| --- | --- | --- |
| **MD Viewer** | 마크다운 뷰어. 위키링크, 옵시디언 임베드, YAML 프런트매터, Mermaid, PDF 열기를 지원한다. | [1.3.0](../../releases/tag/md-viewer-v1.3.0) |
| **CalWidget** | 바탕화면 월간 달력 위젯. 공휴일과 음력을 외부 API 없이 표시한다. | [1.0.0](../../releases/tag/cal-widget-v1.0.0) |

## 설치

1. [Releases](../../releases)에서 원하는 도구의 zip을 받는다.
2. 압축을 풀고 exe를 실행한다. 설치 과정은 없다.

## 요구 사항

- Windows 10 이상 (x64)
- .NET 런타임은 exe에 포함되어 있어 따로 설치하지 않아도 된다.
- MD Viewer는 [WebView2 런타임](https://developer.microsoft.com/microsoft-edge/webview2/)이 필요하다. Windows 11과 최신 Windows 10에는 보통 이미 설치되어 있다.

## 참고

- 서명되지 않은 exe라서 처음 실행할 때 Windows SmartScreen 경고가 뜰 수 있다. 직접 만든 도구이므로 `추가 정보 > 실행`으로 진행하면 된다.
- 사용 조건은 [LICENSE.md](LICENSE.md), 포함된 오픈소스는 [THIRD-PARTY-NOTICES.md](THIRD-PARTY-NOTICES.md)를 참고한다.
- 버그나 제안은 [Issues](../../issues)에 남겨 달라.
