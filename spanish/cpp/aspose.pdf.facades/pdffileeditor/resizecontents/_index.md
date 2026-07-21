---
title: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContents método"
linktitle: "ResizeContents"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContents método. Redimensiona las páginas del documento. Se agregan márgenes en blanco alrededor de la página encogida en C++."
type: docs
weight: 3500
url: /es/cpp/aspose.pdf.facades/pdffileeditor/resizecontents/
---
## PdfFileEditor::ResizeContents(const System::SharedPtr\<Document\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Redimensiona las páginas del documento. Se añaden márgenes en blanco alrededor de la página reducida.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<Document> &source, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<Document\>\& | Documento de origen. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<Document\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Redimensiona las páginas del documento. Se añaden márgenes en blanco alrededor de la página reducida.

```cpp
void Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<Document> &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<Document\>\& | Documento de origen. |
| páginas | System::ArrayPtr\<int32_t\> | Lista de índices de página. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Document](../../../aspose.pdf/document/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene el documento fuente. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | double | Nuevo ancho del contenido de la página en unidades de espacio predeterminadas. |
| newHeight | double | Nueva altura del contenido de la página en unidades de espacio predeterminadas. |

### ReturnValue

True si el redimensionamiento fue exitoso.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Redimensiona el contenido de las páginas del documento.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con el documento de origen. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con el documento de destino. |
| páginas | System::ArrayPtr\<int32_t\> | Arreglo de índices de página. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |

### ReturnValue

Devuelve true si tiene éxito.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Redimensiona el contenido de las páginas del documento. Si la página está reducida, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::SharedPtr<System::IO::Stream> &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia del archivo fuente. |
| páginas | System::ArrayPtr\<int32_t\> | Matriz de páginas a redimensionar. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se guarda el resultado. |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta al documento fuente. |
| destination | const System::String\& | Ruta donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | double | Nuevo ancho del contenido de la página en unidades de espacio predeterminadas. |
| newHeight | double | Nueva altura del contenido de la página en unidades de espacio predeterminadas. |

### ReturnValue

true si el redimensionamiento fue exitoso.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, const System::String\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Redimensiona el contenido de las páginas del documento. Si la página está reducida, se añaden márgenes en blanco alrededor de la página.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, const System::String &destination, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta del documento de origen. |
| destination | const System::String\& | Ruta del documento de destino. |
| páginas | System::ArrayPtr\<int32_t\> | Arreglo de índices de página (el índice de página comienza en 1). |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento de página. |

### ReturnValue

true si el redimensionamiento fue exitoso.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContents(const System::String\&, System::ArrayPtr\<int32_t\>, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Redimensiona el contenido de las páginas del documento. Si la página está reducida, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContents(const System::String &source, System::ArrayPtr<int32_t> pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta al archivo de origen. |
| páginas | System::ArrayPtr\<int32_t\> | Matriz de páginas a redimensionar. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se guarda el resultado. |

### ReturnValue

Verdadero si la operación se completó con éxito.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
