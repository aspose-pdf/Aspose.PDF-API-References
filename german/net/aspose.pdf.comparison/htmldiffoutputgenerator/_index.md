---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.HtmlDiffOutputGenerator-Klasse. Stellt eine Klasse zur Generierung der HTML-Darstellung von Textunterschieden dar. Gelöschte Zeilenumbrüche werden durch Absatzzeichen angezeigt.
type: docs
weight: 3200
url: /de/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator-Klasse

Stellt eine Klasse zur Generierung der HTML-Darstellung von Textunterschieden dar. Gelöschte Zeilenumbrüche werden durch Absatzzeichen angezeigt.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Erstellt eine Instanz der `HtmlDiffOutputGenerator`-Klasse. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Erstellt eine Instanz der `HtmlDiffOutputGenerator`-Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Ruft den CSS-Stil-String für die Löschoperation ab und setzt ihn. Beispiel: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Ruft den CSS-Stil-String für die Gleichheitsoperation ab und setzt ihn. Beispiel: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Ruft den CSS-Stil-String für die Einfügeoperation ab und setzt ihn. Beispiel: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Ruft den Stil text-decoration: line-through für die Löschoperation ab oder setzt ihn. Der Standardwert ist `False`. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |

### Siehe auch

* Schnittstelle [IFileOutputGenerator](../ifileoutputgenerator/)
* Schnittstelle [IStringOutputGenerator](../istringoutputgenerator/)
* Namensraum [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../)