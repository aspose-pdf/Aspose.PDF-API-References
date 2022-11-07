---
title: AttributeName
second_title: Aspose.PDF for Java API Reference
description: Represents class for Attribute Name Values.
type: docs
weight: 11
url: /java/com.aspose.pdf.tagged.logicalstructure/attributename/
---
**Inheritance:**
java.lang.Object
```
public final class AttributeName
```

Represents class for Attribute Name Values.
## Fields

| Field | Description |
| --- | --- |
| [Placement_Block](#Placement-Block) | Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE. |
| [Placement_Inline](#Placement-Inline) | Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE. |
| [Placement_Before](#Placement-Before) | Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| [Placement_Start](#Placement-Start) | Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| [Placement_End](#Placement-End) | Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area. |
| [WritingMode_LrTb](#WritingMode-LrTb) | Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. |
| [WritingMode_RlTb](#WritingMode-RlTb) | Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. |
| [WritingMode_TbRl](#WritingMode-TbRl) | Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. |
| [BorderStyle_None](#BorderStyle-None) | Attribute BorderStyle: None - No border. |
| [BorderStyle_Hidden](#BorderStyle-Hidden) | Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements. |
| [BorderStyle_Dotted](#BorderStyle-Dotted) | Attribute BorderStyle: Dotted - The border is a series of dots. |
| [BorderStyle_Dashed](#BorderStyle-Dashed) | Attribute BorderStyle: Dashed - The border is a series of short line segments. |
| [BorderStyle_Solid](#BorderStyle-Solid) | Attribute BorderStyle: Solid - The border is a single line segment. |
| [BorderStyle_Double](#BorderStyle-Double) | Attribute BorderStyle: Double - The border is two solid lines. |
| [BorderStyle_Groove](#BorderStyle-Groove) | Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas. |
| [BorderStyle_Ridge](#BorderStyle-Ridge) | Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove). |
| [BorderStyle_Inset](#BorderStyle-Inset) | Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas. |
| [BorderStyle_Outset](#BorderStyle-Outset) | Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset). |
| [TextAlign_Start](#TextAlign-Start) | Attribute TextAlign: Start - Aligned with the start edge. |
| [TextAlign_Center](#TextAlign-Center) | Attribute TextAlign: Center - Centered between the start and end edges. |
| [TextAlign_End](#TextAlign-End) | Attribute TextAlign: End - Aligned with the end edge. |
| [TextAlign_Justify](#TextAlign-Justify) | Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. |
| [Width_Auto](#Width-Auto) | Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content. |
| [Height_Auto](#Height-Auto) | Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content. |
| [BlockAlign_Before](#BlockAlign-Before) | Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [BlockAlign_Middle](#BlockAlign-Middle) | Attribute BlockAlign: Middle- Children centered within the table cell. |
| [BlockAlign_After](#BlockAlign-After) | Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [BlockAlign_Justify](#BlockAlign-Justify) | Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. |
| [InlineAlign_Start](#InlineAlign-Start) | Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [InlineAlign_Center](#InlineAlign-Center) | Attribute InlineAlign: Center - Each child centered within the table cell. |
| [InlineAlign_End](#InlineAlign-End) | Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle. |
| [LineHeight_Normal](#LineHeight-Normal) | Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift. |
| [LineHeight_Auto](#LineHeight-Auto) | Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made. |
| [TextDecorationType_None](#TextDecorationType-None) | Attribute TextDecorationType: None - No text decoration. |
| [TextDecorationType_Underline](#TextDecorationType-Underline) | Attribute TextDecorationType: Underline - A line below the text. |
| [TextDecorationType_Overline](#TextDecorationType-Overline) | Attribute TextDecorationType: Overline - A line above the text. |
| [TextDecorationType_LineThrough](#TextDecorationType-LineThrough) | Attribute TextDecorationType: LineThrough - A line through the middle of the text. |
| [RubyAlign_Start](#RubyAlign-Start) | Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction. |
| [RubyAlign_Center](#RubyAlign-Center) | Attribute RubyAlign: Center - The content shall be centered in the inline-progression direction. |
| [RubyAlign_End](#RubyAlign-End) | Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction. |
| [RubyAlign_Justify](#RubyAlign-Justify) | Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction. |
| [RubyAlign_Distribute](#RubyAlign-Distribute) | Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. |
| [RubyPosition_Before](#RubyPosition-Before) | Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element. |
| [RubyPosition_After](#RubyPosition-After) | Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element. |
| [RubyPosition_Warichu](#RubyPosition-Warichu) | Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element. |
| [RubyPosition_Inline](#RubyPosition-Inline) | Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element. |
| [GlyphOrientationVertical_Auto](#GlyphOrientationVertical-Auto) | Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high). |
| [ListNumbering_None](#ListNumbering-None) | Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme. |
| [ListNumbering_Disc](#ListNumbering-Disc) | Attribute ListNumbering: Disc - Solid circular bullet. |
| [ListNumbering_Circle](#ListNumbering-Circle) | Attribute ListNumbering: Circle - Open circular bullet. |
| [ListNumbering_Square](#ListNumbering-Square) | Attribute ListNumbering: Square - Solid square bullet. |
| [ListNumbering_Decimal](#ListNumbering-Decimal) | Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...). |
| [ListNumbering_UpperRoman](#ListNumbering-UpperRoman) | Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...). |
| [ListNumbering_LowerRoman](#ListNumbering-LowerRoman) | Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...). |
| [ListNumbering_UpperAlpha](#ListNumbering-UpperAlpha) | Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...). |
| [ListNumbering_LowerAlpha](#ListNumbering-LowerAlpha) | Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...). |
| [Role_rb](#Role-rb) | Attribute Role: rb - Radio button. |
| [Role_cb](#Role-cb) | Attribute Role: cb - Check box. |
| [Role_pb](#Role-pb) | Attribute Role: pb - Push button. |
| [Role_tv](#Role-tv) | Attribute Role: tv - Text-value field. |
| [Checked_on](#Checked-on) | Attribute checked: On - The state of a radio button or check box field. |
| [Checked_off](#Checked-off) | Attribute checked: Off - The state of a radio button or check box field. |
| [Checked_neutral](#Checked-neutral) | Attribute checked: Neutral - The state of a radio button or check box field. |
| [Scope_Row](#Scope-Row) | Attribute Scope: Row. |
| [Scope_Column](#Scope-Column) | Attribute Scope: Column. |
| [Scope_Both](#Scope-Both) | Attribute Scope: Both. |
## Methods

| Method | Description |
| --- | --- |
| [getName()](#getName--) | Gets name value of attribute. |
| [getAttributeKey()](#getAttributeKey--) | Gets attribute key. |
| [fromNameAttributeKey(String name, AttributeKey attributeKey)](#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Gets attribute name for attribute key. |
| [toString()](#toString--) | Returns a string that represents the current object. |
### Placement_Block {#Placement-Block}
```
public static final AttributeName Placement_Block
```


Attribute Placement: Block - Stacked in the block-progression direction within an enclosing reference area or parent BLSE.

### Placement_Inline {#Placement-Inline}
```
public static final AttributeName Placement_Inline
```


Attribute Placement: Inline - Packed in the inline-progression direction within an enclosing BLSE.

### Placement_Before {#Placement-Before}
```
public static final AttributeName Placement_Before
```


Attribute Placement: Before - Placed so that the before edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.

### Placement_Start {#Placement-Start}
```
public static final AttributeName Placement_Start
```


Attribute Placement: Start - Placed so that the start edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.

### Placement_End {#Placement-End}
```
public static final AttributeName Placement_End
```


Attribute Placement: End - Placed so that the end edge of the element's allocation rectangle coincides with that of the nearest enclosing reference area.

### WritingMode_LrTb {#WritingMode-LrTb}
```
public static final AttributeName WritingMode_LrTb
```


Attribute WritingMode: LrTb - Inline progression from left to right; block progression from top to bottom. This is the typical writing mode for Western writing systems.

### WritingMode_RlTb {#WritingMode-RlTb}
```
public static final AttributeName WritingMode_RlTb
```


Attribute WritingMode: RlTb - Inline progression from right to left; block progression from top to bottom. This is the typical writing mode for Arabic and Hebrew writing systems.

### WritingMode_TbRl {#WritingMode-TbRl}
```
public static final AttributeName WritingMode_TbRl
```


Attribute WritingMode: TbRl - Inline progression from top to bottom; block progression from right to left. This is the typical writing mode for Chinese and Japanese writing systems.

### BorderStyle_None {#BorderStyle-None}
```
public static final AttributeName BorderStyle_None
```


Attribute BorderStyle: None - No border. Forces the computed value of BorderThicknessto be 0.

### BorderStyle_Hidden {#BorderStyle-Hidden}
```
public static final AttributeName BorderStyle_Hidden
```


Attribute BorderStyle: Hidden - Same as None, except in terms of border conflict resolution for table elements.

### BorderStyle_Dotted {#BorderStyle-Dotted}
```
public static final AttributeName BorderStyle_Dotted
```


Attribute BorderStyle: Dotted - The border is a series of dots.

### BorderStyle_Dashed {#BorderStyle-Dashed}
```
public static final AttributeName BorderStyle_Dashed
```


Attribute BorderStyle: Dashed - The border is a series of short line segments.

### BorderStyle_Solid {#BorderStyle-Solid}
```
public static final AttributeName BorderStyle_Solid
```


Attribute BorderStyle: Solid - The border is a single line segment.

### BorderStyle_Double {#BorderStyle-Double}
```
public static final AttributeName BorderStyle_Double
```


Attribute BorderStyle: Double - The border is two solid lines. The sum of the two lines and the space between them equals the value of BorderThickness.

### BorderStyle_Groove {#BorderStyle-Groove}
```
public static final AttributeName BorderStyle_Groove
```


Attribute BorderStyle: Groove - The border looks as though it were carved into the canvas.

### BorderStyle_Ridge {#BorderStyle-Ridge}
```
public static final AttributeName BorderStyle_Ridge
```


Attribute BorderStyle: Ridge - The border looks as though it were coming out of the canvas (the opposite of Groove).

### BorderStyle_Inset {#BorderStyle-Inset}
```
public static final AttributeName BorderStyle_Inset
```


Attribute BorderStyle: Inset - The border makes the entire box look as though it were embedded in the canvas.

### BorderStyle_Outset {#BorderStyle-Outset}
```
public static final AttributeName BorderStyle_Outset
```


Attribute BorderStyle: Outset - The border makes the entire box look as though it were coming out of the canvas (the opposite of Inset).

### TextAlign_Start {#TextAlign-Start}
```
public static final AttributeName TextAlign_Start
```


Attribute TextAlign: Start - Aligned with the start edge.

### TextAlign_Center {#TextAlign-Center}
```
public static final AttributeName TextAlign_Center
```


Attribute TextAlign: Center - Centered between the start and end edges.

### TextAlign_End {#TextAlign-End}
```
public static final AttributeName TextAlign_End
```


Attribute TextAlign: End - Aligned with the end edge.

### TextAlign_Justify {#TextAlign-Justify}
```
public static final AttributeName TextAlign_Justify
```


Attribute TextAlign: Justify - Aligned with both the start and end edges, with internal spacing within each line expanded, if necessary, to achieve such alignment. The last (or only) line shall be aligned with the start edge only.

### Width_Auto {#Width-Auto}
```
public static final AttributeName Width_Auto
```


Attribute Width: Auto - the element's width shall be determined by the intrinsic width of its content.

### Height_Auto {#Height-Auto}
```
public static final AttributeName Height_Auto
```


Attribute Height: Auto - The element's height shall be determined by the intrinsic height of its content.

### BlockAlign_Before {#BlockAlign-Before}
```
public static final AttributeName BlockAlign_Before
```


Attribute BlockAlign: Before - Before edge of the first child's allocation rectangle aligned with that of the table cell's content rectangle.

### BlockAlign_Middle {#BlockAlign-Middle}
```
public static final AttributeName BlockAlign_Middle
```


Attribute BlockAlign: Middle- Children centered within the table cell. The distance between the before edge of the first child's allocation rectangle and that of the table cell's content rectangle shall be the same as the distance between the after edge of the last child's allocation rectangle and that of the table cell's content rectangle.

### BlockAlign_After {#BlockAlign-After}
```
public static final AttributeName BlockAlign_After
```


Attribute BlockAlign: After - After edge of the last child's allocation rectangle aligned with that of the table cell's content rectangle.

### BlockAlign_Justify {#BlockAlign-Justify}
```
public static final AttributeName BlockAlign_Justify
```


Attribute BlockAlign: Justify - Children aligned with both the before and after edges of the table cell's content rectangle. The first child shall be placed as described for Before and the last child as described for After, with equal spacing between the children. If there is only one child, it shall be aligned with the before edge only, as for Before.

### InlineAlign_Start {#InlineAlign-Start}
```
public static final AttributeName InlineAlign_Start
```


Attribute InlineAlign: Start - Start edge of each child's allocation rectangle aligned with that of the table cell's content rectangle.

### InlineAlign_Center {#InlineAlign-Center}
```
public static final AttributeName InlineAlign_Center
```


Attribute InlineAlign: Center - Each child centered within the table cell. The distance between the start edges of the child's allocation rectangle and the table cell's content rectangle shall be the same as the distance between their end edges.

### InlineAlign_End {#InlineAlign-End}
```
public static final AttributeName InlineAlign_End
```


Attribute InlineAlign: End - End edge of each child's allocation rectangle aligned with that of the table cell's content rectangle.

### LineHeight_Normal {#LineHeight-Normal}
```
public static final AttributeName LineHeight_Normal
```


Attribute LineHeight: Normal - Adjust the line height to include any nonzero value specified for BaselineShift.

### LineHeight_Auto {#LineHeight-Auto}
```
public static final AttributeName LineHeight_Auto
```


Attribute LineHeight: Auto - Adjustment for the value of BaselineShift shall not be made.

### TextDecorationType_None {#TextDecorationType-None}
```
public static final AttributeName TextDecorationType_None
```


Attribute TextDecorationType: None - No text decoration.

### TextDecorationType_Underline {#TextDecorationType-Underline}
```
public static final AttributeName TextDecorationType_Underline
```


Attribute TextDecorationType: Underline - A line below the text.

### TextDecorationType_Overline {#TextDecorationType-Overline}
```
public static final AttributeName TextDecorationType_Overline
```


Attribute TextDecorationType: Overline - A line above the text.

### TextDecorationType_LineThrough {#TextDecorationType-LineThrough}
```
public static final AttributeName TextDecorationType_LineThrough
```


Attribute TextDecorationType: LineThrough - A line through the middle of the text.

### RubyAlign_Start {#RubyAlign-Start}
```
public static final AttributeName RubyAlign_Start
```


Attribute RubyAlign: Start - The content shall be aligned on the start edge in the inline-progression direction.

### RubyAlign_Center {#RubyAlign-Center}
```
public static final AttributeName RubyAlign_Center
```


Attribute RubyAlign: Center - The content shall be centered in the inline-progression direction.

### RubyAlign_End {#RubyAlign-End}
```
public static final AttributeName RubyAlign_End
```


Attribute RubyAlign: End - The content shall be aligned on the end edge in the inline-progression direction.

### RubyAlign_Justify {#RubyAlign-Justify}
```
public static final AttributeName RubyAlign_Justify
```


Attribute RubyAlign: Justify - The content shall be expanded to fill the available width in the inline-progression direction.

### RubyAlign_Distribute {#RubyAlign-Distribute}
```
public static final AttributeName RubyAlign_Distribute
```


Attribute RubyAlign: Distribute - The content shall be expanded to fill the available width in the inline-progression direction. However, space shall also be inserted at the start edge and end edge of the text . The spacing shall be distributed using a 1:2:1 (start:infix:end) ratio. It shall be changed to a 0:1:1 ratio if the ruby appears at the start of a text line or to a 1:1:0 ratio if the ruby appears at the end of the text line.

### RubyPosition_Before {#RubyPosition-Before}
```
public static final AttributeName RubyPosition_Before
```


Attribute RubyPosition: Before - The RT content shall be aligned along the before edge of the element.

### RubyPosition_After {#RubyPosition-After}
```
public static final AttributeName RubyPosition_After
```


Attribute RubyPosition: After - The RT content shall be aligned along the after edge of the element.

### RubyPosition_Warichu {#RubyPosition-Warichu}
```
public static final AttributeName RubyPosition_Warichu
```


Attribute RubyPosition: Warichu - The RT and associated RP elements shall be formatted as a warichu, following the RB element.

### RubyPosition_Inline {#RubyPosition-Inline}
```
public static final AttributeName RubyPosition_Inline
```


Attribute RubyPosition: Inline - The RT and associated RP elements shall be formatted as a parenthesis comment, following the RB element.

### GlyphOrientationVertical_Auto {#GlyphOrientationVertical-Auto}
```
public static final AttributeName GlyphOrientationVertical_Auto
```


Attribute GlyphOrientationVertical: Auto - Specifies a default orientation for text, depending on whether it is fullwidth (as wide as it is high).

### ListNumbering_None {#ListNumbering-None}
```
public static final AttributeName ListNumbering_None
```


Attribute ListNumbering: None - No autonumbering; Lbl elements (if present) contain arbitrary text not subject to any numbering scheme.

### ListNumbering_Disc {#ListNumbering-Disc}
```
public static final AttributeName ListNumbering_Disc
```


Attribute ListNumbering: Disc - Solid circular bullet.

### ListNumbering_Circle {#ListNumbering-Circle}
```
public static final AttributeName ListNumbering_Circle
```


Attribute ListNumbering: Circle - Open circular bullet.

### ListNumbering_Square {#ListNumbering-Square}
```
public static final AttributeName ListNumbering_Square
```


Attribute ListNumbering: Square - Solid square bullet.

### ListNumbering_Decimal {#ListNumbering-Decimal}
```
public static final AttributeName ListNumbering_Decimal
```


Attribute ListNumbering: Decimal - Decimal arabic numerals (1-9, 10-99, ...).

### ListNumbering_UpperRoman {#ListNumbering-UpperRoman}
```
public static final AttributeName ListNumbering_UpperRoman
```


Attribute ListNumbering: UpperRoman - Uppercase roman numerals (I, II, III, IV, ...).

### ListNumbering_LowerRoman {#ListNumbering-LowerRoman}
```
public static final AttributeName ListNumbering_LowerRoman
```


Attribute ListNumbering: LowerRoman - Lowercase roman numerals (i, ii, iii, iv, ...).

### ListNumbering_UpperAlpha {#ListNumbering-UpperAlpha}
```
public static final AttributeName ListNumbering_UpperAlpha
```


Attribute ListNumbering: UpperAlpha - Uppercase letters (A, B, C, ...).

### ListNumbering_LowerAlpha {#ListNumbering-LowerAlpha}
```
public static final AttributeName ListNumbering_LowerAlpha
```


Attribute ListNumbering: LowerAlpha - Lowercase letters (a, b, c, ...).

### Role_rb {#Role-rb}
```
public static final AttributeName Role_rb
```


Attribute Role: rb - Radio button.

### Role_cb {#Role-cb}
```
public static final AttributeName Role_cb
```


Attribute Role: cb - Check box.

### Role_pb {#Role-pb}
```
public static final AttributeName Role_pb
```


Attribute Role: pb - Push button.

### Role_tv {#Role-tv}
```
public static final AttributeName Role_tv
```


Attribute Role: tv - Text-value field.

### Checked_on {#Checked-on}
```
public static final AttributeName Checked_on
```


Attribute checked: On - The state of a radio button or check box field.

### Checked_off {#Checked-off}
```
public static final AttributeName Checked_off
```


Attribute checked: Off - The state of a radio button or check box field.

### Checked_neutral {#Checked-neutral}
```
public static final AttributeName Checked_neutral
```


Attribute checked: Neutral - The state of a radio button or check box field.

### Scope_Row {#Scope-Row}
```
public static final AttributeName Scope_Row
```


Attribute Scope: Row.

### Scope_Column {#Scope-Column}
```
public static final AttributeName Scope_Column
```


Attribute Scope: Column.

### Scope_Both {#Scope-Both}
```
public static final AttributeName Scope_Both
```


Attribute Scope: Both.

### getName() {#getName--}
```
public final String getName()
```


Gets name value of attribute.

**Returns:**
java.lang.String - String value
### getAttributeKey() {#getAttributeKey--}
```
public final AttributeKey getAttributeKey()
```


Gets attribute key.

**Returns:**
[AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) - AttributeKey instance
### fromNameAttributeKey(String name, AttributeKey attributeKey) {#fromNameAttributeKey-java.lang.String-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public static AttributeName fromNameAttributeKey(String name, AttributeKey attributeKey)
```


Gets attribute name for attribute key.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Attribute name |
| attributeKey | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) | Attribute key |

**Returns:**
[AttributeName](../../com.aspose.pdf.tagged.logicalstructure/attributename) - Attribute name
### toString() {#toString--}
```
public String toString()
```


Returns a string that represents the current object.

**Returns:**
java.lang.String - String that represents the current object.
