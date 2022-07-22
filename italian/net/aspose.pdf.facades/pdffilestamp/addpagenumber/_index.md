---
title: AddPageNumber
second_title: Aspose.PDF per .NET API Reference
description: Aggiungi il numero di pagina al file. Il testo del numero di pagina può contenere il segno  che verrà sostituito con il numero della pagina. Il numero di pagina è posizionato nella parte inferiore della pagina centrato orizzontalmente.
type: docs
weight: 170
url: /it/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Aggiungi il numero di pagina al file. Il testo del numero di pagina può contenere il segno # che verrà sostituito con il numero della pagina. Il numero di pagina è posizionato nella parte inferiore della pagina centrato orizzontalmente.

```csharp
public void AddPageNumber(string formatString)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formatString | String | Testo del numero di pagina |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Guarda anche

* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Aggiunge il numero di pagina alla pagina. Il numero di pagina può contenere il simbolo # che verrà sostituito con il numero di pagina. Il numero di pagina è posizionato nella parte inferiore della pagina centrato orizzontalmente.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | La stringa di formato per il numero di pagina rappresenta come FormattedText. |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Guarda anche

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Aggiunge il numero di pagina alle pagine del documento.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formatString | String | Formatta la stringa per il numero di pagina. |
| position | Int32 | Posizione in cui verrà posizionato il numero di pagina sulla pagina. 0-in basso al centro, 1-in basso a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro,5 - in basso a sinistra,6 - lati a sinistra,7 - in alto a sinistra. È possibile utilizzare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margine sul bordo sinistro della pagina. |
| rightMargin | Single | Margine sul bordo destro della pagina. |
| topMargin | Single | Margine sul bordo superiore della pagina. |
| bottomMargin | Single | Margine sul bordo inferiore della pagina. |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Guarda anche

* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Aggiunge il numero di pagina nella posizione specificata nella pagina.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formatString | String | Stringa di formato. La stringa di formato può contenere il segno # che verrà sostituito con il numero di pagina. |
| x | Single | Coordinata X del numero di pagina. |
| y | Single | Coordinata Y del numero di pagina. |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Guarda anche

* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Aggiunge il numero di pagina alle pagine del documento.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che rappresenta il formato del numero di pagina e le proprietà del testo. |
| position | Int32 | Posizione in cui verrà posizionato il numero di pagina sulla pagina. 0-in basso al centro, 1-in basso a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro,5 - in basso a sinistra,6 - lati a sinistra,7 - in alto a sinistra. È possibile utilizzare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Margine sul bordo sinistro della pagina. |
| rightMargin | Single | Margine sul bordo destro della pagina. |
| topMargin | Single | Margine sul bordo superiore della pagina. |
| bottomMargin | Single | Margine sul bordo inferiore della pagina. |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Guarda anche

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Aggiunge il numero di pagina nella posizione specificata nella pagina.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Testo formattato che rappresenta il formato del numero di pagina e le proprietà del testo. La stringa di formato può contenere il segno # che verrà sostituito con il numero di pagina. |
| x | Single | Coordinata X del numero di pagina. |
| y | Single | Coordinata Y del numero di pagina. |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Guarda anche

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Aggiunge il numero di pagina alle pagine.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formatString | String | Formato del numero di pagina. Questo testo può contenere # che verrà sostituito con il numero di pagina. |
| position | Int32 | Posizione in cui verrà posizionato il numero di pagina sulla pagina. 0-in basso al centro, 1-in basso a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro,5 - in basso a sinistra,6 - lati a sinistra,7 - in alto a sinistra. È possibile utilizzare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Guarda anche

* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Aggiunge il numero di pagina alle pagine.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| formattedText | FormattedText | Oggetto FormattedText che contiene il formato del numero di pagina e le proprietà del testo. Questo testo può contenere # che verrà sostituito con il numero di pagina. |
| position | Int32 | Posizione in cui verrà posizionato il numero di pagina sulla pagina. 0-in basso al centro, 1-in basso a destra, 2-in alto a destra, 3 - lati a destra, 4 - in alto al centro,5 - in basso a sinistra,6 - lati a sinistra,7 - in alto a sinistra. È possibile utilizzare le seguenti costanti: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Esempi

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Guarda anche

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* spazio dei nomi [Aspose.Pdf.Facades](../../pdffilestamp)
* assemblea [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
