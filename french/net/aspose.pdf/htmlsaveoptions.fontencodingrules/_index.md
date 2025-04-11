---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsFontEncodingRules. Cette énumération définit des règles qui ajustent la logique d'encodage
type: docs
weight: 5620
url: /fr/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## Énumération HtmlSaveOptions.FontEncodingRules

Cette énumération définit des règles qui ajustent la logique d'encodage

```csharp
public enum FontEncodingRules : byte
```

### Valeurs

| Nom | Valeur | Description |
| --- | --- | --- |
| Default | `0` | Laisser la logique d'encodage "telle quelle" - conformément à la spécification PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode est un mécanisme spécial qui aide à décoder les codes d'entrée en symboles unicode. Selon la spécification, il doit être utilisé en premier lieu parmi les mécanismes pour obtenir des symboles unicode pour un code d'entrée spécifique. Mais certains documents ont des polices non standard et pour convertir ces documents correctement, il peut être nécessaire de diminuer la priorité de ToUnicode et d'utiliser d'autres mécanismes pour décoder les codes d'entrée. |

### Voir aussi

* classe [HtmlSaveOptions](../htmlsaveoptions/)
* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)