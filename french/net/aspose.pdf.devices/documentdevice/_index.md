---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.DocumentDevice. Classe abstraite pour tous les dispositifs utilisés pour traiter l'ensemble du document pdf
type: docs
weight: 3570
url: /fr/net/aspose.pdf.devices/documentdevice/
---
## Classe DocumentDevice

Classe abstraite pour tous les dispositifs utilisés pour traiter l'ensemble du document pdf.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Méthodes

| Nom | Description |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Traite l'ensemble du document et enregistre les résultats dans le flux. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Traite l'ensemble du document et enregistre les résultats dans un fichier. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Effectue une opération sur la page donnée, par exemple, convertit la page en image graphique. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Chaque dispositif représente une opération sur le document, par exemple, nous pouvons convertir un document pdf dans un autre format. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Traite certaines pages du document et enregistre les résultats dans un fichier. |

### Voir aussi

* classe [PageDevice](../pagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)