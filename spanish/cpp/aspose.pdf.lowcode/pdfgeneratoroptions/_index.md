---
title: "Aspose::Pdf::LowCode::PdfGeneratorOptions clase"
linktitle: "PdfGeneratorOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::PdfGeneratorOptions clase. Representa opciones para los plugins Generator en C++."
type: docs
weight: 6100
url: /es/cpp/aspose.pdf.lowcode/pdfgeneratoroptions/
---
## PdfGeneratorOptions class


Representa las opciones para los plugins Generator.

```cpp
class PdfGeneratorOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                            public Aspose::Pdf::LowCode::IDataContainer,
                            public Aspose::Pdf::LowCode::ISaveInstruction
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección de datos del plugin PdfGenerator. |
| [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección de datos del plugin PdfGenerator. |
| [get_Inputs](./get_inputs/)() override | Devuelve la colección de datos del plugin PdfGenerator. |
| [get_Outputs](./get_outputs/)() override | Obtiene la colección de objetivos añadidos para guardar los resultados de la operación. |
## Ver también

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
