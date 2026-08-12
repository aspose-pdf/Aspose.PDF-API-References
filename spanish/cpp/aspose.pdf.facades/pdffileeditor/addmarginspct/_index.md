---
title: "Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct método"
linktitle: "AddMarginsPct"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct método. Redimensiona el contenido de la página y agrega los márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página en C++."
type: docs
weight: 300
url: /es/cpp/aspose.pdf.facades/pdffileeditor/addmarginspct/
---
## PdfFileEditor::AddMarginsPct(const System::SharedPtr\<System::IO::Stream\>\&, const System::SharedPtr\<System::IO::Stream\>\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct(const System::SharedPtr<System::IO::Stream> &source, const System::SharedPtr<System::IO::Stream> &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::SharedPtr\<System::IO::Stream\>\& | Flujo que contiene el documento fuente. |
| destination | const System::SharedPtr\<System::IO::Stream\>\& | Secuencia donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margen en porcentajes del tamaño inicial de la página. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margen en porcentajes del tamaño inicial de la página. |
| topMargin | double | Margen superior en porcentajes del tamaño inicial de la página. |
| bottomMargin | double | Margen inferior en porcentajes del tamaño inicial de la página. |

### ReturnValue

true si la acción se realizó con éxito.

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [Stream](../../../system.io/stream/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileEditor::AddMarginsPct(const System::String\&, const System::String\&, const System::ArrayPtr\<int32_t\>\&, double, double, double, double) method


Redimensiona el contenido de la página y agrega márgenes especificados. Los márgenes se especifican en porcentajes del tamaño inicial de la página.

```cpp
bool Aspose::Pdf::Facades::PdfFileEditor::AddMarginsPct(const System::String &source, const System::String &destination, const System::ArrayPtr<int32_t> &pages, double leftMargin, double rightMargin, double topMargin, double bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| origen | const System::String\& | Ruta al documento fuente. |
| destination | const System::String\& | Ruta donde se guardará el documento resultante. |
| páginas | const System::ArrayPtr\<int32_t\>\& | Matriz de índices de página. Si es nulo, se procesarán todas las páginas del documento. |
| leftMargin | double | [Left](../../../aspose.pdf/left/) margen en porcentajes del tamaño inicial de la página. |
| rightMargin | double | [Right](../../../aspose.pdf/right/) margen en porcentajes del tamaño inicial de la página. |
| topMargin | double | Margen superior en porcentajes del tamaño inicial de la página. |
| bottomMargin | double | Margen inferior en porcentajes del tamaño inicial de la página. |

### ReturnValue

true si el redimensionamiento fue exitoso

## Ver también

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [PdfFileEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
