---
title: "EpubLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "EPUB 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 포함합니다."
type: docs
weight: 310
url: /ko/python-net/aspose.pdf/epubloadoptions/
---

## EpubLoadOptions class

EPUB 파일을 PDF 문서로 로드/임포트하기 위한 옵션을 포함합니다.

EpubLoadOptions 타입은 다음 멤버들을 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| EpubLoadOptions() | EPUB 파일을 PDF 문서로 변환하기 위한 기본 로드 옵션을 생성합니다. <br/>            기본 PDF 페이지 크기 - A4 300dpi 2480 X 3508. |
| EpubLoadOptions(page_size) | EpubLoadOptions 클래스의 새 인스턴스를 초기화합니다 |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 모든 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환하면 로드 작업이 중단되어야 합니다. |
| load_format | 파일 형식을 나타내며, [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)에서 설명합니다. |
| page_size | 가져오기에 대한 출력 페이지 크기를 가져오거나 설정합니다. |
| margin | 여백 정보를 나타내는 객체에 대한 참조를 가져옵니다. |
| margins_area_usage_mode | 여백 영역 사용 모드를 나타냅니다 - 가져온 문서의 CSS 지시문(있는 경우)<br/>              의 처리를 정의합니다<br/>              여백 사용과 관련된. |
| page_size_adjustment_mode | 주의! 이 기능은 구현되었지만 샘플 문서에서 <br/>              OSHARED 레이어의 차단 이슈가 발견되어 아직 공개 API에 포함되지 않았습니다.<br/>              <br/>             <br/>              변환 중 페이지 크기 사용 모드를 나타냅니다.<br/>             HTML, EPUB 등과 같은 포맷은 일반적으로 유동적인 디자인을 가지고 있어 필요한<br/>             페이지 크기에 맞출 수 있습니다. 그러나 때때로 콘텐츠에 지정된 가로 위치나 크기가 있어<br/>             요구되는 페이지 크기에 맞추기 어렵습니다.<br/>               이러한 경우(예: 콘텐츠 크기가 결과 PDF 문서의 초기 페이지 크기에 맞지 않을 때) 어떤 작업을 수행할지 정의할 수 있습니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

