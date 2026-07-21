---
title: "Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks método"
linktitle: "SplitToBulks"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks método. Divide el archivo Pdf en varios documentos. Los documentos pueden ser de una sola página o de varias páginas en C++."
type: docs
weight: 5900
url: /es/cpp/aspose.pdf.facades/pdffileeditor/splittobulks/
---
## PdfFileEditor::SplitToBulks(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Divide el archivo [Pdf](../../../aspose.pdf/) en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia de entrada PDF. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | La página de inicio y la página final de cada documento. |

### ReturnValue

Flujos PDF de salida, cada flujo almacena en búfer un documento PDF.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::SplitToBulks(const System::String\&, const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\&) method


Divide el archivo [Pdf](../../../aspose.pdf/) en varios documentos. Los documentos pueden ser de una sola página o de varias páginas.

```cpp
System::ArrayPtr<System::SharedPtr<System::IO::MemoryStream>> Aspose::Pdf::Facades::PdfFileEditor::SplitToBulks(const System::String &inputFile, const System::ArrayPtr<System::ArrayPtr<int32_t>> &numberOfPage)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Archivo PDF de entrada. |
| numberOfPage | const System::ArrayPtr\<System::ArrayPtr\<int32_t\>\>\& | Arreglo que contiene un arreglo de elementos double, que son las páginas de inicio y fin del documento. |

### ReturnValue

Flujos PDF de salida, cada flujo almacena en búfer un documento PDF.

## Ver también

* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [MemoryStream](../../../system.io/memorystream/)
* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
