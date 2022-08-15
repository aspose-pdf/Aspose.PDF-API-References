---
title: PdfAnnotationEditor
second_title: Referencia de API de Aspose.PDF para .NET
description: Representa una clase para trabajar con anotaciones comentarios de documentos PDF.
type: docs
weight: 2420
url: /es/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Representa una clase para trabajar con anotaciones (comentarios) de documentos PDF.

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Inicializa nuevo[`PdfAnnotationEditor`](../pdfannotationeditor) objeto. |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Inicializa nuevo[`PdfAnnotationEditor`](../pdfannotationeditor) objeto sobre la base de la*document* . |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Obtiene la fachada del documento en la que está trabajando. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Inicializa la fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Inicializa la fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Elimina Aspose.Pdf.Document enlazado con una fachada. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Elimina la anotación con el nombre de anotación especificado. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Elimina todas las anotaciones del documento. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Elimina todas las anotaciones del tipo especificado en el documento. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Elimina la fachada. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Exporta anotaciones a flujo. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exporta el contenido de los tipos de anotaciones especificados a XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exporta el contenido de los tipos de anotación especificados a XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Obtiene la lista de anotaciones de los tipos especificados. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Obtiene la lista de anotaciones de los tipos especificados. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Aplana todas las anotaciones en el documento. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Aplana todas las anotaciones en el documento. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Aplana las anotaciones de los tipos especificados. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importa las anotaciones especificadas desde el flujo de datos XFDF. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Importa las anotaciones especificadas del archivo XFDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Importa anotaciones en el documento desde una matriz de otros flujos de documentos PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Importa anotaciones al documento desde una matriz de otros documentos PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Importa las anotaciones especificadas en el documento desde una matriz de otros flujos de documentos PDF. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Importa las anotaciones especificadas en el documento desde una matriz de otros documentos PDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importa todas las anotaciones del flujo de datos XFDF. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importa todas las anotaciones del archivo XFDF. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Modifica las anotaciones del tipo especificado en el rango de página especificado. Admite modificar las propiedades de la siguiente anotación: Modificado, Título, Contenido, Color, Asunto y Abierto. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Modifica el autor de las anotaciones en el rango de páginas especificado. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Redacta el área en la página especificada. Se elimina todo el contenido. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Guarda el documento PDF en el flujo especificado. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Guarda el documento PDF en el archivo especificado. |

### Ver también

* class [SaveableFacade](../saveablefacade)
* espacio de nombres [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* asamblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
