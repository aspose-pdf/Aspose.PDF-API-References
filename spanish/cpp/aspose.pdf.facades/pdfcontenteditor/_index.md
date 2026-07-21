---
title: "Aspose::Pdf::Facades::PdfContentEditor clase"
linktitle: "PdfContentEditor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfContentEditor clase. Representa una clase para editar el contenido del archivo PDF en C++."
type: docs
weight: 1700
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/
---
## PdfContentEditor class


Representa una clase para editar el contenido del archivo PDF.

```cpp
class PdfContentEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [AddDocumentAdditionalAction](./adddocumentadditionalaction/)(const System::String\&, const System::String\&) | Agrega una acción adicional para el evento del documento. |
| [AddDocumentAttachment](./adddocumentattachment/)(const System::String\&, const System::String\&) | Agrega un adjunto de documento sin anotación. |
| [AddDocumentAttachment](./adddocumentattachment/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, const System::String\&) | Agrega un adjunto de documento sin anotación. |
| [BindPdf](./bindpdf/)(System::String) override | Vincula un archivo PDF para edición. |
| [BindPdf](./bindpdf/)(System::SharedPtr\<System::IO::Stream\>) override | Vincula un flujo PDF para edición. |
| [ChangeViewerPreference](./changeviewerpreference/)(int32_t) | Cambia la preferencia de vista. |
| [Close](./close/)() override | Cierra el documento abierto. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| [CreateApplicationLink](./createapplicationlink/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Crea un enlace para lanzar una aplicación en el documento PDF. |
| [CreateBookmarksAction](./createbookmarksaction/)(const System::String\&, System::Drawing::Color, bool, bool, const System::String\&, const System::String\&, const System::String\&) | Crea un marcador con la acción especificada. |
| [CreateCaret](./createcaret/)(int32_t, System::Drawing::Rectangle, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) | Crea una anotación de cursor. |
| [CreateCustomActionLink](./createcustomactionlink/)(System::Drawing::Rectangle, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Crea un enlace a acciones personalizadas en el documento PDF. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) | Crea una anotación de adjunto de archivo. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&, double) | Crea una anotación de adjunto de archivo. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&) | Crea una anotación de adjunto de archivo. |
| [CreateFileAttachment](./createfileattachment/)(System::Drawing::Rectangle, const System::String\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&, int32_t, const System::String\&, double) | Crea una anotación de adjunto de archivo. |
| [CreateFreeText](./createfreetext/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Crea una anotación de texto libre en el documento PDF. |
| [CreateJavaScriptLink](./createjavascriptlink/)(const System::String\&, System::Drawing::Rectangle, int32_t, System::Drawing::Color) | Crea un enlace a JavaScript en el documento PDF. |
| [CreateLine](./createline/)(System::Drawing::Rectangle, const System::String\&, float, float, float, float, int32_t, int32_t, System::Drawing::Color, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::ArrayPtr\<System::String\>\&) | Crea una anotación de línea. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Crea un enlace local en el documento PDF. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t, System::Drawing::Color) | Crea un enlace local en el documento PDF. |
| [CreateLocalLink](./createlocallink/)(System::Drawing::Rectangle, int32_t, int32_t) | Crea un enlace local en el documento PDF. |
| [CreateMarkup](./createmarkup/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) | Crea una anotación de marcado en el documento PDF. |
| [CreateMovie](./createmovie/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Crea Movie [Annotations](../../aspose.pdf.annotations/). |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Crea un enlace a otra página de documento PDF. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t, System::Drawing::Color) | Crea un enlace a otra página de documento PDF. |
| [CreatePdfDocumentLink](./createpdfdocumentlink/)(System::Drawing::Rectangle, const System::String\&, int32_t, int32_t) | Crea un enlace a otra página de documento PDF. |
| [CreatePolygon](./createpolygon/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Crea una anotación de polígono. |
| [CreatePolyLine](./createpolyline/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Crea una anotación de polilínea. |
| [CreatePopup](./createpopup/)(System::Drawing::Rectangle, const System::String\&, bool, int32_t) | Crea una anotación emergente en el documento PDF. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, const System::String\&, System::Drawing::Color) | Crea una anotación de sello de goma. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::String\&) | Crea una anotación de sello de goma. |
| [CreateRubberStamp](./createrubberstamp/)(int32_t, System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, const System::SharedPtr\<System::IO::Stream\>\&) | Crea una anotación de sello de goma. |
| [CreateSound](./createsound/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, int32_t, const System::String\&) | Crea anotaciones de sonido [Anotaciones](../../aspose.pdf.annotations/). |
| [CreateSquareCircle](./createsquarecircle/)(System::Drawing::Rectangle, const System::String\&, System::Drawing::Color, bool, int32_t, int32_t) | Crea una anotación de cuadrado-círculo. |
| [CreateText](./createtext/)(System::Drawing::Rectangle, const System::String\&, const System::String\&, bool, const System::String\&, int32_t) | Crea una anotación de texto en el documento PDF. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color, const System::ArrayPtr\<System::SharedPtr\<System::BoxedValueBase\>\>\&) | Crea un enlace web en el documento PDF. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t, System::Drawing::Color) | Crea un enlace web en el documento PDF. |
| [CreateWebLink](./createweblink/)(System::Drawing::Rectangle, const System::String\&, int32_t) | Crea un enlace web en el documento PDF. |
| [DeleteAttachments](./deleteattachments/)() | Elimina todos los archivos adjuntos del documento PDF. |
| [DeleteImage](./deleteimage/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Elimina las imágenes especificadas en la página especificada. |
| [DeleteImage](./deleteimage/)() | Elimina todas las imágenes del documento PDF. |
| [DeleteStamp](./deletestamp/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Elimina varios sellos en la página especificada por índices de sello. |
| [DeleteStampById](./deletestampbyid/)(int32_t, int32_t) | Elimina el sello en la página especificada por ID de sello. |
| [DeleteStampById](./deletestampbyid/)(int32_t) | Elimina el sello por ID de todas las páginas del documento. |
| [DeleteStampByIds](./deletestampbyids/)(const System::ArrayPtr\<int32_t\>\&) | Elimina los sellos con IDs especificados de todas las páginas del documento. |
| [DeleteStampByIds](./deletestampbyids/)(int32_t, const System::ArrayPtr\<int32_t\>\&) | Elimina los sellos en la página especificada por varios IDs de sello. |
| [DrawCurve](./drawcurve/)(const System::SharedPtr\<LineInfo\>\&, int32_t, System::Drawing::Rectangle, const System::String\&) | Crea una anotación de curva. |
| [ExtractLink](./extractlink/)() | Extrae la colección de instancias de Link contenidas en el documento PDF. |
| [get_ReplaceTextStrategy](./get_replacetextstrategy/)() const | Un conjunto de parámetros para la operación de reemplazo de texto. |
| [get_TextEditOptions](./get_texteditoptions/)() const | Obtiene opciones de edición de texto. |
| [get_TextReplaceOptions](./get_textreplaceoptions/)() const | Obtiene opciones de reemplazo de texto. |
| [get_TextSearchOptions](./get_textsearchoptions/)() const | Obtiene opciones de búsqueda de texto. |
| [GetStamps](./getstamps/)(int32_t) | Devuelve una matriz de sellos en la página. |
| [GetViewerPreference](./getviewerpreference/)() | Devuelve la preferencia de vista. |
| [HideStampById](./hidestampbyid/)(int32_t, int32_t) | Oculta el sello. Después de ocultarlo, la visibilidad del sello puede restaurarse con el método ShowStampById. |
| [MoveStamp](./movestamp/)(int32_t, int32_t, double, double) | Cambia la posición del sello en la página. |
| [MoveStampById](./movestampbyid/)(int32_t, int32_t, double, double) | Cambia la posición del sello en la página. |
| [PdfContentEditor](./pdfcontenteditor/)() | El constructor del objeto [PdfContentEditor](./). |
| [PdfContentEditor](./pdfcontenteditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfContentEditor](./) sobre la base del *document*. |
| [RemoveDocumentOpenAction](./removedocumentopenaction/)() | Elimina la acción de apertura del documento. Esta operación es útil al concatenar varios documentos que utilizan una acción 'GoTo' explícita al iniciar. |
| [ReplaceImage](./replaceimage/)(int32_t, int32_t, const System::String\&) | Reemplaza la imagen especificada en la página especificada del documento PDF con otra imagen. |
| [ReplaceText](./replacetext/)(const System::String\&, int32_t, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Reemplaza texto en el archivo PDF en la página especificada. Se puede especificar el objeto [TextState](../) (familia de fuentes, color) para el texto reemplazado. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&) | Reemplaza texto en el archivo PDF. |
| [ReplaceText](./replacetext/)(const System::String\&, int32_t, const System::String\&) | Reemplaza texto en el archivo PDF en la página especificada. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) | Reemplaza texto en el archivo PDF usando el objeto [TextState](../) especificado. |
| [ReplaceText](./replacetext/)(const System::String\&, const System::String\&, int32_t) | Reemplaza texto en el archivo PDF y establece el tamaño de fuente. |
| [set_ReplaceTextStrategy](./set_replacetextstrategy/)(const System::SharedPtr\<Aspose::Pdf::Facades::ReplaceTextStrategy\>\&) | Un conjunto de parámetros para la operación de reemplazo de texto. |
| [set_TextEditOptions](./set_texteditoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextEditOptions\>\&) | Establece opciones de edición de texto. |
| [set_TextReplaceOptions](./set_textreplaceoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextReplaceOptions\>\&) | Establece opciones de reemplazo de texto. |
| [set_TextSearchOptions](./set_textsearchoptions/)(const System::SharedPtr\<Aspose::Pdf::Text::TextSearchOptions\>\&) | Establece opciones de búsqueda de texto. |
| [ShowStampById](./showstampbyid/)(int32_t, int32_t) | Muestra el sello que fue ocultado por HiddenStampById. |
## Campos

| Campo | Descripción |
| --- | --- |
| static [DocumentClose](./documentclose/) | Tipo de evento de documento. Cierra un documento. |
| static [DocumentOpen](./documentopen/) | Tipo de evento de documento. Abre un documento. |
| static [DocumentPrinted](./documentprinted/) | Tipo de evento de documento. Ejecuta una acción después de imprimir. |
| static [DocumentSaved](./documentsaved/) | Tipo de evento de documento. Ejecuta una acción después de guardar. |
| static [DocumentWillPrint](./documentwillprint/) | Tipo de evento de documento. Ejecuta una acción antes de imprimir. |
| static [DocumentWillSave](./documentwillsave/) | Tipo de evento de documento. Ejecuta una acción antes de guardar. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
