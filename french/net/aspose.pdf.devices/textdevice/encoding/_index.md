---
title: "TextDevice.Encoding"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Propriété TextDevice. Obtient ou définit l'encodage du texte extrait"
type: docs
weight: 20
url: /fr/net/aspose.pdf.devices/textdevice/encoding/
---
## TextDevice.Encoding property

Obtient ou définit l'encodage du texte extrait.

```csharp
public Encoding Encoding { get; set; }
```

## Exemples

L'exemple montre comment représenter le texte extrait avec l'encodage UTF-8.

```csharp
Document doc = new Document(inFile);
string extractedText;

// créer un dispositif texte
TextDevice device = new TextDevice(Encoding.UTF8);

// convertir la page et enregistrer le texte dans le flux
device.Process(doc.Pages[1], outFile);

// utiliser le texte extrait
extractedText = File.ReadAllText(outFile, Encoding.UTF8);
```

### Voir aussi

* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


