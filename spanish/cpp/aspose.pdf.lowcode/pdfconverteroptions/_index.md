---
title: "Aspose::Pdf::LowCode::PdfConverterOptions clase"
linktitle: "PdfConverterOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Clase Aspose::Pdf::LowCode::PdfConverterOptions. Representa opciones para complementos de convertidor Pdf en C++."
type: docs
weight: 5800
url: /es/cpp/aspose.pdf.lowcode/pdfconverteroptions/
---
## PdfConverterOptions class


Representa opciones para complementos de convertidor [Pdf](../../aspose.pdf/).

```cpp
class PdfConverterOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección de datos del complemento PdfConverter. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección de datos del complemento PdfToXLSXConverterOptions. |
| [get_Inputs](./get_inputs/)() override | Devuelve la colección de datos del complemento [PdfConverterOptions](./). |
| virtual [get_OperationName](./get_operationname/)() | Devuelve el nombre de la operación. |
| [get_Outputs](./get_outputs/)() override | Obtiene la colección de objetivos añadidos para guardar los resultados de la operación. |
## Ver también

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
