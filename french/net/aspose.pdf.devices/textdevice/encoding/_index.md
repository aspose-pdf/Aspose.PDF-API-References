---
title: TextDevice.Encoding
second_title: Aspose.PDF for .NET API Reference
description: Propriété TextDevice. Obtient ou définit l'encodage du texte extrait
type: docs
weight: 20
url: /fr/net/aspose.pdf.devices/textdevice/encoding/
---
## Propriété TextDevice.Encoding

Obtient ou définit l'encodage du texte extrait.

```csharp
public Encoding Encoding { get; set; }
```

## Exemples

L'exemple démontre comment représenter le texte extrait en encodage UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// create text device
TextDevice device = new TextDevice(Encoding.UTF8);

// convert the page and save text to the stream
device.Process(doc.Pages[1], outFile);

// use the extracted text
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Voir aussi

* classe [TextDevice](../)
* espace de noms [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)