---
title: Aspose::Pdf::LogicalStructure::AttributeName class
linktitle: AttributeName
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::AttributeName class. Represents class for Attribute Name Values in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.logicalstructure/attributename/
---
## AttributeName class


Represents class for Attribute Name Values.

```cpp
class AttributeName : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| static [FromNameAttributeKey](./fromnameattributekey/)(System::String, System::SharedPtr\<Aspose::Pdf::LogicalStructure::AttributeKey\>) | Gets attribute name for attribute key. |
| [get_AttributeKey](./get_attributekey/)() const | Gets attribute key. |
| [get_Name](./get_name/)() const | Gets name value of attribute. |
| [ToString](./tostring/)() const override | Returns a string that represents the current object. |
## Fields

| Field | Description |
| --- | --- |
| static [BlockAlign_After](./blockalign_after/) | Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static [BlockAlign_Before](./blockalign_before/) | Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static [BlockAlign_Justify](./blockalign_justify/) | Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. The first child shall be placed as described for Before and the last child as described for After, with equal spacing between the children. If there is only one child, it shall be aligned with the before edge only, as for Before. |
| static [BlockAlign_Middle](./blockalign_middle/) | Attribute BlockAlign: Middle- Children centered within the table cell. The distance between the before edge of the first child's allocation rectangle and that of the table cell's content rectangle shall be the same as the distance between the after edge of the last child's allocation rectangle and that of the table cell's content rectangle. |
| static [BorderStyle_Dashed](./borderstyle_dashed/) | Attribute BorderStyle: Dashed - The border is a series of short line segments. |
| static [BorderStyle_Dotted](./borderstyle_dotted/) | Attribute BorderStyle: Dotted - The border is a series of dots. |
| static [BorderStyle_Double](./borderstyle_double/) | Attribute BorderStyle: Double - The border is two solid lines. The sum of the two lines and the space between them equals the value of BorderThickness. |
| static [BorderStyle_Groove](./borderstyle_groove/) | Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas. |
| static [BorderStyle_Hidden](./borderstyle_hidden/) | Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements. |
| static [BorderStyle_Inset](./borderstyle_inset/) | Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas. |
| static [BorderStyle_None](./borderstyle_none/) | Attribute BorderStyle: None - No border. Forces the computed value of BorderThicknessto be 0. |
| static [BorderStyle_Outset](./borderstyle_outset/) | Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset). |
| static [BorderStyle_Ridge](./borderstyle_ridge/) | Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove). |
| static [BorderStyle_Solid](./borderstyle_solid/) | Attribute BorderStyle: Solid - The border is a single line segment. |
| static [Checked_neutral](./checked_neutral/) | Attribute checked: Neutral - The state of a radio button or check box field. |
| static [Checked_off](./checked_off/) | Attribute checked: Off - The state of a radio button or check box field. |
| static [Checked_on](./checked_on/) | Attribute checked: On - The state of a radio button or check box field. |
| static [GlyphOrientationVertical_Auto](./glyphorientationvertical_auto/) | Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high). |
| static [Height_Auto](./height_auto/) | Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content. |
| static [InlineAlign_Center](./inlinealign_center/) | Attribute InlineAlign: [Center](../../aspose.pdf/center/) - Each child centered within the table cell. The distance between the start edges of the child's allocation rectangle and the table cell's content rectangle shall be the same as the distance between their end edges. |
| static [InlineAlign_End](./inlinealign_end/) | Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static [InlineAlign_Start](./inlinealign_start/) | Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| static [LineHeight_Auto](./lineheight_auto/) | Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made. |
| static [LineHeight_Normal](./lineheight_normal/) | Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift. |
| static [ListNumbering_Circle](./listnumbering_circle/) | Attribute ListNumbering: Circle - Open circular bullet. |
| static [ListNumbering_Decimal](./listnumbering_decimal/) | Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...). |
| static [ListNumbering_Disc](./listnumbering_disc/) | Attribute ListNumbering: Disc - Solid circular bullet. |
| static [ListNumbering_LowerAlpha](./listnumbering_loweralpha/) | Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...). |
| static [ListNumbering_LowerRoman](./listnumbering_lowerroman/) | Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...). |
| static [ListNumbering_None](./listnumbering_none/) | Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme. |
| static [ListNumbering_Square](./listnumbering_square/) | Attribute ListNumbering: Square - Solid square bullet. |
| static [ListNumbering_UpperAlpha](./listnumbering_upperalpha/) | Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...). |
| static [ListNumbering_UpperRoman](./listnumbering_upperroman/) | Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...). |
| static [Placement_Before](./placement_before/) | Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| static [Placement_Block](./placement_block/) | Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE. |
| static [Placement_End](./placement_end/) | Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| static [Placement_Inline](./placement_inline/) | Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE. |
| static [Placement_Start](./placement_start/) | Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| static [Role_cb](./role_cb/) | Attribute Role: cb - Check box. |
| static [Role_pb](./role_pb/) | Attribute Role: pb - Push button. |
| static [Role_rb](./role_rb/) | Attribute Role: rb - Radio button. |
| static [Role_tv](./role_tv/) | Attribute Role: tv - Text-value field. |
| static [RubyAlign_Center](./rubyalign_center/) | Attribute RubyAlign: [Center](../../aspose.pdf/center/) - The content shall be centered in the inline-progression direction. |
| static [RubyAlign_Distribute](./rubyalign_distribute/) | Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. However, space shall also be inserted at the start edge and end edge of the text. The spacing shall be distributed using a 1:2:1 (start:infix:end) ratio. It shall be changed to a 0:1:1 ratio if the ruby appears at the start of a text line or to a 1:1:0 ratio if the ruby appears at the end of the text line. |
| static [RubyAlign_End](./rubyalign_end/) | Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction. |
| static [RubyAlign_Justify](./rubyalign_justify/) | Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction. |
| static [RubyAlign_Start](./rubyalign_start/) | Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction. |
| static [RubyPosition_After](./rubyposition_after/) | Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element. |
| static [RubyPosition_Before](./rubyposition_before/) | Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element. |
| static [RubyPosition_Inline](./rubyposition_inline/) | Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element. |
| static [RubyPosition_Warichu](./rubyposition_warichu/) | Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element. |
| static [Scope_Both](./scope_both/) | Attribute Scope: Both. |
| static [Scope_Column](./scope_column/) | Attribute Scope: Column. |
| static [Scope_Row](./scope_row/) | Attribute Scope: [Row](../../aspose.pdf/row/). |
| static [TextAlign_Center](./textalign_center/) | Attribute TextAlign: [Center](../../aspose.pdf/center/) - Centered between the start and end edges. |
| static [TextAlign_End](./textalign_end/) | Attribute TextAlign: End - Aligned with the end edge. |
| static [TextAlign_Justify](./textalign_justify/) | Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. The last (or only) line shall be aligned with the start edge only. |
| static [TextAlign_Start](./textalign_start/) | Attribute TextAlign: Start - Aligned with the start edge. |
| static [TextDecorationType_LineThrough](./textdecorationtype_linethrough/) | Attribute TextDecorationType: LineThrough - A line through the middle of the text. |
| static [TextDecorationType_None](./textdecorationtype_none/) | Attribute TextDecorationType: None - No text decoration. |
| static [TextDecorationType_Overline](./textdecorationtype_overline/) | Attribute TextDecorationType: Overline - A line above the text. |
| static [TextDecorationType_Underline](./textdecorationtype_underline/) | Attribute TextDecorationType: Underline - A line below the text. |
| static [Width_Auto](./width_auto/) | Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content. |
| static [WritingMode_LrTb](./writingmode_lrtb/) | Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. This is the typical writing mode for Western writing systems. |
| static [WritingMode_RlTb](./writingmode_rltb/) | Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. This is the typical writing mode for Arabic and Hebrew writing systems. |
| static [WritingMode_TbRl](./writingmode_tbrl/) | Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. This is the typical writing mode for Chinese and Japanese writing systems. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::LogicalStructure](../)
* Library [Aspose.PDF for C++](../../)
