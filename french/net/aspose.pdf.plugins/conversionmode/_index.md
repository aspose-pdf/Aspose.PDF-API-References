---
title: Enum ConversionMode
second_title: Aspose.PDF for .NET API Reference
description: Enum ConversionMode d'Aspose.Pdf.Plugins. Définit le mode de conversion du document de sortie
type: docs
weight: 8500
url: /fr/net/aspose.pdf.plugins/conversionmode/
---
## Énumération ConversionMode

Définit le mode de conversion du document de sortie.

```csharp
public enum ConversionMode
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| TextBox | `0` | Ce mode est rapide et bon pour préserver au maximum l'apparence originale du fichier PDF, mais l'éditabilité du document résultant pourrait être limitée. |
| Flow | `1` | Mode de reconnaissance complet, le moteur effectue un regroupement et une analyse multi-niveaux pour restaurer l'intention originale de l'auteur du document et produire un document maximement éditable. L'inconvénient est que le document de sortie pourrait avoir une apparence différente de celle du fichier PDF original. |
| EnhancedFlow | `2` | Un mode Flow alternatif qui prend en charge la reconnaissance des tableaux. |

### Voir aussi

* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)