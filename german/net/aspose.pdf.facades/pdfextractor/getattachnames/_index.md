---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor-Methode. Gibt eine Liste von Anhängen in der PDF-Datei zurück. Hinweis ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden
type: docs
weight: 160
url: /de/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## PdfExtractor.GetAttachNames-Methode

Gibt eine Liste von Anhängen in der PDF-Datei zurück. Hinweis: ExtractAttachments muss vor der Verwendung dieser Methode aufgerufen werden.

```csharp
public IList<string> GetAttachNames()
```

### Rückgabewert

Liste der Anhänge

## Beispiele

Das Beispiel zeigt, wie man die Anhangsnamen aus der PDF-Datei extrahiert.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Siehe auch

* Klasse [PdfExtractor](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)