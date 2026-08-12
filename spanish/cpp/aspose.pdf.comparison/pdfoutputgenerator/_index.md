---
title: "Clase Aspose::Pdf::Comparison::PdfOutputGenerator"
linktitle: "PdfOutputGenerator"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Comparison::PdfOutputGenerator. Representa una clase para generar la representación PDF de las diferencias de textos en C++."
type: docs
weight: 1300
url: /es/cpp/aspose.pdf.comparison/pdfoutputgenerator/
---
## PdfOutputGenerator class


Representa una clase para generar una representación PDF de las diferencias de textos.

```cpp
class PdfOutputGenerator : public Aspose::Pdf::Comparison::IFileOutputGenerator,
                           public Aspose::Pdf::LicenseManagement::IVentureLicenseTarget
```

## Métodos

| Método | Descripción |
| --- | --- |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>, System::String) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [GenerateOutput](./generateoutput/)(System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<System::Collections::Generic::List\<System::SharedPtr\<DiffOperation\>\>\>\>\>, System::String) override | Genera la salida basada en las diferencias entre textos y la guarda en un archivo. |
| [PdfOutputGenerator](./pdfoutputgenerator/)() | Crea una instancia de la clase [PdfOutputGenerator](./). |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<PageInfo\>\&) | Crea una instancia de la clase [PdfOutputGenerator](./). |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&) | Crea una instancia de la clase [PdfOutputGenerator](./). |
| [PdfOutputGenerator](./pdfoutputgenerator/)(const System::SharedPtr\<OutputTextStyle\>\&, const System::SharedPtr\<PageInfo\>\&) | Crea una instancia de la clase [PdfOutputGenerator](./). |
## Ver también

* Class [IFileOutputGenerator](../ifileoutputgenerator/)
* Namespace [Aspose::Pdf::Comparison](../)
* Library [Aspose.PDF for C++](../../)
