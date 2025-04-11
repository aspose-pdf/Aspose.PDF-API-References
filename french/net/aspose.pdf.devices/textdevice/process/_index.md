---
title: TextDevice.Process
second_title: Aspose.PDF for .NET API Reference
description: Méthode TextDevice. Convertir la page et l'enregistrer en tant que flux de texte
type: docs
weight: 40
url: /fr/net/aspose.pdf.devices/textdevice/process/
---
## Méthode TextDevice.Process

Convertir la page et l'enregistrer en tant que flux de texte.

```csharp
public override void Process(Page page, Stream output)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| page | Page | La page à convertir. |
| output | Stream | Flux de résultat. |

## Exemples

L'exemple démontre comment extraire le texte de la première page du document PDF.

```csharp
Document doc = new Document(inFile);
string extractedText;

using (MemoryStream ms = new MemoryStream())
{
    // create text device
    TextDevice device = new TextDevice();

    // convert the page and save text to the stream
    device.Process(doc.Pages[1], ms);

    // use the extracted text
    ms.Close();
    extractedText = Encoding.Unicode.GetString(ms.ToArray());
}
```

### Voir aussi

* classe [Page](../../../aspose.pdf/page/)
* classe [TextDevice](../)
* espace de noms [Aspose.Pdf.Devices](../../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../../)