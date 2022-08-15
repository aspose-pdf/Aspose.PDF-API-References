---
title: AttributeName
second_title: Aspose.PDF for .NET API Reference
description: Represents class for Attribute Name Values.
type: docs
weight: 4000
url: /net/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class

Represents class for Attribute Name Values.

```csharp
public sealed class AttributeName
```

## Properties

| Name | Description |
| --- | --- |
| [AttributeKey](../../aspose.pdf.logicalstructure/attributename/attributekey) { get; } | Gets attribute key. |
| [Name](../../aspose.pdf.logicalstructure/attributename/name) { get; } | Gets name value of attribute. |

## Methods

| Name | Description |
| --- | --- |
| static [FromNameAttributeKey](../../aspose.pdf.logicalstructure/attributename/fromnameattributekey)(string, AttributeKey) | Gets attribute name for attribute key. |
| override [ToString](../../aspose.pdf.logicalstructure/attributename/tostring)() | Returns a string that represents the current object. |

## Fields

| Name | Description |
| --- | --- |
| static readonly [BlockAlign_After](../../aspose.pdf.logicalstructure/attributename/blockalign_after) | Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static readonly [BlockAlign_Before](../../aspose.pdf.logicalstructure/attributename/blockalign_before) | Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static readonly [BlockAlign_Justify](../../aspose.pdf.logicalstructure/attributename/blockalign_justify) | Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. The first child shall be placed as described for Before and the last child as described for After, with equal spacing between the children. If there is only one child, it shall be aligned with the before edge only, as for Before. |
| static readonly [BlockAlign_Middle](../../aspose.pdf.logicalstructure/attributename/blockalign_middle) | Attribute BlockAlign: Middle- Children centered within the table cell. The distance between the before edge of the first child's allocation rectangle and that of the table cell's content rectangle shall be the same as the distance between the after edge of the last child's allocation rectangle and that of the table cell's content rectangle. |
| static readonly [BorderStyle_Dashed](../../aspose.pdf.logicalstructure/attributename/borderstyle_dashed) | Attribute BorderStyle: Dashed - The border is a series of short line segments. |
| static readonly [BorderStyle_Dotted](../../aspose.pdf.logicalstructure/attributename/borderstyle_dotted) | Attribute BorderStyle: Dotted - The border is a series of dots. |
| static readonly [BorderStyle_Double](../../aspose.pdf.logicalstructure/attributename/borderstyle_double) | Attribute BorderStyle: Double - The border is two solid lines. The sum of the two lines and the space between them equals the value of BorderThickness. |
| static readonly [BorderStyle_Groove](../../aspose.pdf.logicalstructure/attributename/borderstyle_groove) | Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas. |
| static readonly [BorderStyle_Hidden](../../aspose.pdf.logicalstructure/attributename/borderstyle_hidden) | Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements. |
| static readonly [BorderStyle_Inset](../../aspose.pdf.logicalstructure/attributename/borderstyle_inset) | Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas. |
| static readonly [BorderStyle_None](../../aspose.pdf.logicalstructure/attributename/borderstyle_none) | Attribute BorderStyle: None - No border. Forces the computed value of BorderThicknessto be 0. |
| static readonly [BorderStyle_Outset](../../aspose.pdf.logicalstructure/attributename/borderstyle_outset) | Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset). |
| static readonly [BorderStyle_Ridge](../../aspose.pdf.logicalstructure/attributename/borderstyle_ridge) | Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove). |
| static readonly [BorderStyle_Solid](../../aspose.pdf.logicalstructure/attributename/borderstyle_solid) | Attribute BorderStyle: Solid - The border is a single line segment. |
| static readonly [Checked_neutral](../../aspose.pdf.logicalstructure/attributename/checked_neutral) | Attribute checked: Neutral - The state of a radio button or check box field. |
| static readonly [Checked_off](../../aspose.pdf.logicalstructure/attributename/checked_off) | Attribute checked: Off - The state of a radio button or check box field. |
| static readonly [Checked_on](../../aspose.pdf.logicalstructure/attributename/checked_on) | Attribute checked: On - The state of a radio button or check box field. |
| static readonly [GlyphOrientationVertical_Auto](../../aspose.pdf.logicalstructure/attributename/glyphorientationvertical_auto) | Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high). |
| static readonly [Height_Auto](../../aspose.pdf.logicalstructure/attributename/height_auto) | Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content. |
| static readonly [InlineAlign_Center](../../aspose.pdf.logicalstructure/attributename/inlinealign_center) | Attribute InlineAlign: Center - Each child centered within the table cell. The distance between the start edges of the child's allocation rectangle and the table cell's content rectangle shall be the same as the distance between their end edges. |
| static readonly [InlineAlign_End](../../aspose.pdf.logicalstructure/attributename/inlinealign_end) | Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static readonly [InlineAlign_Start](../../aspose.pdf.logicalstructure/attributename/inlinealign_start) | Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static readonly [LineHeight_Auto](../../aspose.pdf.logicalstructure/attributename/lineheight_auto) | Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made. |
| static readonly [LineHeight_Normal](../../aspose.pdf.logicalstructure/attributename/lineheight_normal) | Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift. |
| static readonly [ListNumbering_Circle](../../aspose.pdf.logicalstructure/attributename/listnumbering_circle) | Attribute ListNumbering: Circle - Open circular bullet. |
| static readonly [ListNumbering_Decimal](../../aspose.pdf.logicalstructure/attributename/listnumbering_decimal) | Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...). |
| static readonly [ListNumbering_Disc](../../aspose.pdf.logicalstructure/attributename/listnumbering_disc) | Attribute ListNumbering: Disc - Solid circular bullet. |
| static readonly [ListNumbering_LowerAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_loweralpha) | Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...). |
| static readonly [ListNumbering_LowerRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_lowerroman) | Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...). |
| static readonly [ListNumbering_None](../../aspose.pdf.logicalstructure/attributename/listnumbering_none) | Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme. |
| static readonly [ListNumbering_Square](../../aspose.pdf.logicalstructure/attributename/listnumbering_square) | Attribute ListNumbering: Square - Solid square bullet. |
| static readonly [ListNumbering_UpperAlpha](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperalpha) | Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...). |
| static readonly [ListNumbering_UpperRoman](../../aspose.pdf.logicalstructure/attributename/listnumbering_upperroman) | Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...). |
| static readonly [Placement_Before](../../aspose.pdf.logicalstructure/attributename/placement_before) | Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| static readonly [Placement_Block](../../aspose.pdf.logicalstructure/attributename/placement_block) | Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE. |
| static readonly [Placement_End](../../aspose.pdf.logicalstructure/attributename/placement_end) | Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| static readonly [Placement_Inline](../../aspose.pdf.logicalstructure/attributename/placement_inline) | Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE. |
| static readonly [Placement_Start](../../aspose.pdf.logicalstructure/attributename/placement_start) | Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| static readonly [Role_cb](../../aspose.pdf.logicalstructure/attributename/role_cb) | Attribute Role: cb - Check box. |
| static readonly [Role_pb](../../aspose.pdf.logicalstructure/attributename/role_pb) | Attribute Role: pb - Push button. |
| static readonly [Role_rb](../../aspose.pdf.logicalstructure/attributename/role_rb) | Attribute Role: rb - Radio button. |
| static readonly [Role_tv](../../aspose.pdf.logicalstructure/attributename/role_tv) | Attribute Role: tv - Text-value field. |
| static readonly [RubyAlign_Center](../../aspose.pdf.logicalstructure/attributename/rubyalign_center) | Attribute RubyAlign: Center - The content shall be centered in the inline-progression direction. |
| static readonly [RubyAlign_Distribute](../../aspose.pdf.logicalstructure/attributename/rubyalign_distribute) | Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. However, space shall also be inserted at the start edge and end edge of the text. The spacing shall be distributed using a 1:2:1 (start:infix:end) ratio. It shall be changed to a 0:1:1 ratio if the ruby appears at the start of a text line or to a 1:1:0 ratio if the ruby appears at the end of the text line. |
| static readonly [RubyAlign_End](../../aspose.pdf.logicalstructure/attributename/rubyalign_end) | Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction. |
| static readonly [RubyAlign_Justify](../../aspose.pdf.logicalstructure/attributename/rubyalign_justify) | Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction. |
| static readonly [RubyAlign_Start](../../aspose.pdf.logicalstructure/attributename/rubyalign_start) | Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction. |
| static readonly [RubyPosition_After](../../aspose.pdf.logicalstructure/attributename/rubyposition_after) | Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element. |
| static readonly [RubyPosition_Before](../../aspose.pdf.logicalstructure/attributename/rubyposition_before) | Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element. |
| static readonly [RubyPosition_Inline](../../aspose.pdf.logicalstructure/attributename/rubyposition_inline) | Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element. |
| static readonly [RubyPosition_Warichu](../../aspose.pdf.logicalstructure/attributename/rubyposition_warichu) | Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element. |
| static readonly [Scope_Both](../../aspose.pdf.logicalstructure/attributename/scope_both) | Attribute Scope: Both. |
| static readonly [Scope_Column](../../aspose.pdf.logicalstructure/attributename/scope_column) | Attribute Scope: Column. |
| static readonly [Scope_Row](../../aspose.pdf.logicalstructure/attributename/scope_row) | Attribute Scope: Row. |
| static readonly [TextAlign_Center](../../aspose.pdf.logicalstructure/attributename/textalign_center) | Attribute TextAlign: Center - Centered between the start and end edges. |
| static readonly [TextAlign_End](../../aspose.pdf.logicalstructure/attributename/textalign_end) | Attribute TextAlign: End - Aligned with the end edge. |
| static readonly [TextAlign_Justify](../../aspose.pdf.logicalstructure/attributename/textalign_justify) | Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. The last (or only) line shall be aligned with the start edge only. |
| static readonly [TextAlign_Start](../../aspose.pdf.logicalstructure/attributename/textalign_start) | Attribute TextAlign: Start - Aligned with the start edge. |
| static readonly [TextDecorationType_LineThrough](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_linethrough) | Attribute TextDecorationType: LineThrough - A line through the middle of the text. |
| static readonly [TextDecorationType_None](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_none) | Attribute TextDecorationType: None - No text decoration. |
| static readonly [TextDecorationType_Overline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_overline) | Attribute TextDecorationType: Overline - A line above the text. |
| static readonly [TextDecorationType_Underline](../../aspose.pdf.logicalstructure/attributename/textdecorationtype_underline) | Attribute TextDecorationType: Underline - A line below the text. |
| static readonly [Width_Auto](../../aspose.pdf.logicalstructure/attributename/width_auto) | Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content. |
| static readonly [WritingMode_LrTb](../../aspose.pdf.logicalstructure/attributename/writingmode_lrtb) | Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. This is the typical writing mode for Western writing systems. |
| static readonly [WritingMode_RlTb](../../aspose.pdf.logicalstructure/attributename/writingmode_rltb) | Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. This is the typical writing mode for Arabic and Hebrew writing systems. |
| static readonly [WritingMode_TbRl](../../aspose.pdf.logicalstructure/attributename/writingmode_tbrl) | Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. This is the typical writing mode for Chinese and Japanese writing systems. |

### See Also

* namespace [Aspose.Pdf.LogicalStructure](../../aspose.pdf.logicalstructure)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
