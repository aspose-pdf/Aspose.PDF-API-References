---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptionsRecognitionMode Enum. Wenn eine PDF-Datei, die normalerweise ein festes Layout hat, konvertiert wird, versucht die Konvertierungsengine, Gruppierungen und mehrstufige Analysen durchzuführen, um die ursprüngliche Absicht des Dokumentautors wiederherzustellen und ein Ergebnis im Fließlayout zu erzeugen. Diese Eigenschaft passt diese Konvertierung für diese oder jene wünschenswerte Methode der Erkennung von Inhalten an.
type: docs
weight: 4070
url: /de/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode Aufzählung

Wenn eine PDF-Datei (die normalerweise ein festes Layout hat) konvertiert wird, versucht die Konvertierungsengine, Gruppierungen und mehrstufige Analysen durchzuführen, um die ursprüngliche Absicht des Dokumentautors wiederherzustellen und ein Ergebnis im Fließlayout zu erzeugen. Diese Eigenschaft passt diese Konvertierung für diese oder jene wünschenswerte Methode der Erkennung von Inhalten an.

```csharp
public enum RecognitionMode
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| Flow | `0` | Vollständiger Erkennungsmodus, die Engine versucht, Gruppierungen und mehrstufige Analysen durchzuführen, um die ursprüngliche Absicht des Dokumentautors wiederherzustellen und xhtml im Fließlayout zu erzeugen. |
| PdfFlow | `1` | Die Hauptidee dieser Konvertierung basiert auf der Erhaltung der "natürlichen" Reihenfolge der Inhaltsdarstellung, die während der Verarbeitung von PDF-Dokumenten entsteht. In den allgemeinen Fällen behalten PDF-Dokumente die Reihenfolge von oben nach unten und von links nach rechts (siehe Anhang directions.png). Diese Annahme ermöglicht es, einen einheitlichen Algorithmus zu erstellen, der Aps-Elemente mit Positionen (festes Layout) in Fließformate wie HTML, EPUB, DOC umwandelt. Dieser Modus ist besonders nützlich für die Konvertierung von PDF (APS) nach EPUB, da das EPUB-Format für E-Reader wie den Kindle oder Smartphones entwickelt wurde. Die Bildschirmgröße dieser Geräte ist normalerweise kleiner als die Bildschirmgröße eines gewöhnlichen PCs. Daher ist es besser, den Inhalt von EPUB-Dokumenten im Fließformat zu speichern, um eine korrekte Darstellung auf Bildschirmen unterschiedlicher Größen zu gewährleisten. In diesem Modus wird jede Spalte am Ende der vorherigen Spalte hinzugefügt, was es ermöglicht, die logische Struktur des transformierten Dokuments während der "Seitenaufteilung" in EPUB-Readern beizubehalten. Diese Errungenschaft ermöglicht eine korrekte Darstellung wissenschaftlicher oder Zeitschriftenartikel. |
| Fixed | `2` | Dieser Modus ist schnell und gut geeignet, um das ursprüngliche Aussehen der Seiten maximal zu bewahren, aber leider unterstützen viele EPUB-Reader kein xhtml mit festem Layout. |

### Siehe auch

* Klasse [EpubSaveOptions](../epubsaveoptions/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)