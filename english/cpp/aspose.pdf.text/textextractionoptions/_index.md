---
title: Aspose::Pdf::Text::TextExtractionOptions class
linktitle: TextExtractionOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextExtractionOptions class. Represents text extraction options in C++.'
type: docs
weight: 4100
url: /cpp/aspose.pdf.text/textextractionoptions/
---
## TextExtractionOptions class


Represents text extraction options.

```cpp
class TextExtractionOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Defines different modes which can be used while converting pdf document into text. See [TextDevice](../) class. |
## Methods

| Method | Description |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Gets formatting mode. |
| [get_ScaleFactor](./get_scalefactor/)() const | Gets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically. |
| [set_FormattingMode](./set_formattingmode/)(TextExtractionOptions::TextFormattingMode) | Gets formatting mode. |
| [set_ScaleFactor](./set_scalefactor/)(double) | Sets factor that will be applied to scale font size during extraction in pure mode. Setting of less value leads to more spaces in the extracted text. Default value is 1 - no scaling; Setting value to zero allows algorithm choose scaling automatically. |
| [TextExtractionOptions](./textextractionoptions/)(TextExtractionOptions::TextFormattingMode) | Initializes new instance of the [TextExtractionOptions](./) object for the specified text formatting mode. |
## See Also

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
