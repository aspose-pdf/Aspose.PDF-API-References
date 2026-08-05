---
title: "AttributeName"
second_title: "Aspose.PDF for Python via .NET API 참조"
description: "속성 이름 값에 대한 클래스를 나타냅니다."
type: docs
weight: 50
url: /ko/python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

속성 이름 값에 대한 클래스를 나타냅니다.

AttributeName 형식은 다음 멤버를 노출합니다:
## 속성
| 이름 | 설명 |
| :- | :- |
| 이름 | 속성의 이름 값을 가져옵니다. |
| attribute_key | 속성 키를 가져옵니다. |
| PLACEMENT_BLOCK | 속성 배치: 블록 - 둘러싸는 참조 영역 또는 상위 BLSE 내에서 블록 진행 방향으로 쌓입니다. |
| PLACEMENT_INLINE | 속성 배치: 인라인 - 둘러싸는 BLSE 내에서 인라인 진행 방향으로 압축됩니다. |
| PLACEMENT_BEFORE | 속성 배치: 이전 - 요소 할당 사각형의 앞쪽 가장자리가 가장 가까운 둘러싸는 참조 영역의 앞쪽 가장자와 일치하도록 배치됩니다. |
| PLACEMENT_START | 속성 Placement: Start - 요소의 할당 사각형 시작 가장자리가 가장 가까운 포함 참조 영역의 시작 가장자리와 일치하도록 배치됩니다. |
| PLACEMENT_END | 속성 Placement: End - 요소의 할당 사각형 끝 가장자리가 가장 가까운 포함 참조 영역의 끝 가장자리와 일치하도록 배치됩니다. |
| WRITING_MODE_LR_TB | 속성 WritingMode: LrTb - 인라인 진행 방향이 왼쪽에서 오른쪽으로, 블록 진행 방향이 위에서 아래로입니다. 이는 서구 문자 체계에 일반적인 쓰기 모드입니다. |
| WRITING_MODE_RL_TB | 속성 WritingMode: RlTb - 인라인 진행 방향이 오른쪽에서 왼쪽으로, 블록 진행 방향이 위에서 아래로입니다. 이는 아랍어와 히브리어 문자 체계에 일반적인 쓰기 모드입니다. |
| WRITING_MODE_TB_RL | 속성 WritingMode: TbRl - 인라인 진행 방향이 위에서 아래로, 블록 진행 방향이 오른쪽에서 왼쪽으로입니다. 이는 중국어와 일본어 문자 체계에 일반적인 쓰기 모드입니다. |
| BORDER_STYLE_NONE | 속성 BorderStyle: None - 테두리가 없습니다. BorderThickness의 계산된 값을 0으로 강제합니다. |
| BORDER_STYLE_HIDDEN | 속성 BorderStyle: Hidden - None과 동일하지만, 표 요소에 대한 테두리 충돌 해결 측면에서는 다릅니다. |
| BORDER_STYLE_DOTTED | 속성 BorderStyle: Dotted - 테두리가 점들의 연속입니다. |
| BORDER_STYLE_DASHED | 속성 BorderStyle: Dashed - 테두리가 짧은 선분들의 연속입니다. |
| BORDER_STYLE_SOLID | 속성 BorderStyle: Solid - 테두리가 단일 선분으로 이루어져 있습니다. |
| BORDER_STYLE_DOUBLE | 속성 BorderStyle: Double - 테두리가 두 개의 실선으로 구성됩니다. 두 선과 그 사이의 공간을 합한 값이 BorderThickness와 같습니다. |
| BORDER_STYLE_GROOVE | 속성 BorderStyle: Groove - 테두리가 캔버스에 새겨진 듯한 모양입니다. |
| BORDER_STYLE_RIDGE | 속성 BorderStyle: Ridge - 테두리가 캔버스에서 튀어나온 듯한 모양입니다 (Groove와 반대). |
| BORDER_STYLE_INSET | 속성 BorderStyle: Inset - 테두리가 전체 박스를 캔버스에 삽입된 듯하게 보이게 합니다. |
| BORDER_STYLE_OUTSET | 속성 BorderStyle: Outset - 테두리가 전체 상자를 캔버스 밖으로 나오는 것처럼 보이게 합니다 (Inset의 반대). |
| TEXT_ALIGN_START | 속성 TextAlign: Start - 시작 가장자리에 정렬됩니다. |
| TEXT_ALIGN_CENTER | 속성 TextAlign: Center - 시작과 끝 가장자리 사이에 가운데 정렬됩니다. |
| TEXT_ALIGN_END | 속성 TextAlign: End - 끝 가장자리에 정렬됩니다. |
| TEXT_ALIGN_JUSTIFY | 속성 TextAlign: Justify - 시작과 끝 가장자리에 모두 정렬되며, 필요에 따라 각 줄의 내부 간격을 확대하여 이러한 정렬을 달성합니다. 마지막(또는 유일한) 줄은 시작 가장자리에만 정렬됩니다. |
| WIDTH_AUTO | 속성 Width: Auto - 요소의 너비는 내용의 고유 너비에 따라 결정됩니다. |
| HEIGHT_AUTO | 속성 Height: Auto - 요소의 높이는 내용의 고유 높이에 따라 결정됩니다. |
| BLOCK_ALIGN_BEFORE | 속성 BlockAlign: Before - 첫 번째 자식의 할당 사각형의 앞 가장자리가 표 셀 내용 사각형의 앞 가장자리에 정렬됩니다. |
| BLOCK_ALIGN_MIDDLE | 속성 BlockAlign: Middle- 자식들이 표 셀 내부에 가운데 정렬됩니다. 첫 번째 자식 할당 사각형의 앞 가장자리와 표 셀 내용 사각형의 앞 가장자리 사이 거리와 마지막 자식 할당 사각형의 뒤 가장자리와 표 셀 내용 사각형의 뒤 가장자리 사이 거리는 동일해야 합니다. |
| BLOCK_ALIGN_AFTER | 속성 BlockAlign: After - 마지막 자식의 할당 사각형의 뒤 가장자리가 표 셀 내용 사각형의 뒤 가장자리에 정렬됩니다. |
| BLOCK_ALIGN_JUSTIFY | 속성 BlockAlign: Justify - 자식들이 표 셀 내용 사각형의 앞과 뒤 가장자리에 모두 정렬됩니다. 첫 번째 자식은 Before에 설명된 대로 배치되고 마지막 자식은 After에 설명된 대로 배치되며, 자식들 사이의 간격은 동일합니다. 자식이 하나만 있을 경우에는 Before와 같이 앞 가장자리에만 정렬됩니다. |
| INLINE_ALIGN_START | 속성 InlineAlign: Start - 각 자식의 할당 사각형의 시작 가장자리가 표 셀 내용 사각형의 시작 가장자리에 정렬됩니다. |
| INLINE_ALIGN_CENTER | Attribute InlineAlign: Center - 각 자식이 테이블 셀 내에서 가운데 정렬됩니다. 자식의 할당 사각형 시작 가장자리와 테이블 셀 내용 사각형 시작 가장자리 사이의 거리는 그들의 끝 가장자리 사이 거리와 동일해야 합니다. |
| INLINE_ALIGN_END | Attribute InlineAlign: End - 각 자식의 할당 사각형 끝 가장자리가 테이블 셀 내용 사각형의 끝 가장자리에 맞춰집니다. |
| LINE_HEIGHT_NORMAL | Attribute LineHeight: Normal - BaselineShift에 지정된 0이 아닌 값을 포함하도록 줄 높이를 조정합니다. |
| LINE_HEIGHT_AUTO | Attribute LineHeight: Auto - BaselineShift 값에 대한 조정은 수행되지 않습니다. |
| TEXT_DECORATION_TYPE_NONE | Attribute TextDecorationType: None - 텍스트 장식이 없습니다. |
| TEXT_DECORATION_TYPE_UNDERLINE | Attribute TextDecorationType: Underline - 텍스트 아래에 선이 그어집니다. |
| TEXT_DECORATION_TYPE_OVERLINE | Attribute TextDecorationType: Overline - 텍스트 위에 선이 그어집니다. |
| TEXT_DECORATION_TYPE_LINE_THROUGH | Attribute TextDecorationType: LineThrough - 텍스트 중간을 가로지르는 선이 그어집니다. |
| RUBY_ALIGN_START | Attribute RubyAlign: Start - 내용이 인라인 진행 방향의 시작 가장자리에 정렬됩니다. |
| RUBY_ALIGN_CENTER | Attribute RubyAlign: Center - 내용이 인라인 진행 방향에서 가운데 정렬됩니다. |
| RUBY_ALIGN_END | Attribute RubyAlign: End - 내용이 인라인 진행 방향의 끝 가장자리에 정렬됩니다. |
| RUBY_ALIGN_JUSTIFY | Attribute RubyAlign: Justify - 내용이 인라인 진행 방향에서 사용 가능한 너비를 채우도록 확장됩니다. |
| RUBY_ALIGN_DISTRIBUTE | Attribute RubyAlign: Distribute - 내용이 인라인 진행 방향에서 사용 가능한 너비를 채우도록 확장됩니다. 그러나 텍스트의 시작 가장자리와 끝 가장자리에도 공간이 삽입됩니다. 간격은 1:2:1 (시작:중간:끝) 비율로 배분됩니다. 루비가 텍스트 줄의 시작에 나타나는 경우 0:1:1 비율로, 텍스트 줄의 끝에 나타나는 경우 1:1:0 비율로 변경됩니다. |
| RUBY_POSITION_BEFORE | 속성 RubyPosition: Before - RT 콘텐츠는 요소의 before 가장자리를 따라 정렬되어야 합니다. |
| RUBY_POSITION_AFTER | 속성 RubyPosition: After - RT 콘텐츠는 요소의 after 가장자리를 따라 정렬되어야 합니다. |
| RUBY_POSITION_WARICHU | 속성 RubyPosition: Warichu - RT와 연관된 RP 요소는 RB 요소 뒤에 와리추 형태로 포맷되어야 합니다. |
| RUBY_POSITION_INLINE | 속성 RubyPosition: Inline - RT와 연관된 RP 요소는 RB 요소 뒤에 괄호 주석 형태로 포맷되어야 합니다. |
| GLYPH_ORIENTATION_VERTICAL_AUTO | 속성 GlyphOrientationVertical: Auto - 텍스트가 전체 너비인지(가로와 세로가 같은) 여부에 따라 기본 방향을 지정합니다. |
| LIST_NUMBERING_NONE | 속성 ListNumbering: None - 자동 번호 매기기가 없으며; Lbl 요소(존재하는 경우)는 번호 매기기 체계에 적용되지 않는 임의의 텍스트를 포함합니다. |
| LIST_NUMBERING_DISC | 속성 ListNumbering: Disc - 실선 원형 글머리표. |
| LIST_NUMBERING_CIRCLE | 속성 ListNumbering: Circle - 비채워진 원형 글머리표. |
| LIST_NUMBERING_SQUARE | 속성 ListNumbering: Square - 실선 사각형 글머리표. |
| LIST_NUMBERING_DECIMAL | 속성 ListNumbering: Decimal - 10진 아라비아 숫자(1-9, 10-99, ...). |
| LIST_NUMBERING_UPPER_ROMAN | 속성 ListNumbering: UpperRoman - 대문자 로마 숫자(I, II, III, IV, ...). |
| LIST_NUMBERING_LOWER_ROMAN | 속성 ListNumbering: LowerRoman - 소문자 로마 숫자(i, ii, iii, iv, ...). |
| LIST_NUMBERING_UPPER_ALPHA | 속성 ListNumbering: UpperAlpha - 대문자 (A, B, C, ...). |
| LIST_NUMBERING_LOWER_ALPHA | 속성 ListNumbering: LowerAlpha - 소문자 (a, b, c, ...). |
| ROLE_RB | 속성 Role: rb - 라디오 버튼. |
| ROLE_CB | 속성 Role: cb - 체크 박스. |
| ROLE_PB | 속성 Role: pb - 푸시 버튼. |
| ROLE_TV | 속성 Role: tv - 텍스트 값 필드. |
| CHECKED_ON | 속성 checked: On - 라디오 버튼 또는 체크 박스 필드의 상태. |
| CHECKED_OFF | 속성 checked: Off - 라디오 버튼 또는 체크 박스 필드의 상태. |
| CHECKED_NEUTRAL | 속성 checked: Neutral - 라디오 버튼 또는 체크 박스 필드의 상태. |
| SCOPE_ROW | 속성 Scope: Row. |
| SCOPE_COLUMN | 속성 Scope: Column. |
| SCOPE_BOTH | 속성 Scope: Both. |
## 메서드
| 이름 | 설명 |
| :- | :- |
| from_name_attribute_key(name, attribute_key) | 속성 키에 대한 속성 이름을 가져옵니다. |

### 또 보기

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

