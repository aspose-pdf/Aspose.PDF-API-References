---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode Enum. Ermöglicht die Steuerung, wie ein PDF-Dokument in ein Textverarbeitungsdokument konvertiert wird
type: docs
weight: 3770
url: /de/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode Aufzählung

Ermöglicht die Steuerung, wie ein PDF-Dokument in ein Textverarbeitungsdokument konvertiert wird.

```csharp
public enum RecognitionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Textbox | `0` | Dieser Modus ist schnell und gut geeignet, um das ursprüngliche Aussehen der PDF-Datei maximal zu bewahren, aber die Bearbeitbarkeit des resultierenden Dokuments könnte eingeschränkt sein. |
| Flow | `1` | Vollständiger Erkennungsmodus, der Motor führt Gruppierungen und mehrstufige Analysen durch, um die ursprüngliche Absicht des Dokumentenautors wiederherzustellen und ein maximal bearbeitbares Dokument zu erstellen. Der Nachteil ist, dass das Ausgabedokument möglicherweise anders aussieht als die ursprüngliche PDF-Datei. |
| EnhancedFlow | `2` | Ein alternativer Flow-Modus, der die Erkennung von Tabellen unterstützt. |

## Anmerkungen

Verwenden Sie den Textbox-Modus, wenn das resultierende Dokument nicht weiter stark bearbeitet werden soll. Textboxen sind leicht zu modifizieren, wenn nicht viel zu tun ist.

Verwenden Sie den Flow-Modus, wenn das Ausgabedokument weitere Bearbeitungen benötigt. Absätze und Textrahmen im Flow-Modus ermöglichen eine einfache Modifikation des Textes, aber nicht unterstützte Formatierungsobjekte sehen im Vergleich zum Textbox-Modus schlechter aus.

### Siehe auch

* Klasse [DocSaveOptions](../docsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)