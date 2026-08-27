---
title: "Enumération HtmlSaveOptions.FontEncodingRules"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. Cette énumération définit des règles qui ajustent la logique d'encodage"
type: docs
weight: 5750
url: /fr/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

Cette énumération définit des règles qui ajustent la logique d'encodage

```csharp
public enum FontEncodingRules : byte
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | `0` | Laisser la logique d'encodage \"telle quelle\" - conformément à la spécification PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode est un mécanisme spécial qui aide à décoder les codes d'entrée en symboles Unicode. Selon la spécification, il doit être utilisé en premier parmi tous les mécanismes pour obtenir des symboles Unicode pour un code d'entrée spécifique. Cependant, certains documents contiennent des polices non standard et, pour convertir correctement ces documents, il peut être nécessaire de diminuer la priorité de ToUnicode et d'utiliser d'autres mécanismes pour décoder les codes d'entrée. |

### Voir aussi

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


