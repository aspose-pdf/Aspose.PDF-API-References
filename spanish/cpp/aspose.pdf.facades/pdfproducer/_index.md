---
title: "Clase Aspose::Pdf::Facades::PdfProducer"
linktitle: "PdfProducer"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::Facades::PdfProducer. Representa una clase para generar PDF a partir de otros formatos en C++."
type: docs
weight: 3000
url: /es/cpp/aspose.pdf.facades/pdfproducer/
---
## PdfProducer class


Representa una clase para producir PDF a partir de otros formatos.

```cpp
class PdfProducer : public System::Object
```

## Métodos

| Método | Descripción |
| --- | --- |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, ImportFormat, const System::SharedPtr\<System::IO::Stream\>\&) | Genera el flujo PDF usando el formato de importación especificado. |
| static [Produce](./produce/)(System::String, ImportFormat, const System::SharedPtr\<System::IO::Stream\>\&) | Genera el flujo PDF usando el formato de importación especificado. |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, ImportFormat, System::String) | Genera el archivo PDF usando el formato de importación especificado. |
| static [Produce](./produce/)(System::String, ImportFormat, System::String) | Genera el archivo PDF usando el formato de importación especificado. |
| static [Produce](./produce/)(const System::String\&, const System::SharedPtr\<ImportOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Genera el flujo PDF usando la opción de importación especificada. |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<ImportOptions\>\&, const System::String\&) | Genera el archivo PDF usando la opción de importación especificada. |
| static [Produce](./produce/)(const System::String\&, const System::SharedPtr\<ImportOptions\>\&, const System::String\&) | Genera el archivo PDF usando la opción de importación especificada. |
| static [Produce](./produce/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<ImportOptions\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Genera el archivo PDF usando la opción de importación especificada. |
## Ver también

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
