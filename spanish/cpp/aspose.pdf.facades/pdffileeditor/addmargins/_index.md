---
title: "Método Aspose::Pdf::Facades::PdfFileEditor::AddMargins"
linktitle: "AddMargins"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfFileEditor::AddMargins. Redimensiona el contenido de la página y agrega los márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas en C++."
type: docs
weight: 200
url: /es/cpp/aspose.pdf.facades/pdffileeditor/addmargins/
---
## PdfFileEditor::AddMargins(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene el documento fuente. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margen. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margen. |
| topMargin | double | Margen superior. |
| bottomMargin | double | Margen inferior. |

### ReturnValue

true si la operación fue exitosa.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMargins(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en unidades de espacio predeterminadas.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMargins(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta al documento fuente. |
| destination | const System::String\& | Ruta donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margen. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margen. |
| topMargin | double | Margen superior. |
| bottomMargin | double | Margen inferior. |

### ReturnValue

true si el redimensionamiento fue exitoso.

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
