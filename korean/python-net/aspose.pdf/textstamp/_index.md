---
title: "TextStamp"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "텍스트 스탬프를 나타냅니다."
type: docs
weight: 1550
url: /ko/python-net/aspose.pdf/textstamp/
---

## TextStamp class

텍스트 스탬프를 나타냅니다.

TextStamp 유형은 다음 멤버를 노출합니다:
## 생성자
| 이름 | 설명 |
| :- | :- |
| TextStamp(value) | TextStamp 클래스의 새 인스턴스를 초기화합니다. |
| TextStamp(value, text_state) | TextStamp 클래스의 새 인스턴스를 초기화합니다. |
| TextStamp(formatted_text) | TextStamp 클래스의 새 인스턴스를 초기화합니다. |
## 속성
| 이름 | 설명 |
| :- | :- |
| background | 콘텐츠가 배경으로 스탬프되는지를 나타내는 bool 값을 설정하거나 가져옵니다.<br/>            값이 true이면 스탬프 콘텐츠가 하단에 배치됩니다.<br/>            기본값은 false이며, 스탬프 콘텐츠가 상단에 배치됩니다. |
| opacity | 스탬프 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이입니다.<br/>            기본값은 1.0입니다. |
| outline_opacity | 스탬프 외곽선 불투명도를 나타내는 값을 가져오거나 설정합니다. 값은 0.0에서 1.0 사이입니다.<br/>            기본값은 1.0입니다. |
| outline_width | 스탬프 외곽선 너비 값을 가져오거나 설정합니다.<br/>            기본값은 1.0입니다. |
| rotate | 스탬프 콘텐츠의 회전을 [Rotation](/pdf/python-net/aspose.pdf/rotation/) 값에 따라 설정하거나 가져옵니다.<br/>            참고: 이 속성은 90도 배수(0, 90, 180, 270도)의 각도를 설정하기 위한 것입니다.<br/>            임의 각도를 설정하려면 RotateAngle 속성을 사용하십시오. <br/>            ArbitraryAngle 로 설정된 각도가 90도의 배수가 아니면 Rotate 속성은 Rotation.None을 반환합니다. |
| x_indent | 왼쪽부터 시작하는 수평 스탬프 좌표. |
| y_indent | 아래쪽부터 시작하는 수직 스탬프 좌표. |
| horizontal_alignment | 페이지에서 스탬프의 수평 정렬을 가져오거나 설정합니다. |
| vertical_alignment | 페이지에서 스탬프의 수직 정렬을 가져오거나 설정합니다. |
| left_margin | 스탬프의 왼쪽 여백을 가져오거나 설정합니다. |
| right_margin | 스탬프의 오른쪽 여백을 가져오거나 설정합니다. |
| bottom_margin | 스탬프의 아래쪽 여백을 가져오거나 설정합니다. |
| top_margin | 스탬프의 위쪽 여백을 가져오거나 설정합니다. |
| zoom_x | 스탬프의 수평 확대 비율입니다. 스탬프를 수평으로 확대할 수 있습니다. |
| width | 페이지에서 스탬프의 원하는 너비입니다. |
| 높이 | 페이지에서 스탬프의 원하는 높이입니다. |
| zoom_y | 스탬프의 수직 확대 비율입니다. 스탬프를 수직으로 확대할 수 있습니다. |
| zoom | 스탬프의 확대 비율입니다. 스탬프를 확대할 수 있습니다.<br/>            ZoomX와 ZoomY 속성 쌍을 사용하면 각 축에 대해 별도로 확대 비율을 설정할 수 있다는 점에 유의하십시오. <br/>            이 속성을 설정하면 ZoomX와 ZoomY 두 속성이 모두 변경됩니다. <br/>            ZoomX와 ZoomY가 다르면 Zoom 속성은 ZoomX 값을 반환합니다. |
| rotate_angle | 스탬프의 회전 각도를 도 단위로 가져오거나 설정합니다.<br/>            이 속성을 사용하면 임의의 회전 각도를 설정할 수 있습니다. |
| draw | 이 속성은 페이지에 스탬프가 어떻게 그려지는지를 결정합니다. Draw = true이면 스탬프가 그래픽 연산자로 그려지고, draw = false이면 텍스트로 그려집니다. |
| treat_y_indent_as_base_line | 텍스트 배치를 위한 좌표 원점을 정의합니다.<br/>            If TreatYIndentAsBaseLine = true (default when Draw = true) YIndent 값은 텍스트 기준선으로 처리됩니다.<br/>            If TreatYIndentAsBaseLine = false (default when Draw = false) YIndent 값은 텍스트의 바닥(내림선)으로 처리됩니다. |
| word_wrap | 단어 줄바꿈을 정의합니다. 이 속성을 true로 설정하고 Width 값을 지정하면, 텍스트가 지정된 너비에 맞게 여러 줄로 나뉩니다. 기본값: false. |
| justify | 텍스트 정렬을 정의합니다. 이 속성을 true로 설정하면 텍스트의 왼쪽과 오른쪽 가장자리가 모두 맞춰집니다. 기본값: false. |
| scale | 텍스트의 스케일링을 정의합니다. 이 속성이 true로 설정되고 Width 값이 지정되면, 텍스트가 지정된 너비에 맞도록 스케일링됩니다. |
| 값 | 페이지에 스탬프로 사용되는 문자열 값을 가져오거나 설정합니다. |
| text_state | 스탬프의 텍스트 속성을 가져옵니다. 자세한 내용은 [text_state](/pdf/python-net/aspose.pdf/textstamp/)를 참조하십시오. |
| text_alignment | 스탬프 내부 텍스트의 정렬. |
| max_row_width | WordWrap 옵션에 대한 최대 행 높이. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| put(page) | 페이지에 텍스트 스탬프를 추가합니다. |
| set_stamp_id(value) | 스탬프 ID를 설정합니다. |
| get_stamp_id() | 스탬프 ID를 반환합니다. |

### 또 보기

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

