---
title: ExtractionOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: Ruft Textextraktionsoptionen ab oder legt sie fest.
type: docs
weight: 30
url: /de/net/aspose.pdf.text/textabsorber/extractionoptions/
---
## TextAbsorber.ExtractionOptions property

Ruft Textextraktionsoptionen ab oder legt sie fest.

```csharp
public virtual TextExtractionOptions ExtractionOptions { get; set; }
```

### Bemerkungen

Ermöglicht die Definition des Textformatierungsmodus[`TextExtractionOptions`](../../textextractionoptions) während der Extraktion. Der Standardmodus istPure

### Beispiele

Das Beispiel zeigt, wie Sie den reinen Textformatierungsmodus einstellen und die Textextraktion durchführen.

```csharp
// Dokument öffnen
Document doc = new Document(inFile);

// TextAbsorber-Objekt erstellen, um Text mit Formatierung zu extrahieren
TextAbsorber absorber = new TextAbsorber();

// reinen Textformatierungsmodus setzen
absorber.ExtractionOptions = new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Pure);

// Akzeptiere den Absorber für alle Seiten des Dokuments
doc.Pages.Accept(absorber);

// Holen Sie sich den extrahierten Text
string extractedText = absorber.Text;
```

### Siehe auch

* class [TextExtractionOptions](../../textextractionoptions)
* class [TextAbsorber](../../textabsorber)
* namensraum [Aspose.Pdf.Text](../../textabsorber)
* Montage [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
