---
title: Aspose::Pdf::Text::TextExtractionErrorLocation class
linktitle: TextExtractionErrorLocation
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextExtractionErrorLocation class. Represents the location in the PDF document where text extraction error has appeared in C++.'
type: docs
weight: 4000
url: /cpp/aspose.pdf.text/textextractionerrorlocation/
---
## TextExtractionErrorLocation class


Represents the location in the PDF document where text extraction error has appeared.

```cpp
class TextExtractionErrorLocation : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_FontUsedKey](./get_fontusedkey/)() const | Key (name) of the PDF [Font](../font/) object that is used for showing of the operator that causes text extraction error. |
| [get_FormKey](./get_formkey/)() const | Key (name) of the PDF Form XObject in which contents stream text extraction error has located. Not empty if ObjectType == 'xForm'. |
| [get_ObjectType](./get_objecttype/)() const | Type of the PDF object ([Page](../../aspose.pdf/page/) or xForm) in which contents stream text extraction error has located. |
| [get_OperatorIndex](./get_operatorindex/)() const | Index of text showing operator in the contents stream (operator collection) that causes text extraction error. |
| [get_OperatorString](./get_operatorstring/)() const | [Text](../) showing operator that causes text extraction error. |
| [get_PageNumber](./get_pagenumber/)() const | Number of the document page where text extraction error has located. |
| [get_Path](./get_path/)() const | Location of the PDF document where text extraction error has appeared. |
| [get_TextStartPoint](./get_textstartpoint/)() const | Key (name) of the PDF [Font](../font/) object that is used for showing of the operator that causes text extraction error. |
| [ToString](./tostring/)() const override | Returns string representation. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
