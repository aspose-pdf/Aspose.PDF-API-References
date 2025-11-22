---
title: Aspose::Pdf::PsLoadOptions class
linktitle: PsLoadOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PsLoadOptions class. Represents options for loading/importing of .mht-file into pdf document in C++.'
type: docs
weight: 16100
url: /cpp/aspose.pdf/psloadoptions/
---
## PsLoadOptions class


Represents options for loading/importing of .mht-file into pdf document.

```cpp
class PsLoadOptions : public Aspose::Pdf::LoadOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_ConvertFontsToTTF](./get_convertfontstottf/)() const | Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image. |
| [get_FontsFolders](./get_fontsfolders/)() const | Gets fonts folders paths. |
| [PsLoadOptions](./psloadoptions/)() | Creates load options for converting PostScript into pdf document with empty base path. |
| [set_ConvertFontsToTTF](./set_convertfontstottf/)(bool) | Specifies whether to save non-TrueType fonts to TTF. It significantly decreases the volume of the resulting document in PS to PDF conversion and increases the speed of conversion of PS files with a large quantity of text in non-TrueType fonts to any output format. However, there is small vertical shift of text when converting PostSctipt file to image. |
| [set_FontsFolders](./set_fontsfolders/)(System::ArrayPtr\<System::String\>) | Sets fonts folders paths. |
## See Also

* Class [LoadOptions](../loadoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
