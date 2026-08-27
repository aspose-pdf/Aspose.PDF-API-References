---
title: "PdfFileStamp.AddPageNumber"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfFileStamp-metod. Lägg till sidnummer i filen. Sidnummertext kan innehålla tecken som ersätts med sidnumret. Sidnumret placeras längst ner på sidan centrerat horisontellt"
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Lägg till sidnummer i filen. Sidnummertexten kan innehålla #-tecken som ersätts med sidnumret. Sidnumret placeras längst ner på sidan centrerat horisontellt.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Text för sidnummer |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Lägger till sidnummer på sidan. Sidnumret kan innehålla #-tecken som ersätts med sidnumret. Sidnumret placeras längst ner på sidan centrerat horisontellt.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formatsträng för sidnummer representeras som FormattedText. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Lägger till sidnummer på dokumentets sidor.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Formatsträng för sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marginal på vänstra kanten av sidan. |
| rightMargin | Single | Marginal på högra kanten av sidan. |
| topMargin | Single | Marginal på övre kanten av sidan. |
| bottomMargin | Single | Marginal på nedre kanten av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Lägger till sidnummer på den angivna positionen på sidan.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Formatsträng. Formatsträngen kan innehålla tecknet # som kommer att ersättas med sidnummer. |
| x | Single | X‑koordinat för sidnummer. |
| y | Single | Y‑koordinat för sidnummer. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Lägger till sidnummer på dokumentets sidor.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object som representerar sidnumrets format och egenskaper för texten. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marginal på vänstra kanten av sidan. |
| rightMargin | Single | Marginal på högra kanten av sidan. |
| topMargin | Single | Marginal på övre kanten av sidan. |
| bottomMargin | Single | Marginal på nedre kanten av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Lägger till sidnummer på den angivna positionen på sidan.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formaterad text som representerar sidnumrets format och egenskaper för texten. Formatsträngen kan innehålla tecknet # som kommer att ersättas med sidnummer. |
| x | Single | X‑koordinat för sidnummer. |
| y | Single | Y‑koordinat för sidnummer. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Lägger till sidnummer på sidorna.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | String | Format för sidnumret. Denna text kan innehålla # som kommer att ersättas med sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Se även

* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Lägger till sidnummer på sidorna.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText object som innehåller formatet för sidnumret och textegenskaper. Denna text kan innehålla # som kommer att ersättas med sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0‑nedre mitten, 1‑nedre höger, 2‑övre höger, 3‑sidor höger, 4‑övre mitten, 5‑nedre vänster, 6‑sidor vänster, 7‑övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Se även

* class [FormattedText](../../formattedtext/)
* class [PdfFileStamp](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


