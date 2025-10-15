---
title: Aspose::Pdf::Facades::Stamp class
linktitle: Stamp
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Stamp class. Class represeting stamp in C++.'
type: docs
weight: 3500
url: /cpp/aspose.pdf.facades/stamp/
---
## Stamp class


Class represeting stamp.

```cpp
class Stamp : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [BindImage](./bindimage/)(System::String) | Sets image as a stamp. |
| [BindImage](./bindimage/)(System::SharedPtr\<System::IO::Stream\>) | Sets image which will be used as stamp. |
| [BindLogo](./bindlogo/)(System::SharedPtr\<FormattedText\>) | Sets text as stamp. |
| [BindPdf](./bindpdf/)(System::String, int32_t) | Sets PDF file and number of page which will be used as stamp. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>, int32_t) | Sets PDF file and number of page which will be used as stamp. |
| [BindTextState](./bindtextstate/)(System::SharedPtr\<Text::TextState\>) | Sets text state of stamp text. |
| [get_BlendingSpace](./get_blendingspace/)() const | Gets a [BlendingColorSpace](../blendingcolorspace/) value that defines a color space that is used to perform transparency and blending operations on the page. |
| [get_IsBackground](./get_isbackground/)() const | Gets background status. If true stamp will be placed as background of the spamped page. By default is set to false. |
| [get_Opacity](./get_opacity/)() | Gets opacity of the stamp. |
| [get_PageNumber](./get_pagenumber/)() const | Gets page number. |
| [get_Pages](./get_pages/)() const | Gets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected. |
| [get_Quality](./get_quality/)() const | Gets quality of image stamp in percent. Valiued values 0..100%. |
| [get_Rotation](./get_rotation/)() const | Gets rotation of the stamp in degrees. |
| [get_StampId](./get_stampid/)() const | Gets identifier of stamp. |
| [set_BlendingSpace](./set_blendingspace/)(BlendingColorSpace) | Sets a [BlendingColorSpace](../blendingcolorspace/) value that defines a color space that is used to perform transparency and blending operations on the page. |
| [set_IsBackground](./set_isbackground/)(bool) | Sets background status. If true stamp will be placed as background of the spamped page. By default is set to false. |
| [set_Opacity](./set_opacity/)(float) | Sets opacity of the stamp. |
| [set_PageNumber](./set_pagenumber/)(int32_t) | Sets page number. |
| [set_Pages](./set_pages/)(System::ArrayPtr\<int32_t\>) | Sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected. |
| [set_Quality](./set_quality/)(int32_t) | Sets quality of image stamp in percent. Valiued values 0..100%. |
| [set_Rotation](./set_rotation/)(float) | Sets rotation of the stamp in degrees. |
| [set_StampId](./set_stampid/)(int32_t) | Sets identifier of stamp. |
| [SetImageSize](./setimagesize/)(float, float) | Sets size of image stamp. [Image](../../aspose.pdf/image/) will be scaled according to the specified values. |
| [SetOrigin](./setorigin/)(float, float) | Sets position on page where stamp will be placed. |
| [Stamp](./stamp/)() | Constructor for [Stamp](./) object. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
