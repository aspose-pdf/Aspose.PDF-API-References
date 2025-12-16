---
title: Aspose::Pdf::PdfSaveOptions class
linktitle: PdfSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfSaveOptions class. Save options for export to Pdf format in C++.'
type: docs
weight: 15400
url: /cpp/aspose.pdf/pdfsaveoptions/
---
## PdfSaveOptions class


Save options for export to [Pdf](../) format.

```cpp
class PdfSaveOptions : public Aspose::Pdf::SaveOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_DefaultFontName](./get_defaultfontname/)() const | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [DefaultFontName](../) is found on device) |
| [get_TempPath](./get_temppath/)() const | Path for temporary files. |
| [PdfSaveOptions](./pdfsaveoptions/)() | Constructor. |
| [set_DefaultFontName](./set_defaultfontname/)(System::String) | Font name used by default for fonts which are absent on computer. When the PDF document that is saved into PDF contains fonts, that are not available in the document itself and on the device, API replaces this fonts with the default font(if font with [DefaultFontName](../) is found on device) |
| [set_TempPath](./set_temppath/)(System::String) | Path for temporary files. |
## See Also

* Class [SaveOptions](../saveoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
