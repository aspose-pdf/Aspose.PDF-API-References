---
title: AddPageNumber
second_title: Aspose.PDF för .NET API Referens
description: Lägg till sidnummer i filen. Sidnummertext kan innehålla -tecken som kommer att ersättas med sidans nummer. Sidnummer placeras längst ner på sidan centrerat horisontellt.
type: docs
weight: 170
url: /sv/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Lägg till sidnummer i filen. Sidnummertext kan innehålla #-tecken som kommer att ersättas med sidans nummer. Sidnummer placeras längst ner på sidan centrerat horisontellt.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Text till sidnummer |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Lägger till sidnummer på sidan. Sidnummer kan innehålla #-tecken som kommer att ersättas med sidnummer. Sidnummer placeras längst ner på sidan centrerat horisontellt.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formatsträng för sidnummer representerar FormattedText. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Lägger till sidnummer på sidorna i dokumentet.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Formatsträng för sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-nedre mitten, 1-nederst höger, 2-upper höger, 3 - sidor höger, 4 - övre mitten, 5 - nedre vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marginal på sidans vänstra kant. |
| rightMargin | Single | Marginal på sidans högra kant. |
| topMargin | Single | Marginal på sidans övre kant. |
| bottomMargin | Single | Marginal i nederkanten av sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Lägger till sidnummer på den angivna positionen på sidan.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Formatera sträng. Formatsträng kan innehålla #-tecken som kommer att ersättas med sidnummer. |
| x | Single | X-koordinat för sidnummer. |
| y | Single | Y-koordinat för sidnummer. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Lägger till sidnummer på sidorna i dokumentet.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som representerar sidnummerformat och egenskaper i texten. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-nedre mitten, 1-nederst höger, 2-upper höger, 3 - sidor höger, 4 - övre mitten, 5 - nedre vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marginal på sidans vänstra kant. |
| rightMargin | Single | Marginal på sidans högra kant. |
| topMargin | Single | Marginal på sidans övre kant. |
| bottomMargin | Single | Marginal i nederkanten av sidan. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Lägger till sidnummer på den angivna positionen på sidan.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formaterad text som representerar sidnummerformat och egenskaper för texten. Formatsträng kan innehålla #-tecken som kommer att ersättas med sidnummer. |
| x | Single | X-koordinat för sidnummer. |
| y | Single | Y-koordinat för sidnummer. |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Lägger till sidnummer på sidorna.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Format på sidnumret. Denna text kan innehålla # som kommer att ersättas med sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-nedre mitten, 1-nederst höger, 2-upper höger, 3 - sidor höger, 4 - övre mitten, 5 - nedre vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Lägger till sidnummer på sidorna.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som innehåller format för sidnumret och textegenskaper. Denna text kan innehålla # som kommer att ersättas med sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-nedre mitten, 1-nederst höger, 2-upper höger, 3 - sidor höger, 4 - övre mitten, 5 - nedre vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

### Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext)
* class [PdfFileStamp](../../pdffilestamp)
* namnutrymme [Aspose.Pdf.Facades](../../pdffilestamp)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
