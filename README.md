# 두뷰 (DoView)

<p align="center">
  <img src="icon.png" alt="DoView Icon" width="128">
</p>

<p align="center">
  <strong>무료 로컬 이미지·문서 뷰어</strong><br>
  웹툰, 만화, 사진, 전자책과 텍스트를 한곳에서 읽으세요.
</p>

<p align="center">
  <a href="#download-ko"><strong>다운로드</strong></a> ·
  <a href="#english">English</a> ·
  <a href="https://github.com/DoView1/DoView-release/issues">문의·오류 제보</a>
</p>

이 저장소는 DoView의 **공식 배포와 사용자 안내**를 제공합니다. 아래 설명은 현재 GitHub 공개 버전인 **1.3.4**를 기준으로 합니다.

<a id="download-ko"></a>

## 📦 다운로드

| 운영체제 | 버전 | 다운로드 |
| --- | --- | --- |
| Windows x64 | 1.3.4 | [설치형 EXE](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-Setup-1.3.4.exe) · [포터블 ZIP](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView.v1.3.4.zip) |
| Linux x64 | 1.3.4 | [AppImage](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-1.3.4-linux-x86_64.AppImage) · [DEB](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-1.3.4-linux-amd64.deb) · [tar.gz](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-1.3.4-linux-x64.tar.gz) |

