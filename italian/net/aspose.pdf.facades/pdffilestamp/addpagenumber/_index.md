---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: Metodo PdfFileStamp. Aggiungere numero della pagina al file. Il testo del numero della pagina potrebbe contenere un segno che verrà sostituito con il numero della pagina. Il numero della pagina viene posto in fondo alla pagina centrato horizontalmente.
type: docs
weight: 130
url: /it/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Aggiungi numero di pagina al file. Il testo del numero di pagina può contenere il segno # che sarà sostituito con il numero della pagina. Il numero di pagina è posizionato in fondo alla pagina centrato orizzontalmente.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Testo del numero di pagina |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il segno # che sarà sostituito con il numero di pagina. Il numero di pagina è posizionato in fondo alla pagina centrato orizzontalmente.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Stringa di formato per il numero di pagina rappresentata come FormattedText. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Aggiunge il numero di pagina alle pagine del documento.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Stringa di formato per il numero di pagina. |
| position | Int32 | Posizione in cui il numero di pagina sarà posizionato sulla pagina. 0-in fondo al centro, 1-in fondo a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro, 5 - in fondo a sinistra, 6 - lati a sinistra, 7 - in alto a sinistra. Puoi usare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margine sul bordo sinistro della pagina. |
| rightMargin | Single | Margine sul bordo destro della pagina. |
| topMargin | Single | Margine sul bordo superiore della pagina. |
| bottomMargin | Single | Margine sul bordo inferiore della pagina. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Aggiunge il numero di pagina nella posizione specificata sulla pagina.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Stringa di formato. La stringa di formato può contenere il segno # che sarà sostituito con il numero di pagina. |
| x | Single | Coordinata X del numero di pagina. |
| y | Single | Coordinata Y del numero di pagina. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Aggiunge il numero di pagina alle pagine del documento.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che rappresenta il formato del numero di pagina e le proprietà del testo. |
| position | Int32 | Posizione in cui il numero di pagina sarà posizionato sulla pagina. 0-in fondo al centro, 1-in fondo a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro, 5 - in fondo a sinistra, 6 - lati a sinistra, 7 - in alto a sinistra. Puoi usare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margine sul bordo sinistro della pagina. |
| rightMargin | Single | Margine sul bordo destro della pagina. |
| topMargin | Single | Margine sul bordo superiore della pagina. |
| bottomMargin | Single | Margine sul bordo inferiore della pagina. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Aggiunge il numero di pagina nella posizione specificata sulla pagina.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Testo formattato che rappresenta il formato del numero di pagina e le proprietà del testo. La stringa di formato può contenere il segno # che sarà sostituito con il numero di pagina. |
| x | Single | Coordinata X del numero di pagina. |
| y | Single | Coordinata Y del numero di pagina. |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Aggiunge il numero di pagina alle pagine.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formatString | String | Formato del numero di pagina. Questo testo può contenere # che sarà sostituito con il numero di pagina. |
| position | Int32 | Posizione in cui il numero di pagina sarà posizionato sulla pagina. 0-in fondo al centro, 1-in fondo a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro, 5 - in fondo a sinistra, 6 - lati a sinistra, 7 - in alto a sinistra. Puoi usare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### See Also

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Aggiunge il numero di pagina alle pagine.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Type | Description |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che contiene il formato del numero di pagina e le proprietà del testo. Questo testo può contenere # che sarà sostituito con il numero di pagina. |
| position | Int32 | Posizione in cui il numero di pagina sarà posizionato sulla pagina. 0-in fondo al centro, 1-in fondo a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro, 5 - in fondo a sinistra, 6 - lati a sinistra, 7 - in alto a sinistra. Puoi usare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Examples

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### See Also

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)