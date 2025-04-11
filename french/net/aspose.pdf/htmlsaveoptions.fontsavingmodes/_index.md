---
title: Enum HtmlSaveOptions.FontSavingModes
second_title: Aspose.PDF for .NET API Reference
description: Enum HtmlSaveOptionsFontSavingModes d'Aspose.Pdf. Énumère les modes qui peuvent être utilisés pour l'enregistrement des polices référencées dans le PDF enregistré
type: docs
weight: 5630
url: /fr/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## Énumération HtmlSaveOptions.FontSavingModes

Énumère les modes qui peuvent être utilisés pour l'enregistrement des polices référencées dans le PDF enregistré.

```csharp
public enum FontSavingModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | Toutes les polices référencées seront enregistrées et référencées en tant que polices WOFF. |
| AlwaysSaveAsTTF | `1` | Toutes les polices référencées seront enregistrées et référencées en tant que polices TTF. |
| AlwaysSaveAsEOT | `2` | Toutes les polices référencées seront enregistrées et référencées en tant que polices EOT. |
| SaveInAllFormats | `3` | Toutes les polices référencées seront enregistrées (et référencées dans le CSS) en tant que 3 fichiers indépendants : EOT, TTH, WOFF. Cela augmente la taille des données de sortie mais rend la sortie adaptée à la grande majorité des navigateurs web. |
| DontSave | `4` | Toutes les polices référencées ne seront pas enregistrées. |

### Voir aussi

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)