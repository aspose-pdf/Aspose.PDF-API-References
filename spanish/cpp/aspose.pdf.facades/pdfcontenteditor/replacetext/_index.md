---
title: "Método Aspose::Pdf::Facades::PdfContentEditor::ReplaceText"
linktitle: "ReplaceText"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Método Aspose::Pdf::Facades::PdfContentEditor::ReplaceText. Reemplaza texto en el archivo PDF en C++."
type: docs
weight: 4500
url: /es/cpp/aspose.pdf.facades/pdfcontenteditor/replacetext/
---
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&) method


Reemplaza texto en el archivo PDF.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | const System::String\& | La cadena a ser reemplazada. |
| destString | const System::String\& | Cadena de reemplazo. |

### ReturnValue

Devuelve true si se realizó el reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) method


Reemplaza texto en el archivo PDF usando el objeto [TextState](../) especificado.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString, const System::SharedPtr<Text::TextState> &textState)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | const System::String\& | Cadena a ser reemplazada |
| destString | const System::String\& | Cadena de reemplazo |
| textState | const System::SharedPtr\<Text::TextState\>\& | [Text](../../../aspose.pdf.text/) estado ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Font etc) |

### ReturnValue

Devuelve true si se realizó el reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, const System::String\&, int32_t) method


Reemplaza texto en el archivo PDF y establece el tamaño de fuente.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, const System::String &destString, int32_t fontSize)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | const System::String\& | Cadena a ser reemplazada. |
| destString | const System::String\& | Cadena de reemplazo. |
| fontSize | int32_t | Tamaño de fuente. |

### ReturnValue

Devuelve true si se realizó el reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, int32_t, const System::String\&) method


Reemplaza texto en el archivo PDF en la página especificada.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, int32_t thePage, const System::String &destString)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | const System::String\& | La cadena a ser reemplazada. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) número (0 para todas las páginas) |
| destString | const System::String\& | Cadena de reemplazo. |

### ReturnValue

Devuelve true si se realizó el reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfContentEditor::ReplaceText(const System::String\&, int32_t, const System::String\&, const System::SharedPtr\<Text::TextState\>\&) method


Reemplaza texto en el archivo PDF en la página especificada. Se puede especificar el objeto [TextState](../) (familia de fuentes, color) para el texto reemplazado.

```cpp
bool Aspose::Pdf::Facades::PdfContentEditor::ReplaceText(const System::String &srcString, int32_t thePage, const System::String &destString, const System::SharedPtr<Text::TextState> &textState)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| srcString | const System::String\& | La cadena a ser reemplazada. |
| thePage | int32_t | [Page](../../../aspose.pdf/page/) número (0 significa "todas las páginas"). |
| destString | const System::String\& | La cadena reemplazada. |
| textState | const System::SharedPtr\<Text::TextState\>\& | [Text](../../../aspose.pdf.text/) estado ([Text](../../../aspose.pdf.text/)[Color](../../../aspose.pdf/color/), Font etc). |

### ReturnValue

Devuelve true si se realizó el reemplazo.

## Ver también

* Class [String](../../../system/string/)
* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [TextState](../../../aspose.pdf.text/textstate/)
* Class [PdfContentEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
