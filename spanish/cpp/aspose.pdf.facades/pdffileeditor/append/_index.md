---
title: "Aspose::Pdf::Facades::PdfFileEditor::Append method"
linktitle: "Append"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::Append method. Añade páginas, que se eligen de una matriz de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos portStreams en el rango startPage a endPage en C++."
type: docs
weight: 500
url: /es/cpp/aspose.pdf.facades/pdffileeditor/append/
---
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Añade páginas, que se eligen de una matriz de documentos en portStreams. El documento resultante incluye firstInputFile y todas las páginas de los documentos de portStreams en el rango startPage a endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Entrada [Pdf](../../../aspose.pdf/) flujo. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Documentos de los que copiar páginas. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) comienza en documentos portStreams. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) termina en documentos portStreams. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Salida [Pdf](../../../aspose.pdf/) flujo. |

### ReturnValue

True para éxito, o false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Añade documentos al documento fuente y guarda el resultado en el objeto response.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::ArrayPtr<System::SharedPtr<System::IO::Stream>> &portStreams, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene el documento fuente. |
| portStreams | const System::ArrayPtr\<System::SharedPtr\<System::IO::Stream\>\>\& | Matriz de flujos con documentos que se agregarán. |
| startPage | int32_t | Página de inicio de la página agregada. |
| endPage | int32_t | Página final de las páginas añadidas. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta donde se guardará el documento. |

### ReturnValue

true si la operación fue exitosa.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, int32_t, int32_t, const System::SharedPtr\<System::IO::Stream\>\&) method


Añade páginas, que se eligen de portStream dentro del rango de startPage a endPage, en portStream al final de firstInputStream.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::SharedPtr<System::IO::Stream> &inputStream, const System::SharedPtr<System::IO::Stream> &portStream, int32_t startPage, int32_t endPage, const System::SharedPtr<System::IO::Stream> &outputStream)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de entrada. |
| portStream | const System::SharedPtr\<System::IO::Stream\>\& | Páginas del flujo de archivo [Pdf](../../../aspose.pdf/). |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) comienza en el flujo portFile. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) termina en el flujo portFile. |
| outputStream | const System::SharedPtr\<System::IO::Stream\>\& | Flujo de archivo de salida [Pdf](../../../aspose.pdf/). |

### ReturnValue

True para éxito, o false.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Añade documentos al documento fuente y guarda el resultado en el objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Nombre del archivo que contiene el documento fuente. |
| portFiles | const System::ArrayPtr\<System::String\>\& | Matriz de nombres de archivo que contienen documentos añadidos. |
| startPage | int32_t | Página inicial de las páginas añadidas. |
| endPage | int32_t | Página final de las páginas añadidas. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto de respuesta donde se guardará el documento. |

### ReturnValue

verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::ArrayPtr\<System::String\>\&, int32_t, int32_t, const System::String\&) method


Añade páginas, que se eligen de los documentos portFiles. El documento resultante incluye firstInputFile y todas las páginas de los documentos portFiles en el rango startPage a endPage.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::ArrayPtr<System::String> &portFiles, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Archivo [Pdf](../../../aspose.pdf/) de entrada. |
| portFiles | const System::ArrayPtr\<System::String\>\& | Documentos de los que copiar páginas. |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) comienza en los documentos portFiles. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) termina en los documentos portFiles. |
| outputFile | const System::String\& | Documento de salida [Pdf](../../../aspose.pdf/). |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::Append(const System::String\&, const System::String\&, int32_t, int32_t, const System::String\&) method


Añade páginas, que se eligen de portFile dentro del rango de startPage a endPage, en portFile al final de firstInputFile.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::Append(const System::String &inputFile, const System::String &portFile, int32_t startPage, int32_t endPage, const System::String &outputFile)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| inputFile | const System::String\& | Archivo [Pdf](../../../aspose.pdf/) de entrada. |
| portFile | const System::String\& | Páginas del archivo [Pdf](../../../aspose.pdf/). |
| startPage | int32_t | [Page](../../../aspose.pdf/page/) comienza en portFile. |
| endPage | int32_t | [Page](../../../aspose.pdf/page/) termina en portFile. |
| outputFile | const System::String\& | Documento de salida [Pdf](../../../aspose.pdf/). |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
