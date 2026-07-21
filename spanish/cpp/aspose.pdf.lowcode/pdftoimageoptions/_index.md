---
title: "Aspose::Pdf::LowCode::PdfToImageOptions clase"
linktitle: "PdfToImageOptions"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::LowCode::PdfToImageOptions clase. Representa opciones para el plugin PdfToImage en C++."
type: docs
weight: 6500
url: /es/cpp/aspose.pdf.lowcode/pdftoimageoptions/
---
## PdfToImageOptions class


Representa opciones para el plugin [PdfToImage](../pdftoimage/).

```cpp
class PdfToImageOptions : public Aspose::Pdf::LowCode::IPluginOptions,
                          public Aspose::Pdf::LowCode::IDataContainer,
                          public Aspose::Pdf::LowCode::ISaveInstruction
```

## Enums

| Enumeración | Descripción |
| --- | --- |
| [ImageConversionMode](./imageconversionmode/) | Define diferentes modos que pueden usarse al convertir un documento PDF a imagen [Jpeg](../jpeg/). Consulte la clase [JpegOptions](../jpegoptions/). |
## Métodos

| Método | Descripción |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Agrega una nueva fuente de datos a la colección de datos del plugin [PdfToImage](../pdftoimage/). |
|  | [AddOutput](./addoutput/)(System::SharedPtr\<IDataSource\>) override | Establece una nueva fuente de datos de guardado. Solo puede ser un |
[FileDataSource](../filedatasource/)


. Si desea guardar imágenes en flujos de memoria, pase null como parámetro. |
| [get_ConversionMode](./get_conversionmode/)() | Obtiene el modo de conversión de imagen. |
| [get_Inputs](./get_inputs/)() override | Devuelve la colección de datos del plugin [PdfToImage](../pdftoimage/). |
| virtual [get_OperationName](./get_operationname/)() | Devuelve el nombre de la operación. |
| [get_OutputResolution](./get_outputresolution/)() const | Obtiene el valor de resolución de las imágenes resultantes. |
| [get_Outputs](./get_outputs/)() override | Obtiene la colección de objetivos añadidos (fuentes de datos de archivo o flujo) para guardar los resultados de la operación. |
| [get_PageList](./get_pagelist/)() const | Obtiene una lista de páginas para el proceso. |
| [set_OutputResolution](./set_outputresolution/)(int32_t) | Establece el valor de resolución de las imágenes resultantes. |
| [set_PageList](./set_pagelist/)(const System::SharedPtr\<System::Collections::Generic::List\<int32_t\>\>\&) | Establece una lista de páginas para el proceso. |
## Observaciones


La clase PdfImageOptions contiene funciones base para agregar datos (archivos, flujos) que representan documentos PDF de entrada.
## Ver también

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Class [ISaveInstruction](../isaveinstruction/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