[최신 릴리스](https://github.com/DoView1/DoView-release/releases/latest) · [1.3.4 변경 사항](https://github.com/DoView1/DoView-release/releases/tag/v1.3.4) · [SHA-256 체크섬](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/SHA256SUMS.txt)

일반 열람에는 계정이나 AI 엔진이 필요하지 않습니다. 선택형 로컬 AI는 **Windows x64에서만** 제공합니다. 현재 이 저장소에는 macOS용 공개 배포 파일이 없습니다.

Windows 배포 파일은 현재 미서명입니다. 게시자 확인 또는 SmartScreen 경고와 파일 확인 방법은 [Windows 실행 안내](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/WINDOWS-UNSIGNED.ko.md)를 참고해 주세요.

### 설치와 업데이트

- **Windows 설치형:** EXE로 설치합니다. 파일 연결을 지원하며, 앱 설정에서 업데이트를 다운로드한 뒤 재시작하면 설치된 앱을 갱신합니다.
- **Windows 포터블:** ZIP 전체를 압축 해제하고 `DoView.exe`를 실행합니다. 설정과 읽기 기록은 실행 파일 옆의 `Data` 폴더에 저장됩니다. 1.3.2 이상에서는 앱 내 업데이트를 지원합니다. 수동으로 새 버전을 덮어쓸 때는 앱을 종료하고 **기존 `Data` 폴더를 보존**해 주세요. 1.3.1 이하 포터블에서 처음 업데이트할 때도 이 방법을 사용합니다.
- **Linux:** AppImage는 실행 권한을 부여한 뒤 실행하며 앱 내 업데이트를 지원합니다. DEB는 배포판의 패키지 설치 도구로 설치하고, tar.gz는 압축 해제 후 실행합니다. DEB·tar.gz는 새 파일로 수동 갱신하며 기존 사용자 설정과 읽기 기록을 유지해 주세요.

## ✨ 주요 기능

- **다양한 읽기 방식:** 페이지·이어서 스크롤·격자 보기, 한 쪽·두 쪽 보기, 좌→우·우→좌 읽기, 자동 스크롤과 전체 화면을 지원합니다. 새 설정의 기본 맞춤은 **화면 전체 맞춤**이며 기존에 저장한 설정은 유지합니다.
- **문서와 전자책:** PDF, EPUB, DOCX, 텍스트를 열고 검색합니다. PDF는 문서 보기와 텍스트 보기, EPUB는 원본 보기와 읽기 보기를 제공합니다. 텍스트 읽기에서는 글꼴·글자 크기·줄 간격·본문 너비·배경을 조절할 수 있습니다.
- **라이브러리와 이어 읽기:** 최근 항목, 북마크, 즐겨찾기와 읽던 위치를 관리합니다. 여러 문서를 탭으로 열고 다시 읽던 곳으로 돌아갈 수 있습니다.
- **메모와 주석:** 읽는 내용에 메모·강조·그림을 남기고, 글과 그림을 함께 담은 `.doview` 작업 파일을 저장하거나 다시 엽니다.
- **이미지 도구:** 밝기·대비·채도·선명도 조정, 회전·확대/축소, EXIF/IPTC 메타데이터 보기를 지원합니다.
- **음성 읽기:** 텍스트를 음성으로 읽습니다. 사용 가능한 음성과 언어는 운영체제와 설치된 음성에 따라 달라집니다.
- **화면과 언어:** V2·Classic 디자인, 화이트·다크·아이보리·블랙 테마와 단축키 변경을 지원합니다. V2가 기본 디자인입니다.

### 지원 파일

| 종류 | 형식 |
| --- | --- |
| 이미지 | JPG/JPEG, PNG, GIF, WebP, BMP, AVIF, HEIC/HEIF, JXL, SVG, ICO/CUR, TIFF/TIF, APNG, PJPEG/PJP, DIB |
| 압축 파일 | ZIP/CBZ, 7Z/CB7, RAR/CBR, TAR/CBT, GZ, XZ, BZ2 |
| 문서·전자책 | PDF, EPUB, DOCX |
| 텍스트 | TXT, MD/Markdown, LOG, JSON/JSONL/NDJSON, CSV/TSV, YAML, TOML, INI, XML 등 |
| DoView 작업 | `.doview` |

압축 파일은 직접 열어 내부의 지원 콘텐츠를 읽을 수 있습니다. CSV·JSON 같은 파일은 텍스트로 표시합니다. 문서의 구성·사용 글꼴·보호 방식에 따라 원본 프로그램과 표시가 다를 수 있습니다.

**UI 언어 11개:** 한국어, 영어, 일본어, 중국어 간체, 독일어, 스페인어, 프랑스어, 이탈리아어, 러시아어, 태국어, 아랍어. 아랍어 문구는 제공하지만 화면 전체의 오른쪽→왼쪽 배치는 아직 완전히 적용되지 않았습니다.

## 🤖 선택형 로컬 AI — Windows x64

**설정 → AI 서비스**에서 로컬 E4B Q4 엔진을 다운로드하거나 호환되는 기존 엔진을 연결합니다. API 키나 별도 Python 설치는 필요하지 않습니다.

- **이미지 번역:** 이미지 속 영어·일본어를 OCR로 읽어 번역합니다. UI 언어 지원과 이미지 원문 인식 언어는 서로 다릅니다.
- **텍스트 AI:** 텍스트 번역, 요약, 문서 내용에 관한 질문을 지원합니다.
- **설치 용량:** 엔진 다운로드 약 **11.30 GB**, 새 설치에 필요한 여유 공간 약 **11.57 GB**입니다. 저장된 번역과 캐시를 위한 추가 공간도 확보해 주세요. 다운로드는 취소하거나 앱을 다시 시작한 뒤 이어받을 수 있습니다.
- **처리 방식:** 설치 후 AI 처리는 이 컴퓨터에서 수행합니다. 실행 가능 여부와 속도는 RAM·GPU·드라이버 등에 따라 달라지며, 번역·인식·요약 결과는 틀릴 수 있습니다.

기본 파일 열람에는 AI 엔진을 설치하지 않아도 됩니다. 앱·엔진 업데이트 확인과 다운로드에는 인터넷을 사용합니다.

[AI 구성요소 이용 조건](https://github.com/DoView1/DoView-ai-engine/blob/main/TERMS.md) · [OCR 대응 소스](https://github.com/DoView1/DoView-ai-engine/blob/main/SOURCES.md)

## ⌨️ 기본 단축키

Windows·Linux 공개판의 기본값입니다. 앱의 **단축키 설정**에서 변경할 수 있으며, `H`로 현재 보기의 도움말을 확인할 수 있습니다. 텍스트 입력 중에는 일부 단축키가 동작하지 않습니다.

| 단축키 | 기능 |
| --- | --- |
| `Ctrl+O` / `Ctrl+Shift+O` | 파일 / 폴더 열기 |
| `Ctrl+Tab` | 사이드바 열기·닫기 |
| `L` | 라이브러리 열기·닫기 |
| `B` | 현재 문서 북마크 켜기·끄기 |
| `Space` / `Shift+Space` | 앞으로 / 뒤로 읽기 이동 — 보기 방식에 따라 스크롤 또는 페이지 전환 |
| `A` | 자동 스크롤 켜기·끄기 |
| `←` / `→` | 자동 스크롤 속도 낮추기 / 높이기 |
| `I` | 정보 패널 열기·닫기 |
| `D` | 밝은 테마 / 어두운 테마 전환 |
| `F11` | 전체 화면 전환 |
| `H` | 단축키 도움말 |
| `Esc` | 전체 화면·젠 모드에서 나오기 또는 열린 보조 패널 닫기 |

같은 키도 현재 콘텐츠에 따라 다르게 동작합니다.

| 단축키 | 이미지 보기 | 텍스트 읽기 |
| --- | --- | --- |
| `T` | 이미지 번역 패널 | 텍스트 AI 도구 |
| `F` | 이미지 필터 | 텍스트 설정 |
| `V` | 보기 방식 전환 | 본문 너비 전환 |
| `R` | 이미지 회전 | 글꼴 전환 |
| `+` / `-` / `0` | 확대 / 축소 / 초기화 | 글자 크기 조절 / 초기화 |
| `Ctrl+F` | — | 문서 내 텍스트 검색 |
| `M` | — | 음성 읽기 패널 |

PDF·DOCX·EPUB의 문서/원본 보기에서는 일부 동작이 다릅니다. 예를 들어 EPUB 원본 보기의 `R`은 표시 방식을 바꾸고, 문서 보기의 `+`·`-`는 배율을 조절합니다. 전체 목록과 적용 범위는 앱의 도움말을 기준으로 확인해 주세요.

## 💬 문의·개인정보·후원

오류나 기능 제안은 [GitHub Issues](https://github.com/DoView1/DoView-release/issues)에 남겨 주세요. 사용 버전, 운영체제, 파일 형식과 재현 순서를 적어 주시면 확인에 도움이 됩니다. 공개 이슈에는 개인 문서나 민감한 정보를 올리지 마세요.

[개인정보 처리방침](PRIVACY.md) · 개인정보 문의: [yym0760@gmail.com](mailto:yym0760@gmail.com)

두뷰가 도움이 되셨다면 [후원](https://ctee.kr/place/doview) 또는 [Buy Me a Coffee](https://buymeacoffee.com/doview)로 응원해 주세요.

## 📄 라이선스

**DoView License**에 따라 무료 사용과 원본 그대로의 재배포를 허용합니다(상업적 이용 포함). 수정·역분석 등 제한을 포함한 전체 조건은 배포본의 `LICENSE-DoView.txt`를 확인해 주세요.

함께 배포되는 타사 구성요소에는 각각의 라이선스가 적용됩니다. 고지와 조건은 `NOTICE.txt`, `THIRD_PARTY_LICENSES.txt`, `LICENSE.electron.txt`, `LICENSES.chromium.html`에서 확인할 수 있습니다. 선택형 AI 구성요소의 조건은 위 AI 안내를 참고해 주세요.

---

<a id="english"></a>

## English

**DoView is a free local image and document viewer** for webtoons, manga, photos, ebooks and text. This repository provides official downloads and user information. This guide covers the current public GitHub release, **1.3.4**.

### 📦 Download

| Platform | Version | Downloads |
| --- | --- | --- |
| Windows x64 | 1.3.4 | [Installer EXE](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-Setup-1.3.4.exe) · [Portable ZIP](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView.v1.3.4.zip) |
| Linux x64 | 1.3.4 | [AppImage](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-1.3.4-linux-x86_64.AppImage) · [DEB](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-1.3.4-linux-amd64.deb) · [tar.gz](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/DoView-1.3.4-linux-x64.tar.gz) |

[Latest release](https://github.com/DoView1/DoView-release/releases/latest) · [1.3.4 release notes](https://github.com/DoView1/DoView-release/releases/tag/v1.3.4) · [SHA-256 checksums](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/SHA256SUMS.txt)

Ordinary viewing requires no account or AI engine. The optional local AI engine is available on **Windows x64 only**. This repository currently has no public macOS download.

Windows builds are currently unsigned, so Windows may display publisher or SmartScreen warnings. See the [Windows launch guide (Korean)](https://github.com/DoView1/DoView-release/releases/download/v1.3.4/WINDOWS-UNSIGNED.ko.md) and checksums when checking a download.

### Installation and updates

- **Windows installer:** Install with the EXE. File associations and in-app updates are supported. Download an update in Settings, then restart to update the installed app.
- **Windows portable:** Extract the entire ZIP and run `DoView.exe`. Settings and reading records are stored in the adjacent `Data` folder. Versions 1.3.2 and later support in-app updates. For a manual update, close DoView, replace the application files and **preserve the existing `Data` folder**. Use this method for the first update from portable version 1.3.1 or earlier.
- **Linux:** Make the AppImage executable before launching it; AppImage supports in-app updates. Install DEB with your distribution's package tool, or extract tar.gz before running. Update DEB and tar.gz manually, keeping your existing user settings and reading records.

### ✨ Features

- **Flexible reading:** Page, continuous-scroll and grid views; single-page and two-page layouts; left-to-right and right-to-left reading; auto-scroll and fullscreen. New settings default to **Fit entire image**; saved preferences are preserved.
- **Documents and ebooks:** Open and search PDF, EPUB, DOCX and text. PDF offers document and text views; EPUB offers original publication and reader views. Adjust fonts, size, line spacing, width and backgrounds in the text reader.
- **Library and reading progress:** Manage recent items, bookmarks, favorites and reading positions. Open multiple documents in tabs and return to where you left off.
- **Notes and annotations:** Add notes, highlights and drawings, and save or reopen `.doview` work files containing text and drawings.
- **Image tools:** Adjust brightness, contrast, saturation and sharpness; rotate and zoom; inspect EXIF/IPTC metadata.
- **Read aloud:** Listen to text with available system voices. Voice and language availability depend on your OS and installed voices.
- **Appearance and controls:** Choose V2 or Classic design, White, Dark, Ivory or Black themes, and customize keyboard shortcuts. V2 is the default design.

### Supported files

| Type | Formats |
| --- | --- |
| Images | JPG/JPEG, PNG, GIF, WebP, BMP, AVIF, HEIC/HEIF, JXL, SVG, ICO/CUR, TIFF/TIF, APNG, PJPEG/PJP, DIB |
| Archives | ZIP/CBZ, 7Z/CB7, RAR/CBR, TAR/CBT, GZ, XZ, BZ2 |
| Documents and ebooks | PDF, EPUB, DOCX |
| Text | TXT, MD/Markdown, LOG, JSON/JSONL/NDJSON, CSV/TSV, YAML, TOML, INI, XML and more |
| DoView work files | `.doview` |

Open archives directly to read supported content inside. Files such as CSV and JSON are displayed as text. Document structure, fonts and protection can affect rendering compared with the original application.

**11 interface languages:** Korean, English, Japanese, Simplified Chinese, German, Spanish, French, Italian, Russian, Thai and Arabic. Arabic strings are available, but full right-to-left UI layout is not yet implemented.

### 🤖 Optional local AI — Windows x64

Download the local E4B Q4 engine or connect a compatible existing engine in **Settings → AI Services**. No API key or separate Python installation is required.

- **Image translation:** OCR recognizes English and Japanese text in images for translation. Interface languages and OCR source languages are separate capabilities.
- **Text AI:** Translate or summarize text and ask questions about document content.
- **Storage:** Approximately **11.30 GB** to download and **11.57 GB** of free space for a new installation. Leave additional room for saved translations and caches. Downloads can resume after cancellation or an app restart.
- **Processing:** AI runs on your computer after installation. Availability and speed depend on RAM, GPU, drivers and other system resources. Recognition, translations and summaries can be inaccurate.

Ordinary viewing works without the AI engine. App and engine update checks and downloads use the internet.

[AI component terms](https://github.com/DoView1/DoView-ai-engine/blob/main/TERMS.md) · [Corresponding OCR source](https://github.com/DoView1/DoView-ai-engine/blob/main/SOURCES.md)

### ⌨️ Default shortcuts

These are the defaults for the public Windows and Linux builds. Customize them in the app's shortcut settings, or press `H` for help with the current view. Some shortcuts are inactive while typing in a text field.

| Key | Action |
| --- | --- |
| `Ctrl+O` / `Ctrl+Shift+O` | Open file / folder |
| `Ctrl+Tab` | Toggle sidebar |
| `L` | Toggle library |
| `B` | Toggle the current document's bookmark |
| `Space` / `Shift+Space` | Move forward / backward by scrolling or changing pages, depending on the view |
| `A` | Toggle auto-scroll |
| `←` / `→` | Decrease / increase auto-scroll speed |
| `I` | Toggle information panel |
| `D` | Switch between light and dark theme families |
| `F11` | Toggle fullscreen |
| `H` | Shortcut help |
| `Esc` | Leave fullscreen or Zen mode, or close an open auxiliary panel |

Some keys change their behavior with the current content.

| Key | Image view | Text reader |
| --- | --- | --- |
| `T` | Image translation panel | Text AI tools |
| `F` | Image filters | Text settings |
| `V` | Cycle view mode | Cycle text width |
| `R` | Rotate image | Cycle font |
| `+` / `-` / `0` | Zoom in / out / reset | Increase / decrease / reset font size |
| `Ctrl+F` | — | Search document text |
| `M` | — | Read-aloud panel |

Some actions differ in PDF, DOCX and EPUB document/publication views. For example, `R` changes the display mode in EPUB publication view, and `+`/`-` adjust zoom in document views. Check the in-app help for the full list and applicable views.

### 💬 Support, privacy and donations

Report bugs or suggest features through [GitHub Issues](https://github.com/DoView1/DoView-release/issues). Include your app version, OS, file type and steps to reproduce the problem. Do not post private documents or sensitive information in public issues.

[Privacy Policy](PRIVACY.md) · Privacy contact: [yym0760@gmail.com](mailto:yym0760@gmail.com)

If DoView helps you, support it through [Donations](https://ctee.kr/place/doview) or [Buy Me a Coffee](https://buymeacoffee.com/doview).

### 📄 License

The **DoView License** permits free use and redistribution of the original, unmodified software, including commercial use. See `LICENSE-DoView.txt` in the distribution for the full terms, including restrictions on modification and reverse engineering.

Bundled third-party components retain their own licenses. See `NOTICE.txt`, `THIRD_PARTY_LICENSES.txt`, `LICENSE.electron.txt` and `LICENSES.chromium.html`. Terms for the optional AI components are linked in the AI section above.
