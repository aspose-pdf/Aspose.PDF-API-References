---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: Método PdfFileStamp. Agregar número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente.
type: docs
weight: 130
url: /es/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Agrega el número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente.

```csharp
public void AddPageNumber(string formatString)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | String | Texto del número de página |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Agrega el número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página. El número de página se coloca en la parte inferior de la página centrado horizontalmente.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Cadena de formato para el número de página representada como FormattedText. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Agrega el número de página a las páginas del documento.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | String | Cadena de formato para el número de página. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-centro inferior, 1-derecha inferior, 2-derecha superior, 3 - lados derecho, 4 - centro superior, 5 - izquierda inferior, 6 - lados izquierdo, 7 - izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margen en el borde izquierdo de la página. |
| rightMargin | Single | Margen en el borde derecho de la página. |
| topMargin | Single | Margen en el borde superior de la página. |
| bottomMargin | Single | Margen en el borde inferior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Agrega el número de página en la posición especificada en la página.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | String | Cadena de formato. La cadena de formato puede contener el signo # que será reemplazado por el número de página. |
| x | Single | Coordenada X del número de página. |
| y | Single | Coordenada Y del número de página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Agrega el número de página a las páginas del documento.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que representa el formato del número de página y las propiedades del texto. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-centro inferior, 1-derecha inferior, 2-derecha superior, 3 - lados derecho, 4 - centro superior, 5 - izquierda inferior, 6 - lados izquierdo, 7 - izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margen en el borde izquierdo de la página. |
| rightMargin | Single | Margen en el borde derecho de la página. |
| topMargin | Single | Margen en el borde superior de la página. |
| bottomMargin | Single | Margen en el borde inferior de la página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Agrega el número de página en la posición especificada en la página.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Texto formateado que representa el formato del número de página y las propiedades del texto. La cadena de formato puede contener el signo # que será reemplazado por el número de página. |
| x | Single | Coordenada X del número de página. |
| y | Single | Coordenada Y del número de página. |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Agrega el número de página a las páginas.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formatString | String | Formato del número de página. Este texto puede contener # que será reemplazado por el número de página. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-centro inferior, 1-derecha inferior, 2-derecha superior, 3 - lados derecho, 4 - centro superior, 5 - izquierda inferior, 6 - lados izquierdo, 7 - izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ver También

* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Agrega el número de página a las páginas.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contiene el formato del número de página y las propiedades del texto. Este texto puede contener # que será reemplazado por el número de página. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-centro inferior, 1-derecha inferior, 2-derecha superior, 3 - lados derecho, 4 - centro superior, 5 - izquierda inferior, 6 - lados izquierdo, 7 - izquierda superior. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ver También

* clase [FormattedText](../../formattedtext/)
* clase [PdfFileStamp](../)
* espacio de nombres [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* ensamblado [Aspose.PDF](../../../)