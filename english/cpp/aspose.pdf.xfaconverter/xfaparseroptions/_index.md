---
title: Aspose::Pdf::XfaConverter::XfaParserOptions class
linktitle: XfaParserOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::XfaConverter::XfaParserOptions class. class to handle related data incapsulation in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.xfaconverter/xfaparseroptions/
---
## XfaParserOptions class


class to handle related data incapsulation

```cpp
class XfaParserOptions : public System::Object
```

## Methods

| Method | Description |
| --- | --- |
| [get_BasePath](./get_basepath/)() const | Gets the base path. |
| [get_EmulateRequierdGroups](./get_emulaterequierdgroups/)() const | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogues of excluded groups during conversion Xfa representation of forms to standard. It is false by default. |
| [get_PageSize](./get_pagesize/)() const | Gets the size of the page. |
| [get_Signed](./get_signed/)() const | If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature. |
| [get_UriResolver](./get_uriresolver/)() const | Gets the URI resolver. |
| [set_BasePath](./set_basepath/)(System::SharedPtr\<System::Uri\>) | Sets the base path. |
| [set_EmulateRequierdGroups](./set_emulaterequierdgroups/)(bool) | If this property is true then additional red rectangles will be drawn for required Xfa "excluded groups" This property was introduced because absences of analogues of excluded groups during conversion Xfa representation of forms to standard. It is false by default. |
| [set_PageSize](./set_pagesize/)(System::Drawing::SizeF) | Sets the size of the page. |
| [set_Signed](./set_signed/)(bool) | If this property is true then document will be converted with using of xfa form stream (if it exists). If it is false then xfa form stream will be ignored. This property was inrtoduced because it's not clear how to calculate check sum that used for checking sygnature. |
| [set_UriResolver](./set_uriresolver/)(System::SharedPtr\<Aspose::Foundation::UriResolver::UriResolver\>) | Sets the URI resolver. |
| [XfaParserOptions](./xfaparseroptions/)(System::Drawing::SizeF) | Initializes a new instance of the [XfaParserOptions](./) class. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::XfaConverter](../)
* Library [Aspose.PDF for C++](../../)
