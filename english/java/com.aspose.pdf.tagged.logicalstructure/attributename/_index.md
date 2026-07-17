---
title: AttributeName
linktitle: AttributeName
second_title: Aspose.PDF for Java API Reference
description: Represents class for Attribute Name Values.
type: docs
weight: 20
url: /java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.AttributeName

```
public final class AttributeName extends Object
```

Represents class for Attribute Name Values.

## Fields

| Field | Description |
| --- | --- |
| [BlockAlign_After](#BlockAlign_After) | Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [BlockAlign_Before](#BlockAlign_Before) | Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [BlockAlign_Justify](#BlockAlign_Justify) | Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. The first child shall be placed as described for Before and the last child as described for After, with equal spacing between the children. If there is only one child, it shall be aligned with the before edge only, as for Before. |
| [BlockAlign_Middle](#BlockAlign_Middle) | Attribute BlockAlign: Middle- Children centered within the table cell. The distance between the before edge of the first child's allocation rectangle and that of the table cell's content rectangle shall be the same as the distance between the after edge of the last child's allocation rectangle and that of the table cell's content rectangle. |
| [BorderStyle_Dashed](#BorderStyle_Dashed) | Attribute BorderStyle: Dashed - The border is a series of short line segments. |
| [BorderStyle_Dotted](#BorderStyle_Dotted) | Attribute BorderStyle: Dotted - The border is a series of dots. |
| [BorderStyle_Double](#BorderStyle_Double) | Attribute BorderStyle: Double - The border is two solid lines. The sum of the two lines and the space between them equals the value of BorderThickness. |
| [BorderStyle_Groove](#BorderStyle_Groove) | Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas. |
| [BorderStyle_Hidden](#BorderStyle_Hidden) | Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements. |
| [BorderStyle_Inset](#BorderStyle_Inset) | Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas. |
| [BorderStyle_None](#BorderStyle_None) | Attribute BorderStyle: None - No border. Forces the computed value of BorderThicknessto be 0. |
| [BorderStyle_Outset](#BorderStyle_Outset) | Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset). |
| [BorderStyle_Ridge](#BorderStyle_Ridge) | Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove). |
| [BorderStyle_Solid](#BorderStyle_Solid) | Attribute BorderStyle: Solid - The border is a single line segment. |
| [Checked_neutral](#Checked_neutral) | Attribute checked: Neutral - The state of a radio button or check box field. |
| [Checked_off](#Checked_off) | Attribute checked: Off - The state of a radio button or check box field. |
| [Checked_on](#Checked_on) | Attribute checked: On - The state of a radio button or check box field. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical_Auto) | Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high). |
| [Height_Auto](#Height_Auto) | Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content. |
| [InlineAlign_Center](#InlineAlign_Center) | Attribute InlineAlign: Center - Each child centered within the table cell. The distance between the start edges of the child's allocation rectangle and the table cell's content rectangle shall be the same as the distance between their end edges. |
| [InlineAlign_End](#InlineAlign_End) | Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [InlineAlign_Start](#InlineAlign_Start) | Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [LineHeight_Auto](#LineHeight_Auto) | Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made. |
| [LineHeight_Normal](#LineHeight_Normal) | Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift. |
| [ListNumbering_Circle](#ListNumbering_Circle) | Attribute ListNumbering: Circle - Open circular bullet. |
| [ListNumbering_Decimal](#ListNumbering_Decimal) | Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...). |
| [ListNumbering_Disc](#ListNumbering_Disc) | Attribute ListNumbering: Disc - Solid circular bullet. |
| [ListNumbering_LowerAlpha](#ListNumbering_LowerAlpha) | Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...). |
| [ListNumbering_LowerRoman](#ListNumbering_LowerRoman) | Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...). |
| [ListNumbering_None](#ListNumbering_None) | Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme. |
| [ListNumbering_Square](#ListNumbering_Square) | Attribute ListNumbering: Square - Solid square bullet. |
| [ListNumbering_UpperAlpha](#ListNumbering_UpperAlpha) | Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...). |
| [ListNumbering_UpperRoman](#ListNumbering_UpperRoman) | Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...). |
| [Placement_Before](#Placement_Before) | Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| [Placement_Block](#Placement_Block) | Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE. |
| [Placement_End](#Placement_End) | Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| [Placement_Inline](#Placement_Inline) | Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE. |
| [Placement_Start](#Placement_Start) | Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| [Role_cb](#Role_cb) | Attribute Role: cb - Check box. |
| [Role_pb](#Role_pb) | Attribute Role: pb - Push button. |
| [Role_rb](#Role_rb) | Attribute Role: rb - Radio button. |
| [Role_tv](#Role_tv) | Attribute Role: tv - Text-value field. |
| [RubyAlign_Center](#RubyAlign_Center) | Attribute RubyAlign: Center - The content shall be centered in the inline-progression direction. |
| [RubyAlign_Distribute](#RubyAlign_Distribute) | Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. However, space shall also be inserted at the start edge and end edge of the text . The spacing shall be distributed using a 1:2:1 (start:infix:end) ratio. It shall be changed to a 0:1:1 ratio if the ruby appears at the start of a text line or to a 1:1:0 ratio if the ruby appears at the end of the text line. |
| [RubyAlign_End](#RubyAlign_End) | Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction. |
| [RubyAlign_Justify](#RubyAlign_Justify) | Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction. |
| [RubyAlign_Start](#RubyAlign_Start) | Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction. |
| [RubyPosition_After](#RubyPosition_After) | Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element. |
| [RubyPosition_Before](#RubyPosition_Before) | Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element. |
| [RubyPosition_Inline](#RubyPosition_Inline) | Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element. |
| [RubyPosition_Warichu](#RubyPosition_Warichu) | Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element. |
| [Scope_Both](#Scope_Both) | Attribute Scope: Both. |
| [Scope_Column](#Scope_Column) | Attribute Scope: Column. |
| [Scope_Row](#Scope_Row) | Attribute Scope: Row. |
| [TextAlign_Center](#TextAlign_Center) | Attribute TextAlign: Center - Centered between the start and end edges. |
| [TextAlign_End](#TextAlign_End) | Attribute TextAlign: End - Aligned with the end edge. |
| [TextAlign_Justify](#TextAlign_Justify) | Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. The last (or only) line shall be aligned with the start edge only. |
| [TextAlign_Start](#TextAlign_Start) | Attribute TextAlign: Start - Aligned with the start edge. |
| [TextDecorationType_LineThrough](#TextDecorationType_LineThrough) | Attribute TextDecorationType: LineThrough - A line through the middle of the text. |
| [TextDecorationType_None](#TextDecorationType_None) | Attribute TextDecorationType: None - No text decoration. |
| [TextDecorationType_Overline](#TextDecorationType_Overline) | Attribute TextDecorationType: Overline - A line above the text. |
| [TextDecorationType_Underline](#TextDecorationType_Underline) | Attribute TextDecorationType: Underline - A line below the text. |
| [Width_Auto](#Width_Auto) | Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content. |
| [WritingMode_LrTb](#WritingMode_LrTb) | Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. This is the typical writing mode for Western writing systems. |
| [WritingMode_RlTb](#WritingMode_RlTb) | Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. This is the typical writing mode for Arabic and Hebrew writing systems. |
| [WritingMode_TbRl](#WritingMode_TbRl) | Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. This is the typical writing mode for Chinese and Japanese writing systems. |

## Methods

| Method | Description |
| --- | --- |
| [fromNameAttributeKey](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Gets attribute name for attribute key. |
| [getAttributeKey](#getAttributeKey--) | Gets attribute key. |
| [getName](#getName--) | Gets name value of attribute. |
| [toString](#toString--) | Returns a string that represents the current object. |

### BlockAlign_After {#BlockAlign_After}
```
public static final AttributeName BlockAlign_After
```

Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle.

### BlockAlign_Before {#BlockAlign_Before}
```
public static final AttributeName BlockAlign_Before
```

Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle.

### BlockAlign_Justify {#BlockAlign_Justify}
```
public static final AttributeName BlockAlign_Justify
```

Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. The first child shall be placed as described for Before and the last child as described for After, with equal spacing between the children. If there is only one child, it shall be aligned with the before edge only, as for Before.

### BlockAlign_Middle {#BlockAlign_Middle}
```
public static final AttributeName BlockAlign_Middle
```

Attribute BlockAlign: Middle- Children centered within the table cell. The distance between the before edge of the first child's allocation rectangle and that of the table cell's content rectangle shall be the same as the distance between the after edge of the last child's allocation rectangle and that of the table cell's content rectangle.

### BorderStyle_Dashed {#BorderStyle_Dashed}
```
public static final AttributeName BorderStyle_Dashed
```

Attribute BorderStyle: Dashed - The border is a series of short line segments.

### BorderStyle_Dotted {#BorderStyle_Dotted}
```
public static final AttributeName BorderStyle_Dotted
```

Attribute BorderStyle: Dotted - The border is a series of dots.

### BorderStyle_Double {#BorderStyle_Double}
```
public static final AttributeName BorderStyle_Double
```

Attribute BorderStyle: Double - The border is two solid lines. The sum of the two lines and the space between them equals the value of BorderThickness.

### BorderStyle_Groove {#BorderStyle_Groove}
```
public static final AttributeName BorderStyle_Groove
```

Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas.

### BorderStyle_Hidden {#BorderStyle_Hidden}
```
public static final AttributeName BorderStyle_Hidden
```

Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements.

### BorderStyle_Inset {#BorderStyle_Inset}
```
public static final AttributeName BorderStyle_Inset
```

Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas.

### BorderStyle_None {#BorderStyle_None}
```
public static final AttributeName BorderStyle_None
```

Attribute BorderStyle: None - No border. Forces the computed value of BorderThicknessto be 0.

### BorderStyle_Outset {#BorderStyle_Outset}
```
public static final AttributeName BorderStyle_Outset
```

Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset).

### BorderStyle_Ridge {#BorderStyle_Ridge}
```
public static final AttributeName BorderStyle_Ridge
```

Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove).

### BorderStyle_Solid {#BorderStyle_Solid}
```
public static final AttributeName BorderStyle_Solid
```

Attribute BorderStyle: Solid - The border is a single line segment.

### Checked_neutral {#Checked_neutral}
```
public static final AttributeName Checked_neutral
```

Attribute checked: Neutral - The state of a radio button or check box field.

### Checked_off {#Checked_off}
```
public static final AttributeName Checked_off
```

Attribute checked: Off - The state of a radio button or check box field.

### Checked_on {#Checked_on}
```
public static final AttributeName Checked_on
```

Attribute checked: On - The state of a radio button or check box field.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical_Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```

Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high).

### Height_Auto {#Height_Auto}
```
public static final AttributeName Height_Auto
```

Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content.

### InlineAlign_Center {#InlineAlign_Center}
```
public static final AttributeName InlineAlign_Center
```

Attribute InlineAlign: Center - Each child centered within the table cell. The distance between the start edges of the child's allocation rectangle and the table cell's content rectangle shall be the same as the distance between their end edges.

### InlineAlign_End {#InlineAlign_End}
```
public static final AttributeName InlineAlign_End
```

Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle.

### InlineAlign_Start {#InlineAlign_Start}
```
public static final AttributeName InlineAlign_Start
```

Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle.

### LineHeight_Auto {#LineHeight_Auto}
```
public static final AttributeName LineHeight_Auto
```

Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made.

### LineHeight_Normal {#LineHeight_Normal}
```
public static final AttributeName LineHeight_Normal
```

Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift.

### ListNumbering_Circle {#ListNumbering_Circle}
```
public static final AttributeName ListNumbering_Circle
```

Attribute ListNumbering: Circle - Open circular bullet.

### ListNumbering_Decimal {#ListNumbering_Decimal}
```
public static final AttributeName ListNumbering_Decimal
```

Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...).

### ListNumbering_Disc {#ListNumbering_Disc}
```
public static final AttributeName ListNumbering_Disc
```

Attribute ListNumbering: Disc - Solid circular bullet.

### ListNumbering_LowerAlpha {#ListNumbering_LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```

Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...).

### ListNumbering_LowerRoman {#ListNumbering_LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```

Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...).

### ListNumbering_None {#ListNumbering_None}
```
public static final AttributeName ListNumbering_None
```

Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme.

### ListNumbering_Square {#ListNumbering_Square}
```
public static final AttributeName ListNumbering_Square
```

Attribute ListNumbering: Square - Solid square bullet.

### ListNumbering_UpperAlpha {#ListNumbering_UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```

Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...).

### ListNumbering_UpperRoman {#ListNumbering_UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```

Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...).

### Placement_Before {#Placement_Before}
```
public static final AttributeName Placement_Before
```

Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.

### Placement_Block {#Placement_Block}
```
public static final AttributeName Placement_Block
```

Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE.

### Placement_End {#Placement_End}
```
public static final AttributeName Placement_End
```

Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.

### Placement_Inline {#Placement_Inline}
```
public static final AttributeName Placement_Inline
```

Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE.

### Placement_Start {#Placement_Start}
```
public static final AttributeName Placement_Start
```

Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.

### Role_cb {#Role_cb}
```
public static final AttributeName Role_cb
```

Attribute Role: cb - Check box.

### Role_pb {#Role_pb}
```
public static final AttributeName Role_pb
```

Attribute Role: pb - Push button.

### Role_rb {#Role_rb}
```
public static final AttributeName Role_rb
```

Attribute Role: rb - Radio button.

### Role_tv {#Role_tv}
```
public static final AttributeName Role_tv
```

Attribute Role: tv - Text-value field.

### RubyAlign_Center {#RubyAlign_Center}
```
public static final AttributeName RubyAlign_Center
```

Attribute RubyAlign: Center - The content shall be centered in the inline-progression direction.

### RubyAlign_Distribute {#RubyAlign_Distribute}
```
public static final AttributeName RubyAlign_Distribute
```

Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. However, space shall also be inserted at the start edge and end edge of the text . The spacing shall be distributed using a 1:2:1 (start:infix:end) ratio. It shall be changed to a 0:1:1 ratio if the ruby appears at the start of a text line or to a 1:1:0 ratio if the ruby appears at the end of the text line.

### RubyAlign_End {#RubyAlign_End}
```
public static final AttributeName RubyAlign_End
```

Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction.

### RubyAlign_Justify {#RubyAlign_Justify}
```
public static final AttributeName RubyAlign_Justify
```

Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction.

### RubyAlign_Start {#RubyAlign_Start}
```
public static final AttributeName RubyAlign_Start
```

Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction.

### RubyPosition_After {#RubyPosition_After}
```
public static final AttributeName RubyPosition_After
```

Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element.

### RubyPosition_Before {#RubyPosition_Before}
```
public static final AttributeName RubyPosition_Before
```

Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element.

### RubyPosition_Inline {#RubyPosition_Inline}
```
public static final AttributeName RubyPosition_Inline
```

Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element.

### RubyPosition_Warichu {#RubyPosition_Warichu}
```
public static final AttributeName RubyPosition_Warichu
```

Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element.

### Scope_Both {#Scope_Both}
```
public static final AttributeName Scope_Both
```

Attribute Scope: Both.

### Scope_Column {#Scope_Column}
```
public static final AttributeName Scope_Column
```

Attribute Scope: Column.

### Scope_Row {#Scope_Row}
```
public static final AttributeName Scope_Row
```

Attribute Scope: Row.

### TextAlign_Center {#TextAlign_Center}
```
public static final AttributeName TextAlign_Center
```

Attribute TextAlign: Center - Centered between the start and end edges.

### TextAlign_End {#TextAlign_End}
```
public static final AttributeName TextAlign_End
```

Attribute TextAlign: End - Aligned with the end edge.

### TextAlign_Justify {#TextAlign_Justify}
```
public static final AttributeName TextAlign_Justify
```

Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. The last (or only) line shall be aligned with the start edge only.

### TextAlign_Start {#TextAlign_Start}
```
public static final AttributeName TextAlign_Start
```

Attribute TextAlign: Start - Aligned with the start edge.

### TextDecorationType_LineThrough {#TextDecorationType_LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```

Attribute TextDecorationType: LineThrough - A line through the middle of the text.

### TextDecorationType_None {#TextDecorationType_None}
```
public static final AttributeName TextDecorationType_None
```

Attribute TextDecorationType: None - No text decoration.

### TextDecorationType_Overline {#TextDecorationType_Overline}
```
public static final AttributeName TextDecorationType_Overline
```

Attribute TextDecorationType: Overline - A line above the text.

### TextDecorationType_Underline {#TextDecorationType_Underline}
```
public static final AttributeName TextDecorationType_Underline
```

Attribute TextDecorationType: Underline - A line below the text.

### Width_Auto {#Width_Auto}
```
public static final AttributeName Width_Auto
```

Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content.

### WritingMode_LrTb {#WritingMode_LrTb}
```
public static final AttributeName WritingMode_LrTb
```

Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. This is the typical writing mode for Western writing systems.

### WritingMode_RlTb {#WritingMode_RlTb}
```
public static final AttributeName WritingMode_RlTb
```

Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. This is the typical writing mode for Arabic and Hebrew writing systems.

### WritingMode_TbRl {#WritingMode_TbRl}
```
public static final AttributeName WritingMode_TbRl
```

Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. This is the typical writing mode for Chinese and Japanese writing systems.

### fromNameAttributeKey {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
Gets attribute name for attribute key.

### getAttributeKey {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```

Gets attribute key.

**Returns:**
AttributeKey instance

### getName {#getName--}
```
public final String getName()
```

Gets name value of attribute.

**Returns:**
String value

### toString {#toString--}
```
public String toString()
```

Returns a string that represents the current object.

**Returns:**
String that represents the current object.
