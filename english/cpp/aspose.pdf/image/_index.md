---
title: Aspose::Pdf::Image class
linktitle: Image
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Image class. Represents image in C++.'
type: docs
weight: 6300
url: /cpp/aspose.pdf/image/
---
## Image class


Represents image.

```cpp
class Image : public Aspose::Pdf::BaseParagraph
```

## Methods

| Method | Description |
| --- | --- |
| [BaseParagraph](../baseparagraph/baseparagraph/)() |  |
| [Clone](./clone/)() override | Clone the image. |
| [get_BitmapInfo](./get_bitmapinfo/)() const | Gets uncompressed image bytes. |
| [get_BitmapSize](./get_bitmapsize/)() | Gets the image bitmap size. |
| [get_File](./get_file/)() const | Gets the image file. |
| [get_FileType](./get_filetype/)() const | Gets the image file type. |
| [get_FixHeight](./get_fixheight/)() const | Gets the image height. |
| [get_FixWidth](./get_fixwidth/)() const | Gets the image width. |
| virtual [get_HorizontalAlignment](../baseparagraph/get_horizontalalignment/)() | Gets a horizontal alignment of paragraph. |
| virtual [get_Hyperlink](../baseparagraph/get_hyperlink/)() | Gets the fragment hyperlink(for pdf generator). |
| [get_ImageScale](./get_imagescale/)() const | Gets the image scale. |
| [get_ImageStream](./get_imagestream/)() const | Gets the image stream. |
| [get_IsApplyResolution](./get_isapplyresolution/)() const | Gets a bool value that indicates whether the image use resolution during generation. |
| [get_IsBlackWhite](./get_isblackwhite/)() const | Gets a bool value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [get_IsFirstParagraphInColumn](../baseparagraph/get_isfirstparagraphincolumn/)() const | Gets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [get_IsInLineParagraph](../baseparagraph/get_isinlineparagraph/)() const | Gets a paragraph is inline. Default is false.(for pdf generation) |
| [get_IsInNewPage](../baseparagraph/get_isinnewpage/)() const | Gets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [get_IsKeptWithNext](../baseparagraph/get_iskeptwithnext/)() const | Gets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [get_Margin](../baseparagraph/get_margin/)() | Gets a outer margin for paragraph (for pdf generation) |
| [get_Title](./get_title/)() const | Gets a string value that indicates the title of the image. |
| virtual [get_VerticalAlignment](../baseparagraph/get_verticalalignment/)() | Gets a vertical alignment of paragraph. |
| [get_ZIndex](../baseparagraph/get_zindex/)() const | Gets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
| static [GetMimeType](./getmimetype/)(System::SharedPtr\<System::Drawing::Image\>) | Returns mime type for image. |
| [Image](./image/)() |  |
| [set_BitmapInfo](./set_bitmapinfo/)(System::SharedPtr\<Aspose::Pdf::BitmapInfo\>) | Sets uncompressed image bytes. |
| [set_File](./set_file/)(System::String) | Sets the image file. |
| [set_FileType](./set_filetype/)(ImageFileType) | Sets the image file type. |
| [set_FixHeight](./set_fixheight/)(double) | Sets the image height. |
| [set_FixWidth](./set_fixwidth/)(double) | Sets the image width. |
| virtual [set_HorizontalAlignment](../baseparagraph/set_horizontalalignment/)(Aspose::Pdf::HorizontalAlignment) | Sets a horizontal alignment of paragraph. |
| virtual [set_Hyperlink](../baseparagraph/set_hyperlink/)(System::SharedPtr\<Aspose::Pdf::Hyperlink\>) | Sets the fragment hyperlink(for pdf generator). |
| [set_ImageScale](./set_imagescale/)(double) | Sets the image scale. |
| [set_ImageStream](./set_imagestream/)(System::SharedPtr\<System::IO::Stream\>) | Sets the image stream. |
| [set_IsApplyResolution](./set_isapplyresolution/)(bool) | Sets a bool value that indicates whether the image use resolution during generation. |
| [set_IsBlackWhite](./set_isblackwhite/)(bool) | Sets a bool value that indicates whether the image is forced to be black-and-white. If TIFF image of CCITT subformat is used, this property must be set to true. |
| [set_IsFirstParagraphInColumn](../baseparagraph/set_isfirstparagraphincolumn/)(bool) | Sets a bool value that indicates whether this paragraph will be at next column. Default is false.(for pdf generation) |
| [set_IsInLineParagraph](../baseparagraph/set_isinlineparagraph/)(bool) | Sets a paragraph is inline. Default is false.(for pdf generation) |
| [set_IsInNewPage](../baseparagraph/set_isinnewpage/)(bool) | Sets a bool value that force this paragraph generates at new page. Default is false.(for pdf generation) |
| [set_IsKeptWithNext](../baseparagraph/set_iskeptwithnext/)(bool) | Sets a bool value that indicates whether current paragraph remains in the same page along with next paragraph. Default is false.(for pdf generation) |
| [set_Margin](../baseparagraph/set_margin/)(System::SharedPtr\<MarginInfo\>) | Sets a outer margin for paragraph (for pdf generation) |
| [set_Title](./set_title/)(System::SharedPtr\<Text::TextFragment\>) | Sets a string value that indicates the title of the image. |
| virtual [set_VerticalAlignment](../baseparagraph/set_verticalalignment/)(Aspose::Pdf::VerticalAlignment) | Sets a vertical alignment of paragraph. |
| [set_ZIndex](../baseparagraph/set_zindex/)(int32_t) | Sets a int value that indicates the Z-order of the graph. A graph with larger ZIndex will be placed over the graph with smaller ZIndex. ZIndex can be negative. Graph with negative ZIndex will be placed behind the text in the page. |
## See Also

* Class [BaseParagraph](../baseparagraph/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
