---
title: "Classe TextDevice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Devices.TextDevice. Représente la classe permettant de convertir les pages de document pdf en texte."
type: docs
weight: 3800
url: /fr/net/aspose.pdf.devices/textdevice/
---
## TextDevice class

Représente une classe permettant de convertir les pages du document PDF en texte.

```csharp
public sealed class TextDevice : PageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [TextDevice](textdevice/#constructor)() | Initialise une nouvelle instance de `TextDevice` avec le mode de formatage texte brut et l'encodage texte Unicode. |
| [TextDevice](textdevice/#constructor_3)(Encoding) | Initialise une nouvelle instance de `TextDevice` pour l'encodage spécifié. |
| [TextDevice](textdevice/#constructor_1)(TextExtractionOptions) | Initialise une nouvelle instance de `TextDevice` avec les options d'extraction de texte. |
| [TextDevice](textdevice/#constructor_2)(TextExtractionOptions, Encoding) | Initialise une nouvelle instance de `TextDevice` pour l'encodage spécifié avec les options d'extraction de texte. |

## Propriétés

| Nom | Description |
| --- | --- |
| [Encoding](../../aspose.pdf.devices/textdevice/encoding/) { get; set; } | Obtient ou définit l'encodage du texte extrait. |
| [ExtractionOptions](../../aspose.pdf.devices/textdevice/extractionoptions/) { get; set; } | Obtient ou définit les options d'extraction de texte. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/textdevice/process/#process)(Page, Stream) | Convertir la page et l'enregistrer comme flux texte. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

## Remarques

L'objet `TextDevice` est essentiellement utilisé pour extraire du texte d'une page pdf.

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

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


