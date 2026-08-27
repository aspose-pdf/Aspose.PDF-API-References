---
title: "TextAbsorber.Visit"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextAbsorber‑metod. Extraherar text på den angivna sidan"
type: docs
weight: 70
url: /sv/net/aspose.pdf.text/textabsorber/visit/
---
## Visit(Page) {#visit_1}

Extraherar text på den angivna sidan

```csharp
public virtual void Visit(Page page)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| sida | Page | Pdf‑dokument sidobjekt. |

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokumentets sida.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa TextAbsorber-objekt för att extrahera text
TextAbsorber absorber = new TextAbsorber();

// acceptera absorberaren för alla dokumentets sidor
absorber.Visit(doc.Pages[1]);

// hämta den extraherade texten
string extractedText = absorber.Text;
```

### Se även

* class [Page](../../../aspose.pdf/page/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(XForm) {#visit_2}

Extraherar text i den angivna XForm.

```csharp
public virtual void Visit(XForm form)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| formulär | XForm | Pdf-formobjekt. |

## Exempel

Exemplet visar hur man extraherar text på den första PDF-dokumentets sida.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa TextAbsorber-objekt för att extrahera text
TextAbsorber absorber = new TextAbsorber();

// acceptera absorberaren för alla dokumentets sidor
absorber.Visit(doc.Pages[1].Resources.Forms["Xform1"]);

// hämta den extraherade texten
string extractedText = absorber.Text;
```

### Se även

* class [XForm](../../../aspose.pdf/xform/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)

---

## Visit(Document) {#visit}

Extraherar text i det angivna dokumentet

```csharp
public virtual void Visit(Document pdf)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| pdf | Dokument | Pdf-dokumentobjekt. |

## Exempel

Exemplet visar hur man extraherar text i ett PDF‑dokument.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa TextAbsorber-objekt för att extrahera text
TextAbsorber absorber = new TextAbsorber();

// acceptera absorberaren för alla dokumentets sidor
absorber.Visit(doc);

// hämta den extraherade texten
string extractedText = absorber.Text;
```

### Se även

* class [Document](../../../aspose.pdf/document/)
* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


