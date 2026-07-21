---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToPages método"
linktitle: "SplitToPages"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToPages método. Divide el archivo Pdf en documentos de una sola página en C++."
type: docs
weight: 6100
url: /es/cpp/aspose.pdf.facades/pdffileeditor/splittopages/
---
## PdfFileEditor::SplitToPages(const System::SharedPtr\<System::IO::Stream\>\&) method


Divide el archivo [Pdf](../../../aspose.pdf/) en documentos de una sola página.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::SharedPtr<System::IO::Stream> &inputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Entrada [Pdf](../../../aspose.pdf/) flujo. |

### ReturnValue

Matriz de flujos de memoria que contienen las páginas del documento.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::SharedPtr\<System::IO::Stream\>\&, const System::String\&) method


Divida el archivo [Pdf](../../../aspose.pdf/) en documentos de una sola página y guárdelo en la ruta especificada. La ruta se especifica mediante el nombre de campo temaplate.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::SharedPtr<System::IO::Stream> &inputStream, const System::String &fileNameTemplate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo del documento fuente. |
| fileNameTemplate | const System::String\& | Plantilla del nombre de archivo resultante. Debe contener NUM% que se reemplaza con el número de página. Por ejemplo, si se especifica c:/dir/pageNUM%.pdf, los archivos resultantes tendrán los siguientes nombres: c:/dir/page1.pdf, c:/dir/page2.pdf, etc. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::String\&) method


Divide el archivo PDF en documentos de una sola página.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::String &inputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Nombre de archivo PDF de entrada. |

### ReturnValue

Secuencias de salida PDF, cada secuencia almacena en búfer un documento PDF de una sola página.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToPages(const System::String\&, const System::String\&) method


Divida el archivo [Pdf](../../../aspose.pdf/) en documentos de una sola página y guárdelo en la ruta especificada. La ruta se especifica mediante el nombre de campo temaplate.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::SplitToPages(const System::String &inputFile, const System::String &fileNameTemplate)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Nombre de archivo de entrada. |
| fileNameTemplate | const System::String\& | Plantilla del nombre de archivo resultante. Debe contener NUM% que se reemplaza con el número de página. Por ejemplo, si se especifica c:/dir/pageNUM%.pdf, los archivos resultantes tendrán los siguientes nombres: c:/dir/page1.pdf, c:/dir/page2.pdf, etc. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
