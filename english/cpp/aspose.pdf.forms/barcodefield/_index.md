---
title: Aspose::Pdf::Forms::BarcodeField class
linktitle: BarcodeField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::BarcodeField class. Class represents barcode field in C++.'
type: docs
weight: 100
url: /cpp/aspose.pdf.forms/barcodefield/
---
## BarcodeField class


Class represents barcode field.

```cpp
class BarcodeField : public Aspose::Pdf::Forms::TextBoxField
```

## Methods

| Method | Description |
| --- | --- |
| [BarcodeField](./barcodefield/)(System::SharedPtr\<Aspose::Pdf::Page\>, System::SharedPtr\<Rectangle\>) | Initializes new instance of the [BarcodeField](./) class. |
| [BarcodeField](./barcodefield/)(System::SharedPtr\<Document\>, System::SharedPtr\<Rectangle\>) | Initializes new instance of the [BarcodeField](./) class. |
| [get_Caption](./get_caption/)() | Gets the caption of the barcode object. |
| [get_ECC](./get_ecc/)() | Gets an integer value representing the error correction coefficient. For PDF417, shall be from 0 to 8. For QRCode, shall be from 0 to 3 (0 for 'L', 1 for 'M', 2 for 'Q', and 3 for 'H'). |
| [get_Resolution](./get_resolution/)() | Gets the resolution, in dots-per-inch (dpi), at which the barcode object is rendered. |
| [get_Symbology](./get_symbology/)() | Specifies which barcode or glyph technology is to be used on this annotation, see [Symbology](../symbology/) for details. |
| [get_XSymHeight](./get_xsymheight/)() | Gets the the vertical distance between two barcode modules, measured in pixels. The ratio XSymHeight/XSymWidth shall be an integer value. For PDF417, the acceptable ratio range is from 1 to 4. For QRCode and DataMatrix, this ratio shall always be 1. |
| [get_XSymWidth](./get_xsymwidth/)() | Gets The horizontal distance, in pixels, between two barcode modules. |
## See Also

* Class [TextBoxField](../textboxfield/)
* Namespace [Aspose::Pdf::Forms](../)
* Library [Aspose.PDF for C++](../../)
