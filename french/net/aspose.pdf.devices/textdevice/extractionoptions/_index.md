---
title: TextDevice.ExtractionOptions
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextDevice. Obtient ou définit les options d'extraction de texte
type: docs
weight: 30
url: /fr/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## Propriété TextDevice.ExtractionOptions

Obtient ou définit les options d'extraction de texte.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Exemples

L'exemple démontre comment extraire le texte dans l'ordre brut.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Voir aussi

* classe [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* classe [TextDevice](../)
* espace de noms [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)