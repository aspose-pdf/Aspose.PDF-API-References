---
title: Class ComHelper
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.ComHelper. Fournit des méthodes pour les clients COM pour charger un document dans Aspose.Pdf
type: docs
weight: 3130
url: /fr/net/aspose.pdf/comhelper/
---
## Classe ComHelper

Fournit des méthodes pour les clients COM pour charger un document dans Aspose.Pdf.

```csharp
public class ComHelper
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [ComHelper](comhelper/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile)(string) | Crée simplement et retourne un Document en utilisant *filename*. Identique à [`Document`](../document/document/). |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_1)(string, LoadOptions) | Ouvre un document existant à partir d'un fichier en fournissant les options de conversion nécessaires pour obtenir un document pdf. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_2)(string, string) | Initialise et retourne une nouvelle instance de la classe [`Document`](../document/) pour travailler avec un document crypté. |
| [OpenFile](../../aspose.pdf/comhelper/openfile/#openfile_3)(string, string, bool) | Initialise une nouvelle instance de la classe [`Document`](../document/) pour travailler avec un document crypté. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream)(Stream) | Initialise et retourne une nouvelle instance de Document à partir du *flux* d'entrée. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_2)(Stream, bool) | Initialise et retourne une nouvelle instance de Document à partir du *flux* d'entrée. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_1)(Stream, LoadOptions) | Ouvre et retourne un document existant à partir d'un flux en fournissant les conversions nécessaires pour obtenir un document pdf. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_3)(Stream, string) | Initialise et retourne une nouvelle instance de Document à partir du *flux* d'entrée. |
| [OpenStream](../../aspose.pdf/comhelper/openstream/#openstream_4)(Stream, string, bool) | Initialise et retourne une nouvelle instance de Document à partir du *flux* d'entrée. |

## Remarques

Utilisez la classe ComHelper pour charger un document à partir d'un fichier ou d'un flux dans un objet Document dans une application COM. La classe Document fournit un constructeur par défaut pour créer un nouveau document et fournit également des constructeurs surchargés pour charger un document à partir d'un fichier ou d'un flux. Si vous utilisez Aspose.Words à partir d'une application .NET, vous pouvez utiliser tous les constructeurs de Document directement, mais si vous utilisez Aspose.Pdf à partir d'une application COM, seul le constructeur par défaut de Document est disponible.

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)