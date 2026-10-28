---
title: "XslFoLoadOptions"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "XSL-FO 파일을 pdf 문서에 로드/임포트하기 위한 옵션을 나타냅니다."
type: docs
weight: 1820
url: /ko/python-net/aspose.pdf/xslfoloadoptions/
---

## XslFoLoadOptions class

XSL-FO 파일을 pdf 문서에 로드/임포트하기 위한 옵션을 나타냅니다.

XslFoLoadOptions 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| XslFoLoadOptions() | XSL 데이터 없이 [XslFoLoadOptions](/pdf/python-net/aspose.pdf/xslfoloadoptions/) 객체를 생성합니다. |
| XslFoLoadOptions(xsl_file) | XslFoLoadOptions 클래스의 새 인스턴스를 초기화합니다. |
| XslFoLoadOptions(xsl_stream) | XslFoLoadOptions 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| warning_handler | 생성된 모든 경고를 처리하기 위한 콜백입니다. <br/>            WarningHandler는 Continue 또는 Abort 중 하나를 지정하는 ReturnAction 열거형 항목을 반환합니다. <br/>            Continue는 기본 동작이며 로드 작업이 계속되지만, 사용자가 Abort를 반환하면 로드 작업이 중단되어야 합니다. |
| load_format | 파일 형식을 나타내며, [LoadOptions](/pdf/python-net/aspose.pdf/loadoptions/)에서 설명합니다. |
| xsl_stream | xml을 pdf 문서로 변환하기 위한 xsl 데이터를 가져옵니다. |
| base_path | 로드된 SVG 파일에서 참조된 외부 리소스(있는 경우)의 상대 경로를 검색하는 기본 경로/URL입니다. |
| parsing_errors_handling_type | 소스 XSLFO 문서에 서식 오류가 포함될 수 있습니다. 이 열거형은 해당 오류를 처리하는 가능한 전략을 나열합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

