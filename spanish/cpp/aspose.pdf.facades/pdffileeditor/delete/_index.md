---
title: "Aspose::Pdf::Facades::PdfFileEditor::Delete method"
linktitle: "Eliminar"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::Delete method. Elimina las páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo Pdf en C++."
type: docs
weight: 700
url: /es/cpp/aspose.pdf.facades/pdffileeditor/delete/
---
## PdfFileEditor::Delete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Elimina las páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de entrada. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Índice de página fuera del archivo de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de salida. |

### ReturnValue

True para éxito, o false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Elimina páginas especificadas del documento y guarda el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream del documento de origen. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que serán eliminados. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse |

### ReturnValue

True si la operación tuvo éxito.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Elimina páginas especificadas del documento y almacena el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo fuente. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que deben eliminarse. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta donde se almacenará el documento resultante. |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Delete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Elimina las páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Delete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo de entrada. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Índice de página fuera del archivo de entrada. |
| outputFile | const System::String\& | Ruta del archivo de salida. |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
