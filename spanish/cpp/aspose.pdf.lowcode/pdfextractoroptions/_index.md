---
title: "Clase Aspose::Pdf::LowCode::PdfExtractorOptions"
linktitle: "PdfExtractorOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::PdfExtractorOptions. Representa opciones para los complementos TextExtractor y ImageExtractor en C++."
type: docs
weight: 6000
url: /es/cpp/aspose.pdf.lowcode/pdfextractoroptions/
---
## PdfExtractorOptions class


Representa opciones para los complementos [TextExtractor](../textextractor/) y [ImageExtractor](../imageextractor/).

```cpp
class PdfExtractorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección de datos del plugin [PdfExtractor](../pdfextractor/). |
| [get_Inputs](./get_inputs/)() override | Devuelve la colección de datos del plugin [PdfExtractor](../pdfextractor/). |
| virtual [get_OperationName](./get_operationname/)() | Devuelve el nombre de la operación. |
## Observaciones


El [PdfExtractorOptions](./) contiene funciones básicas para agregar datos (archivos, flujos) que representan documentos PDF de entrada. Por favor, cree [TextExtractorOptions](../textextractoroptions/) o [ImageExtractorOptions](../imageextractoroptions/) en lugar de este.
## Ver también

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
