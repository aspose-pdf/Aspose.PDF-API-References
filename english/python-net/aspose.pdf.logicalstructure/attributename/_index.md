---
title: AttributeName
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents class for Attribute Name Values.
type: docs
weight: 50
url: /python-net/aspose.pdf.logicalstructure/attributename/
---

## AttributeName class

Represents class for Attribute Name Values.

The AttributeName type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|name|Gets name value of attribute.|
|attribute_key|Gets attribute key.|
|PLACEMENT_BLOCK|Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE.|
|PLACEMENT_INLINE|Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE.|
|PLACEMENT_BEFORE|Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.|
|PLACEMENT_START|Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.|
|PLACEMENT_END|Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.|
|WRITING_MODE_LR_TB|Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. This is the typical writing mode for Western writing systems.|
|WRITING_MODE_RL_TB|Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. This is the typical writing mode for Arabic and Hebrew writing systems.|
|WRITING_MODE_TB_RL|Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. This is the typical writing mode for Chinese and Japanese writing systems.|
|BORDER_STYLE_NONE|Attribute BorderStyle: None - No border. Forces the computed value of BorderThicknessto be 0.|
|BORDER_STYLE_HIDDEN|Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements.|
|BORDER_STYLE_DOTTED|Attribute BorderStyle: Dotted - The border is a series of dots.|
|BORDER_STYLE_DASHED|Attribute BorderStyle: Dashed - The border is a series of short line segments.|
|BORDER_STYLE_SOLID|Attribute BorderStyle: Solid - The border is a single line segment.|
|BORDER_STYLE_DOUBLE|Attribute BorderStyle: Double - The border is two solid lines. The sum of the two lines and the space between them equals the value of BorderThickness.|
|BORDER_STYLE_GROOVE|Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas.|
|BORDER_STYLE_RIDGE|Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove).|
|BORDER_STYLE_INSET|Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas.|
|BORDER_STYLE_OUTSET|Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset).|
|TEXT_ALIGN_START|Attribute TextAlign: Start - Aligned with the start edge.|
|TEXT_ALIGN_CENTER|Attribute TextAlign: Center - Centered between the start and end edges.|
|TEXT_ALIGN_END|Attribute TextAlign: End - Aligned with the end edge.|
|TEXT_ALIGN_JUSTIFY|Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. The last (or only) line shall be aligned with the start edge only.|
|WIDTH_AUTO|Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content.|
|HEIGHT_AUTO|Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content.|
|BLOCK_ALIGN_BEFORE|Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle.|
|BLOCK_ALIGN_MIDDLE|Attribute BlockAlign: Middle- Children centered within the table cell. The distance between the before edge of the first child's allocation rectangle and that of the table cell's content rectangle shall be the same as the distance between the after edge of the last child's allocation rectangle and that of the table cell's content rectangle.|
|BLOCK_ALIGN_AFTER|Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle.|
|BLOCK_ALIGN_JUSTIFY|Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. The first child shall be placed as described for Before and the last child as described for After, with equal spacing between the children. If there is only one child, it shall be aligned with the before edge only, as for Before.|
|INLINE_ALIGN_START|Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle.|
|INLINE_ALIGN_CENTER|Attribute InlineAlign: Center - Each child centered within the table cell. The distance between the start edges of the child's allocation rectangle and the table cell's content rectangle shall be the same as the distance between their end edges.|
|INLINE_ALIGN_END|Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle.|
|LINE_HEIGHT_NORMAL|Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift.|
|LINE_HEIGHT_AUTO|Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made.|
|TEXT_DECORATION_TYPE_NONE|Attribute TextDecorationType: None - No text decoration.|
|TEXT_DECORATION_TYPE_UNDERLINE|Attribute TextDecorationType: Underline - A line below the text.|
|TEXT_DECORATION_TYPE_OVERLINE|Attribute TextDecorationType: Overline - A line above the text.|
|TEXT_DECORATION_TYPE_LINE_THROUGH|Attribute TextDecorationType: LineThrough - A line through the middle of the text.|
|RUBY_ALIGN_START|Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction.|
|RUBY_ALIGN_CENTER|Attribute RubyAlign: Center - The content shall be centered in the inline-progression direction.|
|RUBY_ALIGN_END|Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction.|
|RUBY_ALIGN_JUSTIFY|Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction.|
|RUBY_ALIGN_DISTRIBUTE|Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. However, space shall also be inserted at the start edge and end edge of the text. The spacing shall be distributed using a 1:2:1 (start:infix:end) ratio. It shall be changed to a 0:1:1 ratio if the ruby appears at the start of a text line or to a 1:1:0 ratio if the ruby appears at the end of the text line.|
|RUBY_POSITION_BEFORE|Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element.|
|RUBY_POSITION_AFTER|Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element.|
|RUBY_POSITION_WARICHU|Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element.|
|RUBY_POSITION_INLINE|Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element.|
|GLYPH_ORIENTATION_VERTICAL_AUTO|Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high).|
|LIST_NUMBERING_NONE|Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme.|
|LIST_NUMBERING_DISC|Attribute ListNumbering: Disc - Solid circular bullet.|
|LIST_NUMBERING_CIRCLE|Attribute ListNumbering: Circle - Open circular bullet.|
|LIST_NUMBERING_SQUARE|Attribute ListNumbering: Square - Solid square bullet.|
|LIST_NUMBERING_DECIMAL|Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...).|
|LIST_NUMBERING_UPPER_ROMAN|Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...).|
|LIST_NUMBERING_LOWER_ROMAN|Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...).|
|LIST_NUMBERING_UPPER_ALPHA|Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...).|
|LIST_NUMBERING_LOWER_ALPHA|Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...).|
|ROLE_RB|Attribute Role: rb - Radio button.|
|ROLE_CB|Attribute Role: cb - Check box.|
|ROLE_PB|Attribute Role: pb - Push button.|
|ROLE_TV|Attribute Role: tv - Text-value field.|
|CHECKED_ON|Attribute checked: On - The state of a radio button or check box field.|
|CHECKED_OFF|Attribute checked: Off - The state of a radio button or check box field.|
|CHECKED_NEUTRAL|Attribute checked: Neutral - The state of a radio button or check box field.|
|SCOPE_ROW|Attribute Scope: Row.|
|SCOPE_COLUMN|Attribute Scope: Column.|
|SCOPE_BOTH|Attribute Scope: Both.|
## Methods
| Name | Description |
| :- | :- |
|from_name_attribute_key(name, attribute_key)|Gets attribute name for attribute key.|

### See Also

* namespace [aspose.pdf.logicalstructure](/pdf/python-net/aspose.pdf.logicalstructure/)
* assembly [Aspose.PDF](/pdf/python-net/)

