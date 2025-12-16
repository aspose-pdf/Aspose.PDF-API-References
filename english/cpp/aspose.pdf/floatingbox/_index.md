---
title: Aspose::Pdf::FloatingBox class
linktitle: FloatingBox
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::FloatingBox class. Represents a FloatingBox in a Pdf document. FloatingBox is custom positioned in C++.'
type: docs
weight: 5900
url: /cpp/aspose.pdf/floatingbox/
---
## FloatingBox class


Represents a [FloatingBox](./) in a [Pdf](../) document. [FloatingBox](./) is custom positioned.

```cpp
class FloatingBox : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [Clone](./clone/)() override | Clones a new [FloatingBox](./) object. [Paragraphs](../paragraphs/) in the floating box are not cloned. |
| [FloatingBox](./floatingbox/)(float, float) | Initializes a new instance of the [FloatingBox](./) class with specified width and height. |
| [FloatingBox](./floatingbox/)() | Initializes a new instance of the [FloatingBox](./) class. |
| [get_BackgroundColor](./get_backgroundcolor/)() const | Gets a [Aspose::Pdf::Color](../color/) object that indicates the background color of the floating box. |
| [get_BackgroundImage](./get_backgroundimage/)() const | Gets background image for page (for generator only, not filled in when reading document). |
| [get_Border](./get_border/)() const | Gets a [BorderInfo](../borderinfo/) object that indicates the border info of the floating box. |
| [get_ColumnInfo](./get_columninfo/)() const | Gets a column info. |
| [get_Height](./get_height/)() const | Gets a float value that indicates the height of the floating box. |
| [get_IsNeedRepeating](./get_isneedrepeating/)() const | Gets a bool value that indicates whether the paragraph need to be repeated on next page. Default value is false.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [get_Left](./get_left/)() const | Gets the table left coordinate. |
| [get_Padding](./get_padding/)() const | Gets a [MarginInfo](../margininfo/) object that indicates the padding of the floating box. |
| [get_Paragraphs](./get_paragraphs/)() const | Gets a [Paragraphs](../paragraphs/) collection that indicates all paragraphs in the cell. |
| [get_PositioningMode](./get_positioningmode/)() const | Specifies variant for determining the location of the [FloatingBox](./) on the page. |
| [get_Top](./get_top/)() const | Gets the table top coordinate. |
| [get_Width](./get_width/)() const | Gets a float value that indicates the width of the floating box. |
| [set_BackgroundColor](./set_backgroundcolor/)(System::SharedPtr\<Color\>) | Sets a [Aspose::Pdf::Color](../color/) object that indicates the background color of the floating box. |
| [set_BackgroundImage](./set_backgroundimage/)(System::SharedPtr\<Image\>) | Sets background image for page (for generator only, not filled in when reading document). |
| [set_Border](./set_border/)(System::SharedPtr\<BorderInfo\>) | Sets a [BorderInfo](../borderinfo/) object that indicates the border info of the floating box. |
| [set_ColumnInfo](./set_columninfo/)(System::SharedPtr\<Aspose::Pdf::ColumnInfo\>) | Sets a column info. |
| [set_Height](./set_height/)(double) | Sets a float value that indicates the height of the floating box. |
| [set_IsNeedRepeating](./set_isneedrepeating/)(bool) | Sets a bool value that indicates whether the paragraph need to be repeated on next page. Default value is false.The attribute is only valid when the paragraph itself and the object its ReferenceParagraphID referred to both are included in RepeatingRows. |
| [set_Left](./set_left/)(double) | Sets the table left coordinate. |
| [set_Padding](./set_padding/)(System::SharedPtr\<MarginInfo\>) | Sets a [MarginInfo](../margininfo/) object that indicates the padding of the floating box. |
| [set_Paragraphs](./set_paragraphs/)(System::SharedPtr\<Aspose::Pdf::Paragraphs\>) | Sets a [Paragraphs](../paragraphs/) collection that indicates all paragraphs in the cell. |
| [set_PositioningMode](./set_positioningmode/)(ParagraphPositioningMode) | Specifies variant for determining the location of the [FloatingBox](./) on the page. |
| [set_Top](./set_top/)(double) | Sets the table top coordinate. |
| [set_Width](./set_width/)(double) | Sets a float value that indicates the width of the floating box. |
## See Also

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
