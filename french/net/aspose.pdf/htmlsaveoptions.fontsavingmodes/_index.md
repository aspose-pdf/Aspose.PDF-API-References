---
title: "Énumération HtmlSaveOptions.FontSavingModes"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Énumération Aspose.Pdf.HtmlSaveOptionsFontSavingModes. Énumère les modes pouvant être utilisés pour l'enregistrement des polices référencées dans le PDF enregistré"
type: docs
weight: 5760
url: /fr/net/aspose.pdf/htmlsaveoptions.fontsavingmodes/
---
## HtmlSaveOptions.FontSavingModes enumeration

Énumère les modes pouvant être utilisés pour l'enregistrement des polices référencées dans le PDF enregistré.

```csharp
public enum FontSavingModes
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| AlwaysSaveAsWOFF | `0` | Toutes les polices référencées seront enregistrées et référencées sous forme de polices WOFF. |
| AlwaysSaveAsTTF | `1` | Toutes les polices référencées seront enregistrées et référencées sous forme de polices TTF. |
| AlwaysSaveAsEOT | `2` | Toutes les polices référencées seront enregistrées et référencées sous forme de polices EOT. |
| SaveInAllFormats | `3` | Toutes les polices référencées seront enregistrées (et référencées dans le CSS) sous forme de 3 fichiers indépendants : EOT, TTH, WOFF. Cela augmente la taille des données de sortie mais rend la sortie adaptée à la grande majorité des navigateurs web. |
| DontSave | `4` | Toutes les polices référencées ne seront pas enregistrées. |

### Voir aussi

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


