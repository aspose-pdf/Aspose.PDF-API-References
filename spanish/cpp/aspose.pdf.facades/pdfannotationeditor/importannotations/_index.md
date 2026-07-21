---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations method"
linktitle: "ImportAnnotations"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations method. Importa anotaciones al documento desde una matriz de flujos de documentos PDF de otro documento en C++."
type: docs
weight: 900
url: /es/cpp/aspose.pdf.facades/pdfannotationeditor/importannotations/
---
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&) method


Importa anotaciones al documento desde una matriz de flujos de documentos PDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &annotFileStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotFileStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | La matriz de flujos de documentos PDF que contienen anotaciones de origen. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Importa las anotaciones especificadas al documento desde una matriz de flujos de documentos PDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &annotFileStream, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotFileStream | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | La matriz de flujos de documentos PDF que contienen anotaciones de origen. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | Los tipos de anotación que se importarán. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::String\>\&) method


Importa anotaciones al documento desde una matriz de otros documentos PDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::String> &annotFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotFile | const System::ArrayPtr\<System::String\>\& | La matriz de rutas de documentos PDF que contienen anotaciones de origen. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr\<System::String\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Importa las anotaciones especificadas al documento desde una matriz de otros documentos PDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotations(const System::ArrayPtr<System::String> &annotFile, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| annotFile | const System::ArrayPtr\<System::String\>\& | La matriz de rutas de documentos PDF que contienen anotaciones de origen. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | La matriz de tipos de anotación a importar. |

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [String](../../../system/string/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
