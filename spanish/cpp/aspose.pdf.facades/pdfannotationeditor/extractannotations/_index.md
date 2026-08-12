---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations method"
linktitle: "ExtractAnnotations"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations method. Obtiene la lista de anotaciones de los tipos especificados en C++."
type: docs
weight: 600
url: /es/cpp/aspose.pdf.facades/pdfannotationeditor/extractannotations/
---
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Obtiene la lista de anotaciones de los tipos especificados.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, const System::ArrayPtr<Annotations::AnnotationType> &annotTypes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inicio | int32_t | Página de inicio desde la cual se seleccionarán las anotaciones. |
| end | int32_t | Página final hasta la cual se seleccionarán las anotaciones. |
| annotTypes | const System::ArrayPtr\<Annotations::AnnotationType\>\& | La matriz de tipos de anotación necesarios. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ExtractAnnotations(int32_t, int32_t, const System::ArrayPtr\<System::String\>\&) method


Obtiene la lista de anotaciones de los tipos especificados.

```cpp
System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Annotations::Annotation>>> Aspose::Pdf::Facades::PdfAnnotationEditor::ExtractAnnotations(int32_t start, int32_t end, const System::ArrayPtr<System::String> &annotTypes)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inicio | int32_t | Página de inicio desde la cual se seleccionarán las anotaciones. |
| end | int32_t | Página final hasta la cual se seleccionarán las anotaciones. |
| annotTypes | const System::ArrayPtr\<System::String\>\& | La matriz de tipos de anotación necesarios. |

### ReturnValue

[Annotations](../../../aspose.pdf.annotations/) list.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [IList](../../../system.collections.generic/ilist/)
* Class [Annotation](../../../aspose.pdf.annotations/annotation/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
