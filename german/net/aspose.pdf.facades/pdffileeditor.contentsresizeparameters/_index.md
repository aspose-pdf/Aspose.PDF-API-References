---
title: Class PdfFileEditor.ContentsResizeParameters
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorContentsResizeParameters-Klasse. Klasse zur Spezifizierung von Seitenänderungsparametern. Ermöglicht das Festlegen der folgenden Parameter Größe der Ergebnisseite in Standardraumeinheiten oder in Prozent der ursprünglichen Seitengröße; Linke, Obere, Untere und Rechte Ränder in Standardraumeinheiten oder in Prozent der ursprünglichen Seitengröße; Einige Werte können null gelassen werden für automatische Berechnung. Diese Werte werden aus dem Rest der Seitengröße nach der Berechnung der ausdrücklich angegebenen Werte berechnet. Diese Klasse wird in der ResizeContents-Methode verwendet.
type: docs
weight: 4480
url: /de/net/aspose.pdf.facades/pdffileeditor.contentsresizeparameters/
---
## PdfFileEditor.ContentsResizeParameters-Klasse

Klasse zur Spezifizierung von Seitenänderungsparametern. Ermöglicht das Festlegen der folgenden Parameter: Größe der Ergebnisseite (Breite, Höhe) in Standardraumeinheiten oder in Prozent der ursprünglichen Seitengröße; Linke, Obere, Untere und Rechte Ränder in Standardraumeinheiten oder in Prozent der ursprünglichen Seitengröße; Einige Werte können null gelassen werden für automatische Berechnung. Diese Werte werden aus dem Rest der Seitengröße nach der Berechnung der ausdrücklich angegebenen Werte berechnet. Zum Beispiel: Wenn die Seitenbreite = 100 und die neue Seitenbreite 60 Einheiten beträgt, werden die linken und rechten Ränder automatisch berechnet: (100 - 60) / 2 = 15. Diese Klasse wird in der ResizeContents-Methode verwendet.

```csharp
public class ContentsResizeParameters
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor)() | Erstellt Änderungsparameter, bei denen alle Werte auf "auto" gesetzt sind. Später können Ränder und Inhaltsgrößen angegeben werden, wenn erforderlich. |
| [ContentsResizeParameters](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/.ctor#constructor_1)(ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue, ContentsResizeValue) | Erstellt Änderungsparameter mit angegebenen Randwerten und Inhaltsgröße. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BottomMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/bottommargin) { get; set; } | Ruft den unteren Rand der Ergebnisseite ab oder setzt ihn. |
| [ContentsHeight](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsheight) { get; set; } | Ruft die Höhe des Inhalts der Quellseite auf der Ergebnisseite ab oder setzt sie. |
| [ContentsWidth](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentswidth) { get; set; } | Ruft die Breite des Inhalts der Quellseite auf der Ergebnisseite ab oder setzt sie. |
| [LeftMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/leftmargin) { get; set; } | Ruft den linken Rand der Ergebnisseite ab oder setzt ihn. |
| [RightMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/rightmargin) { get; set; } | Ruft den rechten Rand der Ergebnisseite ab oder setzt ihn. |
| [TopMargin](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/topmargin) { get; set; } | Ruft den oberen Rand der Ergebnisseite ab oder setzt ihn. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ContentSize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsize)(double, double) | Erstellt Änderungsparameter mit angegebener Inhaltsgröße. |
| static [ContentSizePercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/contentsizepercent)(double, double) | Erstellt Änderungsparameter mit angegebener Inhaltsgröße in Prozent der ursprünglichen Seitengröße. Ränder werden automatisch berechnet. |
| static [Margins](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/margins)(double, double, double, double) | Erstellt Änderungsparameter mit angegebenen Randwerten. Die Inhaltsgröße wird automatisch berechnet. |
| static [MarginsPercent](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/marginspercent)(double, double, double, double) | Erstellt Änderungsparameter. Ränder werden in Prozent der ursprünglichen Seitengröße angegeben. |
| static [PageResize](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresize)(double, double) | Erstellt Änderungsparameter für die Seitenänderung. |
| static [PageResizePct](../../aspose.pdf.facades/pdffileeditor.contentsresizeparameters/pageresizepct)(double, double) | Erstellt Änderungsparameter für die Seitenänderung. Neue Größen werden in Prozent angegeben. |

### Siehe auch

* Klasse [PdfFileEditor](../pdffileeditor/)
* Namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../)