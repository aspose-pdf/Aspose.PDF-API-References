---
title: "TextAbsorber.Text"
second_title: "Aspose.PDF för .NET API‑referens"
description: "TextAbsorber-egenskap. Hämtar extraherad text som TextAbsorber extraherar i PDF-dokumentet eller på sidan"
type: docs
weight: 50
url: /sv/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text property

Hämtar extraherad text som [`TextAbsorber`](../) extraherar i PDF-dokumentet eller på sidan.

```csharp
public virtual string Text { get; }
```

## Exempel

Exemplet visar hur man extraherar text från alla sidor i PDF-dokumentet.

```csharp
// öppna dokument
Document doc = new Document(inFile);

// skapa TextAbsorber-objekt för att extrahera text
TextAbsorber absorber = new TextAbsorber();

// acceptera absorberaren för alla dokumentets sidor
doc.Pages.Accept(absorber);

// hämta den extraherade texten
string extractedText = absorber.Text;

```

### Se även

* class [TextAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


