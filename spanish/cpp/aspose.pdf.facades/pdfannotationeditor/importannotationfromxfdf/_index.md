---
title: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf método"
linktitle: "ImportAnnotationFromXfdf"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf método. Importa todas las anotaciones del flujo de datos XFDF en C++."
type: docs
weight: 800
url: /es/cpp/aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/
---
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr\<System::IO::Stream\>\&) method


Importa todas las anotaciones del flujo de datos XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr<System::IO::Stream> &xfdfStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xfdfStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de datos XFDF de entrada. |

## Deprecated
El método está obsoleto, por favor use ImportAnnotationsFromXfdf en su lugar

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Importa las anotaciones especificadas del flujo de datos XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::SharedPtr<System::IO::Stream> &xfdfStream, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xfdfStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de datos XFDF de entrada. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | La matriz de tipos de anotación a importar. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String\&) method


Importa todas las anotaciones del archivo XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String &xfdfFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xfdfFile | const System::String\& | El archivo XFDF de entrada. |

## Deprecated
El método está obsoleto, por favor use ImportAnnotationsFromXfdf en su lugar

## Ver también

* Class [String](../../../system/string/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String\&, const System::ArrayPtr\<Annotations::AnnotationType\>\&) method


Importa las anotaciones especificadas del archivo XFDF.

```cpp
void Aspose::Pdf::Facades::PdfAnnotationEditor::ImportAnnotationFromXfdf(const System::String &xfdfFile, const System::ArrayPtr<Annotations::AnnotationType> &annotType)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| xfdfFile | const System::String\& | El archivo XFDF de entrada. |
| annotType | const System::ArrayPtr\<Annotations::AnnotationType\>\& | La matriz de anotaciones a importar. |

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Enum [AnnotationType](../../../aspose.pdf.annotations/annotationtype/)
* Class [PdfAnnotationEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
