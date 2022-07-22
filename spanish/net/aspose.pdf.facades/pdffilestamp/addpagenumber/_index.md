---
title: AddPageNumber
second_title: Referencia de API de Aspose.PDF para .NET
description: Agregar número de página al archivo. El texto del número de página puede contener el signo  que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente.
type: docs
weight: 170
url: /es/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Agregar número de página al archivo. El texto del número de página puede contener el signo # que será reemplazado por el número de la página. El número de página se coloca en la parte inferior de la página centrado horizontalmente.

```csharp
public void AddPageNumber(string formatString)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formatString | String | Texto del número de página |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Ver también

* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Agrega el número de página a la página. El número de página puede contener el signo # que será reemplazado por el número de página. El número de página se coloca en la parte inferior de la página, centrado horizontalmente.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | La cadena de formato para el número de página se representa como FormattedText. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Ver también

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Agrega el número de página a las páginas del documento.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formatString | String | Cadena de formato para el número de página. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-abajo en el medio, 1-abajo a la derecha, 2-arriba a la derecha, 3 - lados a la derecha, 4 - medio superior, 5 - abajo a la izquierda, 6 - lados a la izquierda,7 - arriba a la izquierda. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margen en el borde izquierdo de la página. |
| rightMargin | Single | Margen en el borde derecho de la página. |
| topMargin | Single | Margen en el borde superior de la página. |
| bottomMargin | Single | Margen en el borde inferior de la página. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ver también

* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Agrega el número de página en la posición especificada en la página.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formatString | String | Cadena de formato. La cadena de formato puede contener el signo # que se reemplazará con el número de página. |
| x | Single | Coordenada X del número de página. |
| y | Single | Coordenada Y del número de página. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ver también

* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Agrega el número de página a las páginas del documento.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que representa el formato del número de página y las propiedades del texto. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-abajo en el medio, 1-abajo a la derecha, 2-arriba a la derecha, 3 - lados a la derecha, 4 - medio superior, 5 - abajo a la izquierda, 6 - lados a la izquierda,7 - arriba a la izquierda. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margen en el borde izquierdo de la página. |
| rightMargin | Single | Margen en el borde derecho de la página. |
| topMargin | Single | Margen en el borde superior de la página. |
| bottomMargin | Single | Margen en el borde inferior de la página. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Ver también

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Agrega el número de página en la posición especificada en la página.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Texto formateado que representa el formato del número de página y las propiedades del texto. La cadena de formato puede contener el signo # que se reemplazará con el número de página. |
| x | Single | Coordenada X del número de página. |
| y | Single | Coordenada Y del número de página. |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Ver también

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Agrega el número de página a las páginas.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formatString | String | Formato del número de página. Este texto puede contener # que será reemplazado por el número de página. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-abajo en el medio, 1-abajo a la derecha, 2-arriba a la derecha, 3 - lados a la derecha, 4 - medio superior, 5 - abajo a la izquierda, 6 - lados a la izquierda,7 - arriba a la izquierda. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ver también

* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Agrega el número de página a las páginas.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| formattedText | FormattedText | Objeto FormattedText que contiene el formato del número de página y las propiedades del texto. Este texto puede contener # que será reemplazado por el número de página. |
| position | Int32 | Posición donde se colocará el número de página en la página. 0-abajo en el medio, 1-abajo a la derecha, 2-arriba a la derecha, 3 - lados a la derecha, 4 - medio superior, 5 - abajo a la izquierda, 6 - lados a la izquierda,7 - arriba a la izquierda. Puede usar las siguientes constantes: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Ejemplos

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Ver también

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* espacio de nombres [Aspose.Pdf.Facades](../../pdffilestamp)
* asamblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
