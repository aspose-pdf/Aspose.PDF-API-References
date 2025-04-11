---
title: Class HeaderArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HeaderArtifact-Klasse. Die Klasse beschreibt das Header-Artefakt. Dieses Artefakt kann verwendet werden, um die Überschrift der Seite festzulegen.
type: docs
weight: 5420
url: /de/net/aspose.pdf/headerartifact/
---
## HeaderArtifact-Klasse

Die Klasse beschreibt das Header-Artefakt. Dieses Artefakt kann verwendet werden, um die Überschrift der Seite festzulegen.

```csharp
public class HeaderArtifact : Artifact
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [HeaderArtifact](headerartifact/)() | Erstellt eine Instanz des Header-Artefakts. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Unterer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Ruft die Sammlung der internen Operatoren des Artefakts ab. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Ruft den Namen des Artefakt-Subtyps ab. Kann verwendet werden, wenn der Artefakt-Subtype kein Standard-Subtype ist. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Ruft den Namen des Artefakt-Typs ab. Kann verwendet werden, wenn der Artefakt-Typ nicht standardmäßig ist. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Ruft das XForm des Artefakts ab (wenn XForm verwendet wird). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Ruft das Bild des Artefakts ab (wenn vorhanden). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Wenn wahr, wird das Artefakt hinter dem Seiteninhalt platziert. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Linker Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linien des mehrzeiligen Textartefakts. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Ruft die Opazität des Artefakts ab oder legt sie fest. Mögliche Werte liegen im Bereich von 0..1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Ruft die Position des Artefakts ab oder legt sie fest. Wenn diese Eigenschaft angegeben ist, werden Ränder und Ausrichtungen ignoriert. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Ruft das Rechteck des Artefakts ab. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Rechter Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Ruft den Rotationswinkel des Artefakts ab oder legt ihn fest. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Ruft den Subtyp des Artefakts ab. Wenn das Artefakt einen nicht standardmäßigen Subtyp hat, kann der Name des Subtyps über CustomSubtype gelesen werden. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Ruft den Text des Artefakts ab. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textzustand für den Text des Artefakts. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Oberer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Position-Eigenschaft), wird dieser Wert ignoriert. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Ruft den Typ des Artefakts ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Beginnt verzögerte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden die Operatoren des Artefakts jedes Mal geändert, wenn eine Eigenschaft des Artefakts geändert wird. Dies führt dazu, dass der Seiteninhalt jedes Mal geändert wird, wenn das Artefakt geändert wird. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt-Updates zwischen den Aufrufen von StartUpdates/SaveUpdates. Dies ermöglicht es, den Seiteninhalt nur einmal zu ändern. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Gibt das Artefakt frei. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Ruft den benutzerdefinierten Wert des Artefakts ab. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Entfernt den benutzerdefinierten Wert aus dem Artefakt. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Speichert alle Updates im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Setzt das Bild des Artefakts. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Setzt das Bild des Artefakts. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Setzt den Text und die Texteigenschaften des Artefakts. Ermöglicht die Angabe mehrerer Zeilen. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Legt fest, welcher String durch die Seitenzahl ersetzt wird. Der Standardwert ist #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Setzt die PDF-Seite, die als Artefakt auf der Dokumentseite platziert wird. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Setzt den Text des Artefakts. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Setzt den Text und die Texteigenschaften des Artefakts. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Setzt den benutzerdefinierten Wert des Artefakts. |

### Siehe auch

* Klasse [Artifact](../artifact/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)