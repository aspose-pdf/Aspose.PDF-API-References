---
title: "TextFragment"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "PDF 텍스트 조각을 나타냅니다."
type: docs
weight: 390
url: /ko/python-net/aspose.pdf.text/textfragment/
---

## TextFragment class

PDF 텍스트 조각을 나타냅니다.

TextFragment 타입은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| TextFragment() | 새로운 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체의 인스턴스를 초기화합니다. |
| TextFragment(tab_stops) | TextFragment 클래스의 새 인스턴스를 초기화합니다. |
| TextFragment(text) | TextFragment 클래스의 새 인스턴스를 초기화합니다. |
| TextFragment(text, tab_stops) | TextFragment 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| vertical_alignment | 텍스트 조각의 수직 정렬을 가져오거나 설정합니다. |
| horizontal_alignment | 텍스트 조각의 수평 정렬을 가져오거나 설정합니다. |
| margin | 단락의 외부 여백을 가져오거나 설정합니다 (PDF 생성용) |
| is_first_paragraph_in_column | 다음 열에 이 단락이 배치될지 여부를 나타내는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_kept_with_next | 현재 단락이 다음 단락과 함께 같은 페이지에 남아 있는지 여부를 나타내는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_in_new_page | 이 단락이 새 페이지에서 생성되도록 강제하는 bool 값을 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| is_in_line_paragraph | 단락이 인라인인지 여부를 가져오거나 설정합니다.<br/>            기본값은 false입니다.(PDF 생성용) |
| hyperlink | 조각의 하이퍼링크를 설정합니다. |
| z_index | 그래프의 Z-순서를 나타내는 int 값을 가져오거나 설정합니다. ZIndex가 큰 그래프는 <br/>            ZIndex가 작은 그래프 위에 배치됩니다. ZIndex는 음수일 수 있습니다. 음수 ZIndex를 가진 그래프는 <br/>            페이지의 텍스트 뒤에 배치됩니다. |
| replace_options | 텍스트 교체 옵션을 가져옵니다. 옵션은 조각 텍스트가 더 짧게/길게 교체될 때의 동작을 정의합니다. |
| text | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체가 나타내는 문자열 텍스트 객체를 가져오거나 설정합니다. |
| text_state | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체가 나타내는 텍스트의 텍스트 상태를 가져오거나 설정합니다. |
| segments | 현재 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/)에 대한 텍스트 세그먼트를 가져옵니다. |
| position | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체로 표현된 텍스트의 위치를 가져오거나 설정합니다. |
| baseline_position | [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체로 표현된 텍스트의 위치를 가져옵니다.<br/>            Position 구조체의 YIndent는 텍스트 조각의 기준선 좌표를 나타냅니다. |
| rectangle | TextFragment의 사각형을 가져옵니다. |
| page | TextFragment를 포함하는 페이지를 가져옵니다. |
| form | TextFragment를 포함하는 폼 객체를 가져옵니다. |
| wrap_lines_count | 이 단락에 대한 줄 바꿈 수를 가져오거나 설정합니다(PDF 생성 전용). |
| end_note | 단락 끝 노트를 가져오거나 설정합니다.(PDF 생성 전용) |
| foot_note | 단락 각주를 가져오거나 설정합니다.(PDF 생성 전용) |
## 메서드
| 이름 | 설명 |
| :- | :- |
| clone() | 조각을 복제합니다. |
| isolate_text_segments(start_index, length) | 지정된 부분을 나타내는 [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s)을 가져와서 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 텍스트를 반환합니다. |
| clone_with_segments() | 모든 세그먼트를 포함하여 조각을 복제합니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

