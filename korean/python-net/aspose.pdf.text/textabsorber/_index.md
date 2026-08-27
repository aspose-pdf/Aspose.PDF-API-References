---
title: "TextAbsorber"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "텍스트의 흡수 객체를 나타냅니다.<br/>            텍스트 추출을 수행하고 [text](/pdf/python-net/aspose.pdf.text/textabsorber/) 객체를 통해 결과에 접근할 수 있습니다."
type: docs
weight: 320
url: /ko/python-net/aspose.pdf.text/textabsorber/
---

## TextAbsorber class

텍스트의 흡수 객체를 나타냅니다.<br/>            텍스트 추출을 수행하고 [text](/pdf/python-net/aspose.pdf.text/textabsorber/) 객체를 통해 결과에 접근할 수 있습니다.

TextAbsorber 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| TextAbsorber() | 새로운 [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) 인스턴스를 초기화합니다. |
| TextAbsorber(extraction_options) | TextAbsorber 클래스를 새 인스턴스로 초기화합니다. |
| TextAbsorber(extraction_options, text_search_options) | TextAbsorber 클래스를 새 인스턴스로 초기화합니다. |
| TextAbsorber(text_search_options) | TextAbsorber 클래스를 새 인스턴스로 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| text | [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/)가 PDF 문서 또는 페이지에서 추출한 텍스트를 가져옵니다. |
| has_errors | 값은 텍스트 추출 중 오류가 발견되었는지 여부를 나타냅니다.<br/>            오류 검색은 TextSearchOptions.LogTextExtractionErrors = true인 경우에만 수행되며, 성능이 저하될 수 있습니다. |
| errors | 텍스트 추출 중 발견된 오류에 대한 정보를 포함하는 [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) 객체 목록입니다.<br/>            오류 검색은 TextSearchOptions.LogTextExtractionErrors = true인 경우에만 수행되며, 성능이 저하될 수 있습니다. |
| extraction_options | 텍스트 추출 옵션을 가져오거나 설정합니다. |
| text_search_options | 텍스트 검색 옵션을 가져오거나 설정합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| visit(page) | 지정된 페이지에서 텍스트를 추출합니다. |
| visit(form) | 지정된 XForm에서 텍스트를 추출합니다. |
| visit(pdf) | 지정된 문서에서 텍스트를 추출합니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

