---
title: "TableAbsorber.Visit"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TableAbsorber‑metod. Extraherar tabeller på den angivna sidan."
type: docs
weight: 70
url: /sv/net/aspose.pdf.text/tableabsorber/visit/
---
## Visit(Page) {#visit_1}

Extraherar tabeller på den angivna sidan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Pdf‑dokument sidobjekt. |

## Exempel

Exemplet visar hur man extraherar en tabell på den första PDF‑dokumentets sida.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TableAbsorber‑objekt för att hitta tabeller
TableAbsorber absorber = new TableAbsorber();

// Besök första sidan med absorberaren
absorber.Visit(doc.Pages[1]);

// Få åtkomst till den första tabellen på sidan, dess första cell och textfragmenten i den
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Ändra texten i det första textfragmentet i cellen
fragment.Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extraherar tabeller i det angivna dokumentet.

```csharp
public void Visit(Document pdf)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | Dokument | Pdf-dokumentobjekt. |

## Exempel

Exemplet visar hur man extraherar en tabell på den första PDF‑dokumentets sida.

```csharp
// Öppna dokument
Document doc = new Document(@"D:\Tests\input.pdf");

// Skapa ett TableAbsorber‑objekt för att hitta tabeller
TableAbsorber absorber = new TableAbsorber();

// Besök första sidan med absorberaren
absorber.Visit(doc);

// Få åtkomst till den första tabellen på sidan, dess första cell och textfragmenten i den
TextFragment fragment = absorber.TableList[0].RowList[0].CellList[0].TextFragments[1];

// Ändra texten i det första textfragmentet i cellen
fragment.Text = "hi world";

// Spara dokument
doc.Save(@"D:\Tests\output.pdf");  
```

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [TableAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


