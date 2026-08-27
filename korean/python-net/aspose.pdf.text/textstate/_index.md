---
title: "TextState"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "텍스트의 텍스트 상태를 나타냅니다"
type: docs
weight: 490
url: /ko/python-net/aspose.pdf.text/textstate/
---

## TextState class

텍스트의 텍스트 상태를 나타냅니다

TextState 유형은 다음 멤버를 제공합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| TextState() | 텍스트 상태 객체를 생성합니다. |
| TextState(font_size) | TextState 클래스의 새 인스턴스를 초기화합니다. |
| TextState(foreground_color) | TextState 클래스의 새 인스턴스를 초기화합니다. |
| TextState(foreground_color, font_size) | TextState 클래스의 새 인스턴스를 초기화합니다. |
| TextState(font_family) | TextState 클래스의 새 인스턴스를 초기화합니다. |
| TextState(font_family, bold, italic) | TextState 클래스의 새 인스턴스를 초기화합니다. |
| TextState(font_family, font_size) | TextState 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| character_spacing | 텍스트의 문자 간격을 가져오거나 설정합니다. |
| line_spacing | 텍스트의 줄 간격을 가져오거나 설정합니다. |
| horizontal_scaling | 텍스트의 가로 스케일을 가져오거나 설정합니다. |
| subscript | 텍스트의 아래 첨자를 가져오거나 설정합니다. |
| superscript | 텍스트의 위 첨자를 가져오거나 설정합니다. |
| word_spacing | 텍스트의 단어 간격을 가져오거나 설정합니다. |
| invisible | 텍스트의 가시성을 가져오거나 설정합니다. 이는 기본적으로 [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/) 상태를 반영하지만, 일부 특수 경우(예: 클리핑)는 제외됩니다. |
| rendering_mode | 텍스트의 렌더링 모드를 가져오거나 설정합니다. |
| font_size | 텍스트의 글꼴 크기를 가져오거나 설정합니다. |
| font | 텍스트의 글꼴을 가져오거나 설정합니다. |
| foreground_color | 텍스트의 전경색을 가져오거나 설정합니다. |
| stroking_color | 텍스트의 전경색을 가져오거나 설정합니다. |
| underline | 텍스트에 대한 밑줄을 가져오거나 설정합니다. 이는 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체로 표현됩니다. |
| strike_out | 텍스트에 대한 취소선을 설정합니다. 이는 [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) 객체로 표현됩니다. |
| background_color | 텍스트의 배경색을 설정합니다. |
| font_style | 텍스트의 글꼴 스타일을 설정합니다. |
| horizontal_alignment | 텍스트의 수평 정렬을 가져오거나 설정합니다. |
| TAB_TAG | 텍스트에 이 태그를 삽입하여 탭을 선언할 수 있습니다. |
| TABSTOP_DEFAULT_VALUE | 기본 글꼴의 공백 문자 너비에서 탭의 기본값입니다. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| apply_changes_from(text_state) | 다른 textState의 설정을 적용합니다. |
| measure_string(str) | 문자열의 길이를 측정합니다. |

### 또 보기

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

