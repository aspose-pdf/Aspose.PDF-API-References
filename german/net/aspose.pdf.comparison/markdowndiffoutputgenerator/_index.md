---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator-Klasse. Stellt eine Klasse zur Generierung der Markdown-Darstellung von Textunterschieden dar. Aufgrund der Markdown-Syntax ist es nicht möglich, Änderungen an Leerzeichen anzuzeigen. Die Auswahl von Änderungen erfordert das Hinzufügen von Leerzeichen um die Formatierung, andernfalls wird der Markdown-Viewer den Text nicht korrekt anzeigen. Gelöschte Zeilenumbrüche werden durch das Absatzzeichen angezeigt.
type: docs
weight: 3250
url: /de/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## Klasse MarkdownDiffOutputGenerator

Stellt eine Klasse zur Generierung der Markdown-Darstellung von Textunterschieden dar. Aufgrund der Markdown-Syntax ist es nicht möglich, Änderungen an Leerzeichen anzuzeigen. Die Auswahl von Änderungen erfordert das Hinzufügen von Leerzeichen um die Formatierung, andernfalls wird der Markdown-Viewer den Text nicht korrekt anzeigen. Gelöschte Zeilenumbrüche werden durch das Absatzzeichen angezeigt.

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Generiert die Ausgabe basierend auf den Unterschieden zwischen Texten und speichert sie in einer Datei. |

### Siehe auch

* Schnittstelle [IFileOutputGenerator](../ifileoutputgenerator/)
* Schnittstelle [IStringOutputGenerator](../istringoutputgenerator/)
* Namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* Assembly [Aspose.PDF](../../)