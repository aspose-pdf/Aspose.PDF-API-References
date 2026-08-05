---
title: "FontRepository"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "글꼴 검색을 수행합니다. 시스템에 설치된 글꼴 및 표준 PDF 글꼴을 검색합니다.<br/>             또한 사용자 정의 글꼴을 열 수 있는 기능을 제공합니다."
type: docs
weight: 130
url: /ko/python-net/aspose.pdf.text/fontrepository/
---

## FontRepository class

글꼴 검색을 수행합니다. 시스템에 설치된 글꼴 및 표준 PDF 글꼴을 검색합니다.<br/>             또한 사용자 정의 글꼴을 열 수 있는 기능을 제공합니다.

FontRepository 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| FontRepository() | FontRepository 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| substitutions | 폰트 대체 전략 컬렉션을 가져옵니다. |
| sources | 폰트 소스 컬렉션을 가져옵니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| find_font(font_name) | 지정된 폰트 이름으로 폰트를 검색하고 반환합니다. |
| find_font(font_name, ignore_case) | 대소문자 구분을 무시하거나 존중하여 지정된 폰트 이름으로 폰트를 검색하고 반환합니다. |
| find_font(font_family_name, stl) | 지정된 폰트 이름과 폰트 스타일로 폰트를 검색하고 반환합니다. |
| find_font(font_family_name, stl, ignore_case) | 지정된 폰트 이름과 폰트 스타일로 폰트를 검색하고 반환합니다 <br/>             대소문자 구분을 무시하거나 존중합니다. |
| open_font(font_stream, font_type) | 지정된 폰트 스트림으로 폰트를 엽니다. |
| open_font(font_file_path) | 지정된 폰트 파일 경로로 폰트를 엽니다. |
| open_font(font_file_path, metrics_file_path) | 지정된 폰트 파일 경로로 폰트를 엽니다. |
| load_fonts() | 시스템에 설치된 폰트와 표준 Pdf 폰트를 로드합니다. 이 메서드는 폰트 로드 프로세스를 가속화하도록 설계되었습니다.<br/>            기본적으로 폰트는 어떤 폰트에 대한 첫 번째 요청 시 로드됩니다. 이 메서드를 사용하면 시스템 및 표준 Pdf 폰트를<br/>            PDF 문서를 열기 전에 즉시 로드합니다. |
| reload_fonts() | 속성 [sources](/pdf/python-net/aspose.pdf.text/fontrepository/)에 지정된 모든 폰트를 다시 로드합니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

