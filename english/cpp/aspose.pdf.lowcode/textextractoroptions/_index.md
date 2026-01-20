---
title: Aspose::Pdf::LowCode::TextExtractorOptions class
linktitle: TextExtractorOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::TextExtractorOptions class. Represents text extraction options for the TextExtractor plugin in C++.'
type: docs
weight: 8700
url: /cpp/aspose.pdf.lowcode/textextractoroptions/
---
## TextExtractorOptions class


Represents text extraction options for the [TextExtractor](../textextractor/) plugin.

```cpp
class TextExtractorOptions : public Aspose::Pdf::LowCode::PdfExtractorOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Defines different modes which can be used while converting a PDF document into text. See [TextExtractorOptions](./) class. |
## Methods

| Method | Description |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Gets formatting mode. |
| [get_OperationName](./get_operationname/)() override | Returns name of the operation. |
| [TextExtractorOptions](./textextractoroptions/)(TextExtractorOptions::TextFormattingMode) | Initializes a new instance of the [TextExtractorOptions](./) object for the specified text formatting mode. |
| [TextExtractorOptions](./textextractoroptions/)() | Initializes a new instance of the [TextExtractorOptions ](./) object with 'Raw' (default) text formatting mode. |
## Remarks


The [TextExtractorOptions](./) object is used to set [TextFormattingMode](./textformattingmode/) and another options for the text extraction operation. Also, it inherits functions to add data (files, streams) representing input PDF documents. 
## See Also

* Class [PdfExtractorOptions](../pdfextractoroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
