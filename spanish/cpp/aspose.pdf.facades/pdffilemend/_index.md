---
title: "Aspose::Pdf::Facades::PdfFileMend clase"
linktitle: "PdfFileMend"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileMend clase. Representa una clase para agregar textos e imágenes en las páginas de un documento PDF existente en C++."
type: docs
weight: 2200
url: /es/cpp/aspose.pdf.facades/pdffilemend/
---
## PdfFileMend class


Representa una clase para añadir textos e imágenes en las páginas de un documento PDF existente.

```cpp
class PdfFileMend : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::String\&, int32_t, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Agrega una imagen a la página especificada del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddImage](./addimage/)(const System::String\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float, const System::SharedPtr\<CompositingParameters\>\&) | Agrega una imagen a las páginas especificadas del documento PDF en las coordenadas especificadas. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float) | No implementado. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | No implementado. |
| [AddText](./addtext/)(const System::SharedPtr\<FormattedText\>\&, const System::ArrayPtr\<int32_t\>\&, float, float, float, float) | No implementado. |
| [Close](./close/)() override | Cierra el objeto [PdfFileMend](./). |
| [get_InputFile](./get_inputfile/)() const | Establece el archivo de entrada. |
| [get_InputStream](./get_inputstream/)() const | Establece el flujo de entrada. |
| [get_OutputFile](./get_outputfile/)() const | Establece el archivo de salida. |
| [get_OutputStream](./get_outputstream/)() const | Establece el flujo de salida. |
| [get_TextPositioningMode](./get_textpositioningmode/)() const | Establece o obtiene la estrategia de posicionamiento de texto. [PositioningMode](../positioningmode/) El modo predeterminado es Legacy. |
| [get_WrapMode](./get_wrapmode/)() const | Establece o obtiene el algoritmo de ajuste de línea. Ver [WordWrapMode](../wordwrapmode/) y IsWordWrap. |
| [PdfFileMend](./pdffilemend/)() | Constructor. |
| [PdfFileMend](./pdffilemend/)(const System::String\&, const System::String\&) | Constructor. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfFileMend](./) basado en el *document*. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Inicializa un nuevo objeto [PdfFileMend](./) basado en el *document*. |
| [PdfFileMend](./pdffilemend/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa un nuevo objeto [PdfFileMend](./) basado en el *document*. |
| [Save](./save/)(System::String) override | Guarda el documento PDF en el archivo especificado. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el documento PDF en el flujo especificado. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Establece el archivo de entrada. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de entrada. |
| [set_IsWordWrap](./set_iswordwrap/)(bool) | Establece un valor bool que indica el ajuste de línea en los métodos AddText. Si el valor es true, el texto en [FormattedText](../formattedtext/) se ajustará. Por defecto, el valor es false. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Establece el archivo de salida. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de salida. |
| [set_TextPositioningMode](./set_textpositioningmode/)(PositioningMode) | Establece o obtiene la estrategia de posicionamiento de texto. [PositioningMode](../positioningmode/) El modo predeterminado es Legacy. |
| [set_WrapMode](./set_wrapmode/)(WordWrapMode) | Establece o obtiene el algoritmo de ajuste de línea. Ver [WordWrapMode](../wordwrapmode/) y IsWordWrap. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
