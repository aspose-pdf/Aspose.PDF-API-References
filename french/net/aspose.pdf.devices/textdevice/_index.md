---
title: Class TextDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.TextDevice. Représente une classe pour convertir les pages de documents pdf en texte
type: docs
weight: 3680
url: /fr/net/aspose.pdf.devices/textdevice/
---
## Classe TextDevice

Représente une classe pour convertir les pages de documents pdf en texte.

```csharp
public sealed class TextDevice : PageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Initialise une nouvelle instance de `TextDevice` avec le mode de formatage de texte brut et l'encodage de texte Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Initialise une nouvelle instance de `TextDevice` pour l'encodage spécifié. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Initialise une nouvelle instance de `TextDevice` avec des options d'extraction de texte. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Initialise une nouvelle instance de `TextDevice` pour l'encodage spécifié avec des options d'extraction de texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Obtient ou définit l'encodage du texte extrait. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Obtient ou définit les options d'extraction de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Convertit la page et l'enregistre en tant que flux de texte. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

## Remarques

L'objet `TextDevice` est essentiellement utilisé pour extraire du texte d'une page pdf.

## Exemples

L'exemple démontre comment extraire du texte sur la première page du document PDF.

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

* classe [PageDevice](../pagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)