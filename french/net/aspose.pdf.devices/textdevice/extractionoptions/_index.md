---
title: ExtractionOptions
second_title: Référence de l'API Aspose.PDF pour .NET
description: Obtient ou définit les options dextraction de texte.
type: docs
weight: 30
url: /fr/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Obtient ou définit les options d'extraction de texte.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

### Exemples

L'exemple montre comment extraire du texte dans l'ordre brut.

```csharp
Document doc = new Document(inFile);
string extractedText;

// crée un périphérique texte
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convertit la page et enregistre le texte dans le flux
device.Process(doc.Pages[1], outFile);

// utilise le texte extrait
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Voir également

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions)
* class [TextDevice](../../textdevice)
* espace de noms [Aspose.Pdf.Devices](../../textdevice)
* Assemblée [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->