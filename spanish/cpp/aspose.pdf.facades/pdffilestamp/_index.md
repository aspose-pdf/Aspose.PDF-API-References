---
title: "Aspose::Pdf::Facades::PdfFileStamp clase"
linktitle: "PdfFileStamp"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileStamp clase. Clase para agregar sellos (marca de agua o fondo) a archivos PDF en C++."
type: docs
weight: 2600
url: /es/cpp/aspose.pdf.facades/pdffilestamp/
---
## PdfFileStamp class


Clase para añadir sellos (marca de agua o fondo) a archivos PDF.

```cpp
class PdfFileStamp : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddFooter](./addfooter/)(const System::SharedPtr\<FormattedText\>\&, float) | Agrega pie de página a las páginas del documento. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<FormattedText\>\&, float, float, float) | Agrega pie de página a las páginas del documento. |
| [AddFooter](./addfooter/)(const System::String\&, float) | Agrega una imagen como pie de página a las páginas del documento. |
| [AddFooter](./addfooter/)(const System::String\&, float, float, float) | Agrega una imagen como pie de página de las páginas. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<System::IO::Stream\>\&, float) | Agrega una imagen como pie de página de la página. |
| [AddFooter](./addfooter/)(const System::SharedPtr\<System::IO::Stream\>\&, float, float, float) | Agrega una imagen como pie de página de la página. |
| [AddHeader](./addheader/)(const System::SharedPtr\<FormattedText\>\&, float) | Agrega encabezado a la página. |
| [AddHeader](./addheader/)(const System::SharedPtr\<FormattedText\>\&, float, float, float) | Agrega encabezado a las páginas del archivo. |
| [AddHeader](./addheader/)(const System::String\&, float) | Agrega una imagen como encabezado a las páginas del archivo. |
| [AddHeader](./addheader/)(const System::String\&, float, float, float) | Agrega una imagen como encabezado en las páginas. |
| [AddHeader](./addheader/)(const System::SharedPtr\<System::IO::Stream\>\&, float) | Agrega una imagen como encabezado en las páginas. |
| [AddHeader](./addheader/)(const System::SharedPtr\<System::IO::Stream\>\&, float, float, float) | Agrega una imagen en la parte superior de la página. |
| [AddPageNumber](./addpagenumber/)(const System::String\&) | Agrega número de página al archivo. [Page](../../aspose.pdf/page/) el texto del número puede contener el signo # que será reemplazado por el número de la página. [Page](../../aspose.pdf/page/) el número se coloca en la parte inferior de la página centrado horizontalmente. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&) | Agrega número de página a la página. [Page](../../aspose.pdf/page/) el número puede contener el signo # que será reemplazado por el número de página. [Page](../../aspose.pdf/page/) el número se coloca en la parte inferior de la página centrado horizontalmente. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, int32_t, float, float, float, float) | Agrega número de página a las páginas del documento. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, float, float) | Agrega número de página en la posición especificada de la página. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) | Agrega número de página a las páginas del documento. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, float, float) | Agrega número de página en la posición especificada de la página. |
| [AddPageNumber](./addpagenumber/)(const System::String\&, int32_t) | Agrega número de página a las páginas. |
| [AddPageNumber](./addpagenumber/)(const System::SharedPtr\<FormattedText\>\&, int32_t) | Agrega número de página a las páginas. |
| [AddStamp](./addstamp/)(const System::SharedPtr\<Stamp\>\&) | Agrega sello al archivo. |
| [Close](./close/)() override | Cierra los archivos abiertos y guarda los cambios. Advertencia. Si se especifican flujos de entrada o salida, no se cierran mediante el método [Close()](./close/). |
| [get_AttachmentName](./get_attachmentname/)() const | Obtiene el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Obtiene cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [get_InputFile](./get_inputfile/)() const | Obtiene el nombre y la ruta del archivo de entrada. |
| [get_InputStream](./get_inputstream/)() const | Obtiene el flujo de entrada. |
| [get_KeepSecurity](./get_keepsecurity/)() const | Mantiene la seguridad si es verdadero. (Esta característica se implementará en próximas versiones). |
| [get_NumberingStyle](./get_numberingstyle/)() const | Obtiene el estilo de numeración de pabge. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [get_OptimizeSize](./get_optimizesize/)() const | Obtiene la bandera de optimización. Los flujos de recursos iguales en el archivo resultante se fusionan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [get_OutputFile](./get_outputfile/)() const | Obtiene el nombre y la ruta del archivo de salida. |
| [get_OutputStream](./get_outputstream/)() const | Obtiene el flujo de salida. |
| [get_PageHeight](./get_pageheight/)() | Obtiene la altura de la primera página en el archivo souorce. |
| [get_PageNumberRotation](./get_pagenumberrotation/)() | Obtiene la rotación del número de página. [Rotation](../../aspose.pdf/rotation/) está en grados. El valor predeterminado es 0. |
| [get_PageWidth](./get_pagewidth/)() | Obtiene el ancho de la primera página en el archivo de entrada. |
| [get_Response](./get_response/)() const | Obtiene el objeto Response donde se almacenará el resultado de la operación. |
| [get_SaveOptions](./get_saveoptions/)() const | Obtiene las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_StampId](./get_stampid/)() const | [Stamp](../stamp/) ID del siguiente sello añadido (incluiding encabezados de página/hooters/números de página). |
| [get_StartingNumber](./get_startingnumber/)() const | Obtiene el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102... |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::String\&) | Constructor para [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Constructor para [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::String\&, bool) | Constructor para [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, bool) | Constructor de [PdfFileStamp](./). |
| [PdfFileStamp](./pdffilestamp/)() | Constructor del [PdfFileStamp](./). El archivo de entrada y el archivo de salida pueden especificarse mediante las propiedades correspondientes. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfFileStamp](./) basado en el *document*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::String\&) | Inicializa un nuevo objeto [PdfFileStamp](./) basado en el *document*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&) | Inicializa un nuevo objeto [PdfFileStamp](./) basado en el *document*. |
| [PdfFileStamp](./pdffilestamp/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Crea [PdfFileStamp](./) que guardará el resultado en un objeto HttpResponse. |
| [PdfFileStamp](./pdffilestamp/)(const System::String\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) | Crea [PdfFileStamp](./) que guardará el resultado en un objeto HttpResponse. |
| [Save](./save/)(System::String) override | Guarda el resultado en el archivo especificado. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Guarda el documento en el flujo especificado. |
| [set_AttachmentName](./set_attachmentname/)(const System::String\&) | Establece el nombre del adjunto cuando el resultado de la operación se almacena en objetos HttpResponse como adjunto. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Establece cómo se almacenará el contenido cuando el resultado de la operación se almacene en un objeto HttpResponse. Valor posible: inline / attachment. Predeterminado: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Establece el formato de archivo PDF. El archivo resultante se guardará en el formato de archivo especificado. Si esta propiedad no se especifica, el archivo se guardará en el formato PDF predeterminado sin conversión. |
| [set_InputFile](./set_inputfile/)(const System::String\&) | Establece el nombre y la ruta del archivo de entrada. |
| [set_InputStream](./set_inputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de entrada. |
| [set_KeepSecurity](./set_keepsecurity/)(bool) | Mantiene la seguridad si es verdadero. (Esta característica se implementará en próximas versiones). |
| [set_NumberingStyle](./set_numberingstyle/)(Aspose::Pdf::NumberingStyle) | Establece el estilo de numeración de pabge. Valores posibles: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase. |
| [set_OptimizeSize](./set_optimizesize/)(bool) | Establece la bandera de optimización. Los flujos de recursos iguales en el archivo resultante se fusionan en un solo objeto PDF si esta bandera está activada. Esto permite reducir el tamaño del archivo resultante pero puede causar una ejecución más lenta y mayores requisitos de memoria. Valor predeterminado: false. |
| [set_OutputFile](./set_outputfile/)(const System::String\&) | Establece el nombre y la ruta del archivo de salida. |
| [set_OutputStream](./set_outputstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Establece el flujo de salida. |
| [set_PageNumberRotation](./set_pagenumberrotation/)(float) | Establece la rotación del número de página. [Rotation](../../aspose.pdf/rotation/) está en grados. El valor predeterminado es 0. |
| [set_Response](./set_response/)(const System::SharedPtr\<System::Web::HttpResponse\>\&) | Establece el objeto Response donde se almacenará el resultado de la operación. |
| [set_SaveOptions](./set_saveoptions/)(const System::SharedPtr\<Aspose::Pdf::SaveOptions\>\&) | Establece las opciones de guardado cuando el resultado se almacena como HttpResponse. Valor predeterminado: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_StampId](./set_stampid/)(int32_t) | [Stamp](../stamp/) ID del siguiente sello añadido (incluiding encabezados de página/hooters/números de página). |
| [set_StartingNumber](./set_startingnumber/)(int32_t) | Establece el número inicial para la primera página en el archivo de entrada. Las páginas siguientes se numerarán a partir de este valor. Por ejemplo, si StartingNumber se establece en 100, las páginas del documento tendrán los números 100, 101, 102... |
## Campos

| Campo | Descripción |
| --- | --- |
| static [PosBottomLeft](./posbottomleft/) | Posición inferior izquierda. |
| static [PosBottomMiddle](./posbottommiddle/) | Posición inferior central. |
| static [PosBottomRight](./posbottomright/) | Posición inferior derecha. |
| static [PosSidesLeft](./possidesleft/) | [Left](../../aspose.pdf/left/) posición. |
| static [PosSidesRight](./possidesright/) | [Right](../../aspose.pdf/right/) posición. |
| static [PosUpperLeft](./posupperleft/) | Posición superior izquierda. |
| static [PosUpperMiddle](./posuppermiddle/) | Posición superior central. |
| static [PosUpperRight](./posupperright/) | [Right](../../aspose.pdf/right/) posición superior. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
