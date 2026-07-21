---
title: "Método Aspose::Pdf::Facades::PdfFileEditor::TryDelete"
linktitle: "TryDelete"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryDelete método. Elimina las páginas especificadas por una matriz de números del archivo de entrada y guarda un nuevo archivo Pdf en C++."
type: docs
weight: 6400
url: /es/cpp/aspose.pdf.facades/pdffileeditor/trydelete/
---
## PdfFileEditor::TryDelete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Elimina las páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de entrada. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Índice de página fuera del archivo de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de salida. |

### ReturnValue

True para éxito, o false.
## Observaciones



El método TryDelete es similar al método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Elimina páginas especificadas del documento y guarda el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Stream del documento de origen. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que serán eliminados. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryDelete es similar al método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Elimina páginas especificadas del documento y almacena el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo fuente. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que deben eliminarse. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta donde se almacenará el documento resultante. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryDelete es similar al método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryDelete(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Elimina las páginas especificadas por una matriz de números del archivo de entrada, y guarda como un nuevo archivo [Pdf](../../../aspose.pdf/).

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryDelete(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo de entrada. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Índice de página fuera del archivo de entrada. |
| outputFile | const System::String\& | Ruta del archivo de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryDelete es similar al método Delete, excepto que el método TryDelete no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
