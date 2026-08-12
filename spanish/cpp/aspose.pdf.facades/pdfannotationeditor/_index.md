---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor clase"
linktitle: "PdfAnnotationEditor"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor clase. Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF en C++."
type: docs
weight: 1500
url: /es/cpp/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class


Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF.

```cpp
class PdfAnnotationEditor : public Aspose::Pdf::Facades::SaveableFacade
```

## Métodos

| Método | Descripción |
| --- | --- |
| [DeleteAnnotation](./deleteannotation/)(const System::String\&) | Elimina la anotación con el nombre de anotación especificado. |
| [DeleteAnnotations](./deleteannotations/)() | Elimina todas las anotaciones del documento. |
| [DeleteAnnotations](./deleteannotations/)(const System::String\&) | Elimina todas las anotaciones del tipo especificado en el documento. |
| [ExportAnnotationsToXfdf](./exportannotationstoxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Exporta anotaciones a un flujo. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) | Exporta el contenido de los tipos de anotación especificados a XFDF. |
| [ExportAnnotationsXfdf](./exportannotationsxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Exporta el contenido de los tipos de anotaciones especificados a XFDF. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) | Obtiene la lista de anotaciones de los tipos especificados. |
| [ExtractAnnotations](./extractannotations/)(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Obtiene la lista de anotaciones de los tipos especificados. |
| [FlatteningAnnotations](./flatteningannotations/)() | Aplana todas las anotaciones en el documento. |
| [FlatteningAnnotations](./flatteningannotations/)(const System::SharedPtr\<Forms::Form::FlattenSettings\>\&) | Aplana todas las anotaciones en el documento. |
| [FlatteningAnnotations](./flatteningannotations/)(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Aplana las anotaciones de los tipos especificados. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::String\&) | Importa todas las anotaciones del archivo XFDF. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::String\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importa las anotaciones especificadas del archivo XFDF. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importa las anotaciones especificadas del flujo de datos XFDF. |
| [ImportAnnotationFromXfdf](./importannotationfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa todas las anotaciones del flujo de datos XFDF. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importa las anotaciones especificadas al documento desde una matriz de otros documentos PDF. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::String\>\&) | Importa anotaciones al documento desde una matriz de otros documentos PDF. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) | Importa las anotaciones especificadas al documento desde una matriz de flujos de documentos PDF. |
| [ImportAnnotations](./importannotations/)(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) | Importa anotaciones al documento desde una matriz de flujos de documentos PDF. |
| [ImportAnnotationsFromFdf](./importannotationsfromfdf/)(const System::String\&) | Importa todas las anotaciones del archivo FDF. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::String\&) | Importa todas las anotaciones del archivo XFDF. |
| [ImportAnnotationsFromXfdf](./importannotationsfromxfdf/)(const System::SharedPtr\<System::IO::Stream\>\&) | Importa todas las anotaciones del flujo de datos XFDF. |
| [ModifyAnnotations](./modifyannotations/)(int32_t, int32_t, const System::SharedPtr\<Annotations::Annotation\>\&) | Modifica las anotaciones del tipo especificado en el rango de páginas especificado. Permite modificar las siguientes propiedades de anotación: Modified, Title, Contents, [Color](../../aspose.pdf/color/), Subject y Open. |
| [ModifyAnnotationsAuthor](./modifyannotationsauthor/)(int32_t, int32_t, const System::String\&, const System::String\&) | Modifica el autor de las anotaciones en el rango de páginas especificado. |
| [PdfAnnotationEditor](./pdfannotationeditor/)() | Inicializa un nuevo objeto [PdfAnnotationEditor](./). |
| [PdfAnnotationEditor](./pdfannotationeditor/)(const System::SharedPtr\<Aspose::Pdf::Document\>\&) | Inicializa un nuevo objeto [PdfAnnotationEditor](./) basado en el *document*. |
| [RedactArea](./redactarea/)(int32_t, System::SharedPtr\<Rectangle\>, System::Drawing::Color) | Redacta el área en la página especificada. Todo el contenido es eliminado. |
## Ver también

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
