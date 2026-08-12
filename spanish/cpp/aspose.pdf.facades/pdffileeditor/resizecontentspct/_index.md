---
title: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct método"
linktitle: "ResizeContentsPct"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct método. Cambia el tamaño del contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes en C++."
type: docs
weight: 3600
url: /es/cpp/aspose.pdf.facades/pdffileeditor/resizecontentspct/
---
## PdfFileEditor::ResizeContentsPct(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene el documento fuente. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | double | Nuevo ancho del contenido de la página en porcentajes. |
| newHeight | double | Nueva altura del contenido de la página en porcentajes. |

### ReturnValue

true si se redimensionó correctamente.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::ResizeContentsPct(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double) method


Redimensiona el contenido de las páginas del documento. Reduce el contenido de la página y agrega márgenes. El nuevo tamaño del contenido se especifica en porcentajes.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::ResizeContentsPct(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double newWidth, double newHeight)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta al documento fuente. |
| destination | const System::String\& | Ruta donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| newWidth | double | Nuevo ancho del contenido de la página en porcentajes. |
| newHeight | double | Nueva altura del contenido de la página en porcentajes. |

### ReturnValue

true si el redimensionamiento fue exitoso.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
