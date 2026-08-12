---
title: "Aspose::Pdf::LowCode::TextExtractorOptions clase"
linktitle: "TextExtractorOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::TextExtractorOptions clase. Representa opciones de extracción de texto para el plugin TextExtractor en C++."
type: docs
weight: 8700
url: /es/cpp/aspose.pdf.lowcode/textextractoroptions/
---
## TextExtractorOptions class


Representa opciones de extracción de texto para el plugin [TextExtractor](../textextractor/).

```cpp
class TextExtractorOptions : public Aspose::Pdf::LowCode::PdfExtractorOptions
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [TextFormattingMode](./textformattingmode/) | Define diferentes modos que pueden usarse al convertir un documento PDF a texto. Ver la clase [TextExtractorOptions](./). |
## Métodos

| Método | Descripción |
| --- | --- |
| [get_FormattingMode](./get_formattingmode/)() const | Obtiene el modo de formato. |
| [get_OperationName](./get_operationname/)() override | Devuelve el nombre de la operación. |
| [TextExtractorOptions](./textextractoroptions/)(TextExtractorOptions::TextFormattingMode) | Inicializa una nueva instancia del objeto [TextExtractorOptions](./) para el modo de formato de texto especificado. |
| [TextExtractorOptions](./textextractoroptions/)() | Inicializa una nueva instancia del objeto [TextExtractorOptions ](./) con el modo de formato de texto 'Raw' (predeterminado). |
## Observaciones


El objeto [TextExtractorOptions](./) se utiliza para establecer [TextFormattingMode](./textformattingmode/) y otras opciones para la operación de extracción de texto. Además, hereda funciones para agregar datos (archivos, flujos) que representan documentos PDF de entrada.
## Ver también

* Class [PdfExtractorOptions](../pdfextractoroptions/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
