---
title: "TextFragmentAbsorber"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "텍스트 조각의 흡수 객체를 나타냅니다.<br/>            텍스트 검색을 수행하고 [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 컬렉션을 통해 검색 결과에 접근할 수 있습니다."
type: docs
weight: 400
url: /ko/python-net/aspose.pdf.text/textfragmentabsorber/
---

## TextFragmentAbsorber class

텍스트 조각의 흡수 객체를 나타냅니다.<br/>            텍스트 검색을 수행하고 [text_fragments](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 컬렉션을 통해 검색 결과에 접근할 수 있습니다.

TextFragmentAbsorber 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| TextFragmentAbsorber() | 문서 또는 페이지의 모든 텍스트 세그먼트를 검색하는 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)의 새 인스턴스를 초기화합니다. |
| TextFragmentAbsorber(text_edit_options) | TextFragmentAbsorber 클래스의 새 인스턴스를 초기화합니다. |
| TextFragmentAbsorber(phrase) | TextFragmentAbsorber 클래스의 새 인스턴스를 초기화합니다. |
| TextFragmentAbsorber(phrase, text_search_options) | TextFragmentAbsorber 클래스의 새 인스턴스를 초기화합니다. |
| TextFragmentAbsorber(phrase, text_search_options, text_edit_options) | TextFragmentAbsorber 클래스의 새 인스턴스를 초기화합니다. |
| TextFragmentAbsorber(phrase, text_edit_options) | TextFragmentAbsorber 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| text | [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/)가 PDF 문서 또는 페이지에서 추출한 텍스트를 가져옵니다. |
| has_errors | 값은 텍스트 추출 중 오류가 발견되었는지 여부를 나타냅니다.<br/>            오류 검색은 TextSearchOptions.LogTextExtractionErrors = true인 경우에만 수행되며, 성능이 저하될 수 있습니다. |
| errors | 텍스트 추출 중 발견된 오류에 대한 정보를 포함하는 [TextExtractionError](/pdf/python-net/aspose.pdf.text/textextractionerror/) 객체 목록입니다.<br/>            오류 검색은 TextSearchOptions.LogTextExtractionErrors = true인 경우에만 수행되며, 성능이 저하될 수 있습니다. |
| extraction_options | 텍스트 추출 옵션을 가져오거나 설정합니다. |
| text_search_options | 검색 옵션을 가져오거나 설정합니다. 이 옵션은 정규식을 사용한 검색을 가능하게 합니다. |
| text_fragments | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체로 표시되는 검색 발생 컬렉션을 가져옵니다. |
| phrase | [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/)가 PDF 문서 또는 페이지에서 검색하는 구문을 가져오거나 설정합니다. |
| text_edit_options | 텍스트 편집 옵션을 가져오거나 설정합니다. 이 옵션은 요청된 기호를 해당 폰트로 쓸 수 없을 때의 특수 동작을 정의합니다. |
| text_replace_options | 텍스트 교체 옵션을 가져오거나 설정합니다. 이 옵션은 조각 텍스트가 더 짧거나 길게 교체될 때의 동작을 정의합니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| visit(page) | 지정된 페이지에서 검색을 수행합니다. |
| visit(pdf) | 지정된 문서에서 검색을 수행합니다. |
| visit(x_form) | 지정된 양식 개체에서 검색을 수행합니다. |
| apply_for_all_fragments(font) | 흡수된 모든 텍스트 조각에 대해 글꼴을 적용합니다. 페이지(들)의 모든 조각이 흡수된 경우 조각을 반복하는 것보다 더 빠르게 작동합니다. 그렇지 않은 경우 반복과 유사하게 작동합니다. |
| apply_for_all_fragments(font_size) | 흡수된 모든 텍스트 조각에 대해 글꼴 크기를 적용합니다. 페이지(들)의 모든 조각이 흡수된 경우 조각을 반복하는 것보다 더 빠르게 작동합니다. 그렇지 않은 경우 반복과 유사하게 작동합니다. |
| apply_for_all_fragments(font, font_size) | 흡수된 모든 텍스트 조각에 대해 글꼴과 크기를 적용합니다. 페이지(들)의 모든 조각이 흡수된 경우 조각을 반복하는 것보다 더 빠르게 작동합니다. 그렇지 않은 경우 반복과 유사하게 작동합니다. |
| remove_all_text(page) | 지정된 페이지에서 모든 텍스트를 제거합니다. |
| remove_all_text(page, rect) | 지정된 페이지의 지정된 사각형 내부 텍스트를 제거합니다. |
| remove_all_text(document) | 문서에서 모든 텍스트를 제거합니다. |
| reset() | 이 [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) 객체의 TextFragments 컬렉션을 지웁니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

