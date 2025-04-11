---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontEncodingRules Enum. Diese Enumeration definiert Regeln, die die Kodierungslogik anpassen
type: docs
weight: 5620
url: /de/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules Enumeration

Diese Enumeration definiert Regeln, die die Kodierungslogik anpassen

```csharp
public enum FontEncodingRules : byte
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Default | `0` | Kodierungslogik "wie sie ist" belassen - gemäß PDF-Spezifikation |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode ist ein spezieller Mechanismus, der hilft, Eingabecodes in Unicode-Symbole zu dekodieren. Laut Spezifikation muss es als erstes von allen Mechanismen verwendet werden, um Unicode-Symbole für spezifische Eingabecodes zu erhalten. Aber einige Dokumente haben nicht-standardisierte Schriftarten, und um diese Dokumente korrekt zu konvertieren, kann es notwendig sein, die ToUnicode-Priorität zu verringern und andere Mechanismen zur Dekodierung von Eingabecodes zu verwenden. |

### Siehe Auch

* Klasse [HtmlSaveOptions](../htmlsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)