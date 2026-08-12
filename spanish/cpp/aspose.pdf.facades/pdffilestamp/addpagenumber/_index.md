---
title: "Método Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber"
linktitle: "AddPageNumber"
second_title: "Referencia de API de Aspose.PDF para C++"
description: "Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber method. Añade el número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página. El número de página se coloca en la parte inferior de la página centrado horizontalmente en C++."
type: docs
weight: 400
url: /es/cpp/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&) method


Añade el número de página a la página. El número de [Page](../../../aspose.pdf/page/) puede contener el signo # que será reemplazado por el número de página. El número de [Page](../../../aspose.pdf/page/) se coloca en la parte inferior de la página centrado horizontalmente.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Cadena de formato para el número de página representada como [FormattedText](../../formattedtext/). |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, float, float) method


Agrega número de página en la posición especificada de la página.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, float x, float y)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Texto formateado que representa el formato del número de página y las propiedades del texto. La cadena de formato puede contener el signo # que será reemplazado por el número de página. |
| x | float | Coordenada X del número de página. |
| y | float | Coordenada Y del número de página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, int32_t) method


Agrega número de página a las páginas.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, int32_t position)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Objeto [FormattedText](../../formattedtext/) que contiene el formato del número de página y las propiedades del texto. Este texto puede contener # que será reemplazado por el número de página. |
| posición | int32_t | Posición donde se colocará el número de página en la página. 0‑centro inferior, 1‑derecha inferior, 2‑derecha superior, 3‑lado derecho, 4‑centro superior, 5‑izquierda inferior, 6‑lado izquierdo, 7‑izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::SharedPtr\<FormattedText\>\&, int32_t, float, float, float, float) method


Agrega número de página a las páginas del documento.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::SharedPtr<FormattedText> &formattedText, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | const System::SharedPtr\<FormattedText\>\& | Objeto [FormattedText](../../formattedtext/) que representa el formato del número de página y las propiedades del texto. |
| posición | int32_t | Posición donde se colocará el número de página en la página. 0‑centro inferior, 1‑derecha inferior, 2‑derecha superior, 3‑lado derecho, 4‑centro superior, 5‑izquierda inferior, 6‑lado izquierdo, 7‑izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margen en el borde izquierdo de la página. |
| rightMargin | float | Margen en el borde derecho de la página. |
| topMargin | float | Margen en el borde superior de la página. |
| bottomMargin | float | Margen en el borde inferior de la página. |

## Ver también

* Typedef [SharedPtr](../../../system/sharedptr/)
* Class [FormattedText](../../formattedtext/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&) method


Agregar número de página al archivo. El número de [Page](../../../aspose.pdf/page/) puede contener el signo # que será reemplazado por el número de la página. El número de [Page](../../../aspose.pdf/page/) se coloca en la parte inferior de la página centrado horizontalmente.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | const System::String\& | [Text](../../../aspose.pdf.text/) del número de página |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, float, float) method


Agrega número de página en la posición especificada de la página.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, float x, float y)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | const System::String\& | Cadena de formato. La cadena de formato puede contener el signo # que será reemplazado por el número de página. |
| x | float | Coordenada X del número de página. |
| y | float | Coordenada Y del número de página. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, int32_t) method


Agrega número de página a las páginas.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, int32_t position)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | const System::String\& | Formato del número de página. Este texto puede contener # que será reemplazado por el número de página. |
| posición | int32_t | Posición donde se colocará el número de página en la página. 0‑centro inferior, 1‑derecha inferior, 2‑derecha superior, 3‑lado derecho, 4‑centro superior, 5‑izquierda inferior, 6‑lado izquierdo, 7‑izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## PdfFileStamp::AddPageNumber(const System::String\&, int32_t, float, float, float, float) method


Agrega número de página a las páginas del documento.

```cpp
void Aspose::Pdf::Facades::PdfFileStamp::AddPageNumber(const System::String &formatString, int32_t position, float leftMargin, float rightMargin, float topMargin, float bottomMargin)
```


| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | const System::String\& | Cadena de formato para el número de página. |
| posición | int32_t | Posición donde se colocará el número de página en la página. 0‑centro inferior, 1‑derecha inferior, 2‑derecha superior, 3‑lado derecho, 4‑centro superior, 5‑izquierda inferior, 6‑lado izquierdo, 7‑izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | float | Margen en el borde izquierdo de la página. |
| rightMargin | float | Margen en el borde derecho de la página. |
| topMargin | float | Margen en el borde superior de la página. |
| bottomMargin | float | Margen en el borde inferior de la página. |

## Ver también

* Class [String](../../../system/string/)
* Class [PdfFileStamp](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
