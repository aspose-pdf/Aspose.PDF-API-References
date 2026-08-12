---
title: "Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare método"
linktitle: "Compare"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare método. Compara dos documentos. Las páginas se comparan una a una. Las páginas de los documentos comparados se copian una tras otra en el documento resultante. Primero la primera página del primer documento, luego la primera página del segundo documento. Después sigue la segunda del primer documento y luego la segunda del segundo documento, etc. Puedes abrirlo en Adobe Acrobat en vista de doble página para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha en C++."
type: docs
weight: 100
url: /es/cpp/aspose.pdf.comparison/sidebysidepdfcomparer/compare/
---
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compara dos documentos. Las páginas se comparan una a una. Las páginas de los documentos comparados se copian una tras otra en el documento resultante. Primero la primera página del primer documento, luego la primera página del segundo documento. Después la segunda del primer documento y luego la segunda del segundo documento, etc. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | El primer documento a comparar. |
| document2 | const System::SharedPtr\<Document\>\& | El segundo documento a comparar. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de destino para guardar un resultado de comparación. |
| opciones | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Las opciones de comparación. |

### ReturnValue

El resultado de la comparación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<Document\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compara dos documentos. Las páginas se comparan una a una. Las páginas de los documentos comparados se copian una tras otra en el documento resultante. Primero la primera página del primer documento, luego la primera página del segundo documento. Después la segunda del primer documento y luego la segunda del segundo documento, etc. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha.

```cpp
static System::SharedPtr<SideBySideDocsComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Document> &document1, const System::SharedPtr<Document> &document2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| document1 | const System::SharedPtr\<Document\>\& | El primer documento a comparar. |
| document2 | const System::SharedPtr\<Document\>\& | El segundo documento a comparar. |
| targetPdfPath | const System::String\& | La ruta al archivo PDF para guardar un resultado de comparación. |
| opciones | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Las opciones de comparación. |

### ReturnValue

El resultado de la comparación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySideDocsComparisonResult](../../sidebysidedocscomparisonresult/)
* Class [Document](../../../aspose.pdf/document/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compara dos páginas. El resultado se guarda en un documento PDF en el que la primera página se escribe primero, y luego la segunda. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::SharedPtr<System::IO::Stream> &targetStream, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | La primera página a comparar. |
| page2 | const System::SharedPtr\<Page\>\& | La primera página a comparar. |
| targetStream | const System::SharedPtr\<System::IO::Stream\>\& | El flujo de destino para guardar un resultado de comparación. |
| opciones | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Las opciones de comparación. |

### ReturnValue

El resultado de la comparación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [Stream](../../../system.io/stream/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
## SideBySidePdfComparer::Compare(const System::SharedPtr\<Page\>\&, const System::SharedPtr\<Page\>\&, const System::String\&, const System::SharedPtr\<SideBySideComparisonOptions\>\&) method


Compara dos páginas. El resultado se guarda en un documento PDF en el que la primera página se escribe primero, y luego la segunda. Puede abrirlo en Adobe Acrobat en vista de dos páginas para ver los cambios lado a lado. Las eliminaciones se anotan en la página izquierda, y las inserciones se anotan en la página derecha.

```cpp
static System::SharedPtr<SideBySidePagesComparisonResult> Aspose::Pdf::Comparison::SideBySidePdfComparer::Compare(const System::SharedPtr<Page> &page1, const System::SharedPtr<Page> &page2, const System::String &targetPdfPath, const System::SharedPtr<SideBySideComparisonOptions> &options)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page1 | const System::SharedPtr\<Page\>\& | La primera página a comparar. |
| page2 | const System::SharedPtr\<Page\>\& | La primera página a comparar. |
| targetPdfPath | const System::String\& | La ruta al archivo PDF para guardar un resultado de comparación. |
| opciones | const System::SharedPtr\<SideBySideComparisonOptions\>\& | Las opciones de comparación. |

### ReturnValue

El resultado de la comparación.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [SideBySidePagesComparisonResult](../../sidebysidepagescomparisonresult/)
* Class [Page](../../../aspose.pdf/page/)
* Class [String](../../../system/string/)
* Class [SideBySideComparisonOptions](../../sidebysidecomparisonoptions/)
* Class [SideBySidePdfComparer](../)
* Namespace [Aspose::Pdf::Comparison](../../)
* Library [Aspose.PDF for C++](../../../)
