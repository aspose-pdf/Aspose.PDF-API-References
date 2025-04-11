---
title: Class FooterArtifact
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.FooterArtifact-Klasse. Beschreibt Fußzeilenartefakt. Dies kann verwendet werden, um die Fußzeile der Seite festzulegen
type: docs
weight: 4930
url: /de/net/aspose.pdf/footerartifact/
---
## FooterArtifact-Klasse

Beschreibt Fußzeilenartefakt. Dies kann verwendet werden, um die Fußzeile der Seite festzulegen.

```csharp
public class FooterArtifact : Artifact
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [FooterArtifact](footerartifact/)() | Erstellt eine Instanz des Fußzeilenartefakts. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment/) { get; set; } | Horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment/) { get; set; } | Vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin/) { get; set; } | Unterer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Contents](../../aspose.pdf/artifact/contents/) { get; } | Gibt die Sammlung der internen Operatoren des Artefakts zurück. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype/) { get; set; } | Gibt den Namen des Untertyps des Artefakts zurück. Kann verwendet werden, wenn der Untertyp des Artefakts kein Standarduntertyp ist. |
| [CustomType](../../aspose.pdf/artifact/customtype/) { get; set; } | Gibt den Namen des Typs des Artefakts zurück. Kann verwendet werden, wenn der Typ des Artefakts nicht standardmäßig ist. |
| [Form](../../aspose.pdf/artifact/form/) { get; } | Gibt das XForm des Artefakts zurück (wenn XForm verwendet wird). |
| [Image](../../aspose.pdf/artifact/image/) { get; } | Gibt das Bild des Artefakts zurück (wenn vorhanden). |
| [IsBackground](../../aspose.pdf/artifact/isbackground/) { get; set; } | Wenn wahr, wird das Artefakt hinter den Seiteninhalten platziert. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin/) { get; set; } | Linker Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Lines](../../aspose.pdf/artifact/lines/) { get; } | Linien des mehrzeiligen Textartefakts. |
| [Opacity](../../aspose.pdf/artifact/opacity/) { get; set; } | Gibt die Opazität des Artefakts zurück oder legt sie fest. Mögliche Werte liegen im Bereich von 0 bis 1. |
| [Position](../../aspose.pdf/artifact/position/) { get; set; } | Gibt die Position des Artefakts zurück oder legt sie fest. Wenn diese Eigenschaft angegeben ist, werden Ränder und Ausrichtungen ignoriert. |
| [Rectangle](../../aspose.pdf/artifact/rectangle/) { get; } | Gibt das Rechteck des Artefakts zurück. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin/) { get; set; } | Rechter Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Rotation](../../aspose.pdf/artifact/rotation/) { get; set; } | Gibt den Rotationswinkel des Artefakts zurück oder legt ihn fest. |
| [Subtype](../../aspose.pdf/artifact/subtype/) { get; set; } | Gibt den Untertyp des Artefakts zurück. Wenn das Artefakt einen nicht standardmäßigen Untertyp hat, kann der Name des Untertyps über CustomSubtype gelesen werden. |
| [Text](../../aspose.pdf/artifact/text/) { get; set; } | Gibt den Text des Artefakts zurück oder legt ihn fest. |
| [TextState](../../aspose.pdf/artifact/textstate/) { get; set; } | Textzustand für den Text des Artefakts. |
| [TopMargin](../../aspose.pdf/artifact/topmargin/) { get; set; } | Oberer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Positionseigenschaft), wird dieser Wert ignoriert. |
| [Type](../../aspose.pdf/artifact/type/) { get; set; } | Gibt den Typ des Artefakts zurück. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates/)() | Beginnt verzögerte Updates. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen am selben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden die Operatoren des Artefakts jedes Mal geändert, wenn eine Eigenschaft des Artefakts geändert wurde. Dies führt dazu, dass die Seiteninhalte jedes Mal geändert werden, wenn das Artefakt geändert wurde. Um diesen Effekt zu vermeiden, setzen Sie alle Artefakt-Updates zwischen den Aufrufen von StartUpdates/SaveUpdates. Dies ermöglicht es, die Seiteninhalte nur einmal zu ändern. |
| [Dispose](../../aspose.pdf/artifact/dispose/)() | Gibt das Artefakt frei. |
| [GetValue](../../aspose.pdf/artifact/getvalue/)(string) | Gibt den benutzerdefinierten Wert des Artefakts zurück. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue/)(string) | Entfernt den benutzerdefinierten Wert aus dem Artefakt. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates/)() | Speichert alle Updates im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(Stream) | Legt das Bild des Artefakts fest. |
| [SetImage](../../aspose.pdf/artifact/setimage/)(string) | Legt das Bild des Artefakts fest. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate/)(string[], TextState) | Legt den Text und die Texteigenschaften des Artefakts fest. Ermöglicht die Angabe mehrerer Zeilen. |
| [SetPageNumberReplacementString](../../aspose.pdf/artifact/setpagenumberreplacementstring/)(string) | Legt fest, welcher String durch die Seitenzahl ersetzt wird. Der Standardwert ist #. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage/)(Page) | Legt die PDF-Seite fest, die als Artefakt auf der Dokumentseite platziert wird. |
| [SetText](../../aspose.pdf/artifact/settext/)(FormattedText) | Legt den Text des Artefakts fest. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate/)(string, TextState) | Legt den Text und die Texteigenschaften des Artefakts fest. |
| [SetValue](../../aspose.pdf/artifact/setvalue/)(string, string) | Legt den benutzerdefinierten Wert des Artefakts fest. |

### Siehe auch

* Klasse [Artifact](../artifact/)
* Namespace [Aspose.Pdf](../../aspose.pdf/)
* Assembly [Aspose.PDF](../../)