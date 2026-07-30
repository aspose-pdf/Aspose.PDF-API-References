---
title: "TextDevice.Process"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode TextDevice. Convertit la page et l'enregistre en flux texte"
type: docs
weight: 40
url: /fr/net/aspose.pdf.devices/textdevice/process/
---
## TextDevice.Process method

Convertir la page et l'enregistrer comme flux texte.

```csharp
public override void Process(Page page, Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | La page à convertir. |
| output | Stream | Flux de résultat. |

## Exemples

L’exemple montre comment extraire du texte sur la première page du document PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // créer un dispositif texte
    TextDevice device = new TextDevice();

    // convertir la page et enregistrer le texte dans le flux
    device.Process(doc.Pages[1], ms);

    // utiliser le texte extrait
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Voir aussi

* class [Page](../../../aspose.pdf/page/)
* class [TextDevice](../)
* namespace [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)


