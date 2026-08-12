---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf method"
linktitle: "ExportAnnotationsXfdf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf method. Exporta el contenido de los tipos de anotaciones especificados a XFDF en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/
---
## PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Exporta el contenido de los tipos de anotaciones especificados a XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr<System::IO::Stream> &xmlOutputStream, int32_t start, int32_t end, const System::ArrayPtr<Annotations::AnnotationType> &annotTypes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlOutputStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo XFDF de salida. |
| inicio | int32_t | Página de inicio desde la cual se exportarán las anotaciones del documento. |
| end | int32_t | Página final hasta la cual se exportarán las anotaciones del documento. |
| annotTypes | const System::ArrayPtr\<Annotations::AnnotationType\>\& | La matriz de tipos de anotación que deben exportarse. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) method


Exporta el contenido de los tipos de anotación especificados a XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ExportAnnotationsXfdf(const System::SharedPtr<System::IO::Stream> &xmlOutputStream, int32_t start, int32_t end, const System::ArrayPtr<System::String> &annotTypes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xmlOutputStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo XFDF de salida. |
| inicio | int32_t | Página de inicio desde la cual se exportarán las anotaciones del documento. |
| end | int32_t | Página final hasta la cual se exportarán las anotaciones del documento. |
| annotTypes | const System::ArrayPtr\<System::String\>\& | La matriz de tipos de anotación que deben exportarse. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
