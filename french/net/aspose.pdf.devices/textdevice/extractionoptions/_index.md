---
title: "TextDevice.ExtractionOptions"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextDevice. Obtient ou définit les options d'extraction de texte"
type: docs
weight: 30
url: /fr/net/aspose.pdf.devices/textdevice/extractionoptions/
---
## TextDevice.ExtractionOptions property

Obtient ou définit les options d'extraction de texte.

```csharp
public TextExtractionOptions ExtractionOptions { get; set; }
```

## Exemples

L'exemple montre comment extraire le texte dans l'ordre brut.

```csharp
Document doc = new Document(inFile);
string extractedText;

// créer un dispositif texte
TextDevice device = new TextDevice(new TextExtractionOptions(TextExtractionOptions.TextFormattingMode.Raw));

// convertir la page et enregistrer le texte dans le flux
device.Process(doc.Pages[1], outFile);

// utiliser le texte extrait
extractedText = File.ReadAllText(outFile, Encoding.Unicode); 
```

### Voir aussi

* class [TextExtractionOptions](../../../aspose.pdf.text/textextractionoptions/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


