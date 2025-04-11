---
title: PdfFileStamp.AddPageNumber
second_title: Aspose.PDF for .NET API Reference
description: PdfFileStamp-metod. Lägg till sidnummer till filen. Texten för sidnumret kan innehålla #-tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt
type: docs
weight: 130
url: /sv/net/aspose.pdf.facades/pdffilestamp/addpagenumber/
---
## AddPageNumber(string) {#addpagenumber_4}

Lägg till sidnummer till filen. Texten för sidnumret kan innehålla # tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt.

```csharp
public void AddPageNumber(string formatString)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | Sträng | Text för sidnummer |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #");
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText) {#addpagenumber}

Lägger till sidnummer till sidan. Sidnumret kan innehålla # tecken som kommer att ersättas med sidnumret. Sidnumret placeras i botten av sidan centrerat horisontellt.

```csharp
public void AddPageNumber(FormattedText formattedText)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formatsträng för sidnummer representerad som FormattedText. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"));
fileStamp.Close();
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int, float, float, float, float) {#addpagenumber_6}

Lägger till sidnummer till sidorna i dokumentet.

```csharp
public void AddPageNumber(string formatString, int position, float leftMargin, float rightMargin, 
    float topMargin, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | Sträng | Formatsträng för sidnummer. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-botten mitt, 1-botten höger, 2-övre höger, 3 - sidor höger, 4 - övre mitt, 5 - botten vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marginal på vänster kant av sidan. |
| rightMargin | Single | Marginal på höger kant av sidan. |
| topMargin | Single | Marginal på övre kant av sidan. |
| bottomMargin | Single | Marginal på nedre kant av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, float, float) {#addpagenumber_7}

Lägger till sidnummer på den angivna positionen på sidan.

```csharp
public void AddPageNumber(string formatString, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | Sträng | Formatsträng. Formatsträngen kan innehålla # tecken som kommer att ersättas med sidnumret. |
| x | Single | X-koordinat för sidnumret. |
| y | Single | Y-koordinat för sidnumret. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int, float, float, float, float) {#addpagenumber_2}

Lägger till sidnummer till sidorna i dokumentet.

```csharp
public void AddPageNumber(FormattedText formattedText, int position, float leftMargin, 
    float rightMargin, float topMargin, float bottomMargin)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som representerar sidnummerformat och egenskaper för texten. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-botten mitt, 1-botten höger, 2-övre höger, 3 - sidor höger, 4 - övre mitt, 5 - botten vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |
| leftMargin | Single | Marginal på vänster kant av sidan. |
| rightMargin | Single | Marginal på höger kant av sidan. |
| topMargin | Single | Marginal på övre kant av sidan. |
| bottomMargin | Single | Marginal på nedre kant av sidan. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page #"), PdfFileStamp.PosBottomLeft, 100, 100, 200, 200);
fileStamp.Close();
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, float, float) {#addpagenumber_3}

Lägger till sidnummer på den angivna positionen på sidan.

```csharp
public void AddPageNumber(FormattedText formattedText, float x, float y)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | Formaterad text som representerar sidnummerformat och egenskaper för texten. Formatsträngen kan innehålla # tecken som kommer att ersättas med sidnumret. |
| x | Single | X-koordinat för sidnumret. |
| y | Single | Y-koordinat för sidnumret. |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber(new FormattedText("Page  #"), 123, 357);
fileStamp.Close();
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(string, int) {#addpagenumber_5}

Lägger till sidnummer till sidorna.

```csharp
public void AddPageNumber(string formatString, int position)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formatString | Sträng | Format för sidnumret. Denna text kan innehålla # som kommer att ersättas med sidnumret. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-botten mitt, 1-botten höger, 2-övre höger, 3 - sidor höger, 4 - övre mitt, 5 - botten vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Se Även

* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## AddPageNumber(FormattedText, int) {#addpagenumber_1}

Lägger till sidnummer till sidorna.

```csharp
public void AddPageNumber(FormattedText formattedText, int position)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formattedText | FormattedText | FormattedText-objekt som innehåller format för sidnumret och textens egenskaper. Denna text kan innehålla # som kommer att ersättas med sidnumret. |
| position | Int32 | Position där sidnumret kommer att placeras på sidan. 0-botten mitt, 1-botten höger, 2-övre höger, 3 - sidor höger, 4 - övre mitt, 5 - botten vänster, 6 - sidor vänster, 7 - övre vänster. Du kan använda följande konstanter: PosBottomMiddle = 0, PosBottomRight = 1, PosUpperRight = 2, PosSidesRight = 3, PosUpperMiddle, PosBottomLeft = 5, PosSidesLeft, PosUpperLeft |

## Exempel

```csharp
PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf");
fileStamp.AddPageNumber("Page #", PdfFileStamp.PosUpperRight);
fileStamp.Close();
```

### Se Även

* klass [FormattedText](../../formattedtext/)
* klass [PdfFileStamp](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)