---
title: "Método Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents"
linktitle: "TryResizeContents"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents. Redimensiona el contenido de las páginas en el documento. Si la página se reduce, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en el objeto HttpResponse en C++."
type: docs
weight: 6900
url: /es/cpp/aspose.pdf.facades/pdffileeditor/tryresizecontents/
---
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Redimensiona el contenido de las páginas del documento. Si la página está reducida, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia del archivo fuente. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de páginas a redimensionar. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se guarda el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Redimensiona el contenido de las páginas del documento.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con el documento de origen. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Flujo con el documento de destino. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Arreglo de índices de página. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |

### ReturnValue

Devuelve true si tiene éxito.
## Observaciones



El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en unidades de espacio predeterminadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene el documento fuente. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | double | Nuevo ancho del contenido de la página en unidades de espacio predeterminadas. |
| newHeight | double | Nueva altura del contenido de la página en unidades de espacio predeterminadas. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.
## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&, const System::SharedPtr\<System::Web::HttpResponse\>\&) method


Redimensiona el contenido de las páginas del documento. Si la página está reducida, se añaden márgenes en blanco alrededor de la página. El resultado se almacena en un objeto HttpResponse.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::String &source, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters, const System::SharedPtr<System::Web::HttpResponse> &response)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta al archivo de origen. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de páginas a redimensionar. |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento. |
| response | const System::SharedPtr\<System::Web::HttpResponse\>\& | Objeto HttpResponse donde se guarda el resultado. |

### ReturnValue

true si la operación se completó con éxito; de lo contrario, false.
## Observaciones



El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [HttpResponse](../../../system.web/httpresponse/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::TryResizeContents(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\&) method


Redimensiona el contenido de las páginas del documento. Si la página está reducida, se añaden márgenes en blanco alrededor de la página.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::TryResizeContents(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, const System::SharedPtr<PdfFileEditor::ContentsResizeParameters> &parameters)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta del documento de origen. |
| destination | const System::String\& | Ruta del documento de destino. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Arreglo de índices de página (el índice de página comienza en 1). |
| parámetros | const System::SharedPtr\<PdfFileEditor::ContentsResizeParameters\>\& | Parámetros de redimensionamiento de página. |

### ReturnValue

true si el redimensionamiento fue exitoso.
## Observaciones



El método TryResizeContents es similar al método ResizeContents, excepto que el método TryResizeContents no lanza una excepción si la operación falla.
## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [ContentsResizeParameters](../contentsresizeparameters/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
