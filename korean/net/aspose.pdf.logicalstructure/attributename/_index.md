---
title: Class AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LogicalStructure.AttributeName 클래스. 속성 이름 값에 대한 클래스를 나타냅니다.
type: docs
weight: 6220
url: /ko/net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName 클래스

속성 이름 값에 대한 클래스를 나타냅니다.

```csharp
public sealed class AttributeName
```

## 속성

| 이름 | 설명 |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey/) { get; } | 속성 키를 가져옵니다. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name/) { get; } | 속성의 이름 값을 가져옵니다. |

## 메서드

| 이름 | 설명 |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey/)(string, AttributeKey) | 속성 키에 대한 속성 이름을 가져옵니다. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring/)() | 현재 객체를 나타내는 문자열을 반환합니다. |

## 필드

| 이름 | 설명 |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after/) | 속성 BlockAlign: After - 마지막 자식의 할당 사각형의 후면 가장자리가 테이블 셀의 콘텐츠 사각형과 정렬됩니다. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before/) | 속성 BlockAlign: Before - 첫 번째 자식의 할당 사각형의 전면 가장자리가 테이블 셀의 콘텐츠 사각형과 정렬됩니다. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify/) | 속성 BlockAlign: Justify - 자식들이 테이블 셀의 콘텐츠 사각형의 전면 및 후면 가장자리에 정렬됩니다. 첫 번째 자식은 Before에 설명된 대로 배치되고 마지막 자식은 After에 설명된 대로 배치되며, 자식들 사이에 동일한 간격이 유지됩니다. 자식이 하나만 있는 경우, Before와 같이 전면 가장자리에만 정렬됩니다. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle/) | 속성 BlockAlign: Middle - 자식들이 테이블 셀 내에서 중앙에 배치됩니다. 첫 번째 자식의 할당 사각형의 전면 가장자리와 테이블 셀의 콘텐츠 사각형 사이의 거리는 마지막 자식의 할당 사각형의 후면 가장자리와 테이블 셀의 콘텐츠 사각형 사이의 거리와 동일해야 합니다. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed/) | 속성 BorderStyle: Dashed - 테두리는 짧은 선분의 연속입니다. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted/) | 속성 BorderStyle: Dotted - 테두리는 점의 연속입니다. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double/) | 속성 BorderStyle: Double - 테두리는 두 개의 실선입니다. 두 선의 합과 그 사이의 간격은 BorderThickness의 값과 같습니다. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove/) | 속성 BorderStyle: Groove - 테두리는 캔버스에 새겨진 것처럼 보입니다. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden/) | 속성 BorderStyle: Hidden - None과 동일하지만 테이블 요소의 테두리 충돌 해결 측면에서 다릅니다. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset/) | 속성 BorderStyle: Inset - 테두리는 전체 상자가 캔버스에 내장된 것처럼 보이게 합니다. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none/) | 속성 BorderStyle: None - 테두리가 없습니다. BorderThickness의 계산된 값을 0으로 강제합니다. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset/) | 속성 BorderStyle: Outset - 테두리는 전체 상자가 캔버스에서 나오는 것처럼 보이게 합니다(Inset의 반대). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge/) | 속성 BorderStyle: Ridge - 테두리는 캔버스에서 나오는 것처럼 보입니다(Groove의 반대). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid/) | 속성 BorderStyle: Solid - 테두리는 단일 선분입니다. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral/) | 속성 checked: Neutral - 라디오 버튼 또는 체크 박스 필드의 상태입니다. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off/) | 속성 checked: Off - 라디오 버튼 또는 체크 박스 필드의 상태입니다. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on/) | 속성 checked: On - 라디오 버튼 또는 체크 박스 필드의 상태입니다. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto/) | 속성 GlyphOrientationVertical: Auto - 텍스트의 기본 방향을 지정합니다. 전체 폭인지 여부에 따라 결정됩니다(너비가 높이와 같습니다). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto/) | 속성 Height: Auto - 요소의 높이는 콘텐츠의 고유한 높이에 의해 결정됩니다. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center/) | 속성 InlineAlign: Center - 각 자식이 테이블 셀 내에서 중앙에 배치됩니다. 자식의 할당 사각형의 시작 가장자리와 테이블 셀의 콘텐츠 사각형 사이의 거리는 끝 가장자리 사이의 거리와 동일해야 합니다. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end/) | 속성 InlineAlign: End - 각 자식의 할당 사각형의 끝 가장자가 테이블 셀의 콘텐츠 사각형과 정렬됩니다. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start/) | 속성 InlineAlign: Start - 각 자식의 할당 사각형의 시작 가장자가 테이블 셀의 콘텐츠 사각형과 정렬됩니다. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto/) | 속성 LineHeight: Auto - BaselineShift의 값에 대한 조정이 이루어지지 않습니다. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal/) | 속성 LineHeight: Normal - BaselineShift에 대해 지정된 비제로 값을 포함하도록 줄 높이를 조정합니다. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle/) | 속성 ListNumbering: Circle - 열린 원형 글머리 기호입니다. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal/) | 속성 ListNumbering: Decimal - 십진수 아라비아 숫자(1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc/) | 속성 ListNumbering: Disc - 단단한 원형 글머리 기호입니다. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha/) | 속성 ListNumbering: LowerAlpha - 소문자 알파벳(a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman/) | 속성 ListNumbering: LowerRoman - 소문자 로마 숫자(i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none/) | 속성 ListNumbering: None - 자동 번호 매김 없음; Lbl 요소(존재하는 경우)는 어떤 번호 매김 체계에도 적용되지 않는 임의의 텍스트를 포함합니다. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square/) | 속성 ListNumbering: Square - 단단한 정사각형 글머리 기호입니다. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha/) | 속성 ListNumbering: UpperAlpha - 대문자 알파벳(A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman/) | 속성 ListNumbering: UpperRoman - 대문자 로마 숫자(I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before/) | 속성 Placement: Before - 요소의 할당 사각형의 전면 가장자리가 가장 가까운 포함 참조 영역과 일치하도록 배치됩니다. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block/) | 속성 Placement: Block - 포함된 참조 영역 또는 부모 BLSE 내에서 블록 진행 방향으로 쌓입니다. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end/) | 속성 Placement: End - 요소의 할당 사각형의 끝 가장자리가 가장 가까운 포함 참조 영역과 일치하도록 배치됩니다. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline/) | 속성 Placement: Inline - 포함된 BLSE 내에서 인라인 진행 방향으로 포장됩니다. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start/) | 속성 Placement: Start - 요소의 할당 사각형의 시작 가장자리가 가장 가까운 포함 참조 영역과 일치하도록 배치됩니다. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb/) | 속성 Role: cb - 체크 박스입니다. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb/) | 속성 Role: pb - 푸시 버튼입니다. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb/) | 속성 Role: rb - 라디오 버튼입니다. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv/) | 속성 Role: tv - 텍스트-값 필드입니다. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center/) | 속성 RubyAlign: Center - 콘텐츠가 인라인 진행 방향으로 중앙에 배치됩니다. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute/) | 속성 RubyAlign: Distribute - 콘텐츠가 인라인 진행 방향으로 사용 가능한 너비를 채우도록 확장됩니다. 그러나 텍스트의 시작 가장자리와 끝 가장자리에 공간이 삽입됩니다. 간격은 1:2:1(시작:중간:끝) 비율로 분배됩니다. 루비가 텍스트 줄의 시작에 나타나면 0:1:1 비율로 변경되며, 루비가 텍스트 줄의 끝에 나타나면 1:1:0 비율로 변경됩니다. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end/) | 속성 RubyAlign: End - 콘텐츠가 인라인 진행 방향의 끝 가장자리에 정렬됩니다. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify/) | 속성 RubyAlign: Justify - 콘텐츠가 인라인 진행 방향으로 사용 가능한 너비를 채우도록 확장됩니다. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start/) | 속성 RubyAlign: Start - 콘텐츠가 인라인 진행 방향의 시작 가장자리에 정렬됩니다. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after/) | 속성 RubyPosition: After - RT 콘텐츠가 요소의 후면 가장자리를 따라 정렬됩니다. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before/) | 속성 RubyPosition: Before - RT 콘텐츠가 요소의 전면 가장자리를 따라 정렬됩니다. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline/) | 속성 RubyPosition: Inline - RT 및 관련 RP 요소가 RB 요소 뒤에 괄호 주석으로 형식화됩니다. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu/) | 속성 RubyPosition: Warichu - RT 및 관련 RP 요소가 RB 요소 뒤에 와리치로 형식화됩니다. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both/) | 속성 Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column/) | 속성 Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row/) | 속성 Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center/) | 속성 TextAlign: Center - 시작과 끝 가장자리 사이에 중앙에 배치됩니다. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end/) | 속성 TextAlign: End - 끝 가장자리에 정렬됩니다. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify/) | 속성 TextAlign: Justify - 시작과 끝 가장자리에 정렬되며, 필요에 따라 각 줄 내에서 내부 간격이 확장됩니다. 마지막(또는 유일한) 줄은 시작 가장자리에만 정렬됩니다. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start/) | 속성 TextAlign: Start - 시작 가장자리에 정렬됩니다. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough/) | 속성 TextDecorationType: LineThrough - 텍스트 중간에 선이 그어집니다. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none/) | 속성 TextDecorationType: None - 텍스트 장식이 없습니다. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline/) | 속성 TextDecorationType: Overline - 텍스트 위에 선이 그어집니다. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline/) | 속성 TextDecorationType: Underline - 텍스트 아래에 선이 그어집니다. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto/) | 속성 Width: Auto - 요소의 너비는 콘텐츠의 고유한 너비에 의해 결정됩니다. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb/) | 속성 WritingMode: LrTb - 왼쪽에서 오른쪽으로 인라인 진행; 위에서 아래로 블록 진행. 이는 서양 문서 시스템의 일반적인 쓰기 모드입니다. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb/) | 속성 WritingMode: RlTb - 오른쪽에서 왼쪽으로 인라인 진행; 위에서 아래로 블록 진행. 이는 아랍어 및 히브리어 문서 시스템의 일반적인 쓰기 모드입니다. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl/) | 속성 WritingMode: TbRl - 위에서 아래로 인라인 진행; 오른쪽에서 왼쪽으로 블록 진행. 이는 중국어 및 일본어 문서 시스템의 일반적인 쓰기 모드입니다. |

### 참조

* 네임스페이스 [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure/)
* 어셈블리 [Aspose.PDF](../../)