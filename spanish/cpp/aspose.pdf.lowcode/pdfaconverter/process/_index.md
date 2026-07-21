---
title: "Aspose::Pdf::LowCode::PdfAConverter::Process método"
linktitle: "Process"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::PdfAConverter::Process método. Inicia un proceso de conversión o validación PDF/A con las opciones proporcionadas en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.lowcode/pdfaconverter/process/
---
## PdfAConverter::Process method


Inicia un proceso de conversión o validación PDF/A con las opciones proporcionadas.

```cpp
System::SharedPtr<ResultContainer> Aspose::Pdf::LowCode::PdfAConverter::Process(System::SharedPtr<IPluginOptions> options) override
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| options | System::SharedPtr\<IPluginOptions\> | Un objeto de opciones que contiene instrucciones para el complemento. Debe ser una instancia de la clase [PdfAConvertOptions](../../pdfaconvertoptions/) o de la clase [PdfAValidateOptions](../../pdfavalidateoptions/). |

### ReturnValue

Un objeto [ResultContainer](../../resultcontainer/) que contiene el resultado del procesamiento.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ResultContainer](../../resultcontainer/)
* Class [IPluginOptions](../../ipluginoptions/)
* Class [PdfAConverter](../)
* Namespace [Aspose::Pdf::LowCode](../../)
* Library [Aspose.PDF for C++](../../../)
