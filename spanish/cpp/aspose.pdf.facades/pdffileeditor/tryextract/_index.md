---
title: "Aspose::Pdf::Facades::PdfFileEditor::TryExtract método"
linktitle: "TryExtract"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::TryExtract método. Extrae páginas especificadas por una matriz de números, guarda como un nuevo archivo Pdf en C++."
type: docs
weight: 6500
url: /es/cpp/aspose.pdf.facades/pdffileeditor/tryextract/
---
## PdfFileEditor::TryExtract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::IO::Stream\>\&) method


Extrae páginas especificadas por una matriz de números, guarda como un nuevo archivo [Pdf](../../../aspose.pdf/)

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de entrada. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Índice de página fuera del archivo de entrada. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de salida. |

### ReturnValue

True para éxito, o false.
## Observaciones



El método TryExtract es similar al método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo del documento de origen. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que se extraerán. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryExtract es similar al método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Extrae páginas especificadas del archivo fuente y almacena el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo fuente. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Matriz de números de página que se extraerán. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se almacenará el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryExtract es similar al método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::String\&) method


Extrae páginas especificadas por una matriz de números, y las guarda como un nuevo archivo PDF.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, const System::ArrayPtr<int32_t> &pageNumber, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo de entrada. |
| pageNumber | const System::ArrayPtr\<int32_t\>\& | Índice de página fuera del archivo de entrada. |
| outputFile | const System::String\& | Ruta del archivo de salida. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryExtract es similar al método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryExtract(const System::String\&, int32_t, int32_t, const System::String\&) method


Extrae páginas del archivo de entrada,guarda como un nuevo archivo [Pdf](../../../aspose.pdf/)

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryExtract(const System::String &inputFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Ruta del archivo [Pdf](../../../aspose.pdf/) de entrada. |
| startPage | int32_t | Número de página inicial. |
| endPage | int32_t | Número de página final. |
| outputFile | const System::String\& | Ruta del archivo [Pdf](../../../aspose.pdf/) de salida. |

### ReturnValue

True para éxito, o false.
## Observaciones



El método TryExtract es similar al método Extract, excepto que el método TryExtract no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
