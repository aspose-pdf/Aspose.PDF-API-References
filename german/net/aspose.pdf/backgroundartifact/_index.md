---
title: BackgroundArtifact
second_title: Aspose.PDF für .NET-API-Referenz
description: Klasse beschreibt Hintergrundartefakt. Dieses Artefakt ermöglicht es den Hintergrund der Seite festzulegen.
type: docs
weight: 1350
url: /de/net/aspose.pdf/backgroundartifact/
---
## BackgroundArtifact class

Klasse beschreibt Hintergrundartefakt. Dieses Artefakt ermöglicht es, den Hintergrund der Seite festzulegen.

```csharp
public class BackgroundArtifact : Artifact
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [BackgroundArtifact](backgroundartifact)() | Initialisiert das BackgroundArtifact-Objekt. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ArtifactHorizontalAlignment](../../aspose.pdf/artifact/artifacthorizontalalignment) { get; set; } | Horizontale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [ArtifactVerticalAlignment](../../aspose.pdf/artifact/artifactverticalalignment) { get; set; } | Vertikale Ausrichtung des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [BackgroundColor](../../aspose.pdf/backgroundartifact/backgroundcolor) { get; set; } | Ruft die Hintergrundfarbe des Hintergrundartefakts ab oder legt sie fest |
| [BackgroundImage](../../aspose.pdf/backgroundartifact/backgroundimage) { get; set; } | Ruft das Hintergrundbild des Hintergrundartefakts ab oder legt es fest |
| [BottomMargin](../../aspose.pdf/artifact/bottommargin) { get; set; } | Unterer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [Contents](../../aspose.pdf/artifact/contents) { get; } | Ruft eine Sammlung interner Artefaktoperatoren ab. |
| [CustomSubtype](../../aspose.pdf/artifact/customsubtype) { get; set; } | Ruft den Namen des Artefaktuntertyps ab. Kann verwendet werden, wenn der Artefakt-Untertyp kein Standard-Untertyp ist. |
| [CustomType](../../aspose.pdf/artifact/customtype) { get; set; } | Ruft den Namen des Artefakttyps ab. Kann verwendet werden, wenn der Artefakttyp nicht dem Standard entspricht. |
| [Form](../../aspose.pdf/artifact/form) { get; } | Ruft XForm des Artefakts ab (wenn XForm verwendet wird). |
| [Image](../../aspose.pdf/artifact/image) { get; } | Ruft ein Bild des Artefakts ab (falls vorhanden). |
| [IsBackground](../../aspose.pdf/artifact/isbackground) { get; set; } | Wenn wahr Artefakt wird hinter Seiteninhalten platziert. |
| [LeftMargin](../../aspose.pdf/artifact/leftmargin) { get; set; } | Linker Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [Lines](../../aspose.pdf/artifact/lines) { get; } | Zeilen eines mehrzeiligen Textartefakts. |
| [Opacity](../../aspose.pdf/artifact/opacity) { get; set; } | Ruft die Deckkraft des Artefakts ab oder legt sie fest. Mögliche Werte liegen im Bereich 0..1. |
| [Position](../../aspose.pdf/artifact/position) { get; set; } | Ruft die Position des Artefakts ab oder legt sie fest. Wenn diese Eigenschaft angegeben ist, werden Ränder und Ausrichtungen ignoriert. |
| [Rectangle](../../aspose.pdf/artifact/rectangle) { get; } | Ruft das Rechteck des Artefakts ab. |
| [RightMargin](../../aspose.pdf/artifact/rightmargin) { get; set; } | Rechter Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [Rotation](../../aspose.pdf/artifact/rotation) { get; set; } | Ruft den Rotationswinkel des Artefakts ab oder legt ihn fest. |
| [Subtype](../../aspose.pdf/artifact/subtype) { get; set; } | Ruft den Untertyp des Artefakts ab. Wenn das Artefakt einen nicht standardmäßigen Untertyp hat, kann der Name des Untertyps über CustomSubtype. gelesen werden. |
| [Text](../../aspose.pdf/artifact/text) { get; set; } | Ruft den Text des Artefakts ab. |
| [TextState](../../aspose.pdf/artifact/textstate) { get; set; } | Textstatus für Artefakttext. |
| [TopMargin](../../aspose.pdf/artifact/topmargin) { get; set; } | Oberer Rand des Artefakts. Wenn die Position explizit angegeben ist (in der Eigenschaft Position), wird dieser Wert ignoriert. |
| [Type](../../aspose.pdf/artifact/type) { get; set; } | Ruft den Artefakttyp ab. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [BeginUpdates](../../aspose.pdf/artifact/beginupdates)() | Verzögerte Aktualisierungen starten. Verwenden Sie diese Funktion, wenn Sie mehrere Änderungen an demselben Artefakt vornehmen müssen, um die Leistung zu verbessern. Normalerweise werden Artefaktoperatoren immer dann geändert, wenn die Artefakteigenschaft geändert wurde. Dies bewirkt jedes Mal, wenn das Artefakt geändert wurde, eine Änderung von Seiteninhalten . Um diesen Effekt zu vermeiden, platzieren Sie alle Artefaktaktualisierungen zwischen StartUpdates/SaveUpdates-Aufrufen. Dadurch können Seiteninhalte nur einmal geändert werden. |
| [Dispose](../../aspose.pdf/artifact/dispose)() | Entsorgen Sie das Artefakt. |
| [GetValue](../../aspose.pdf/artifact/getvalue)(string) | Ruft den benutzerdefinierten Wert des Artefakts ab. |
| [RemoveValue](../../aspose.pdf/artifact/removevalue)(string) | Benutzerdefinierten Wert aus dem Artefakt entfernen. |
| [SaveUpdates](../../aspose.pdf/artifact/saveupdates)() | Speichert alle Aktualisierungen im Artefakt, die nach dem Aufruf von BeginUpdates() vorgenommen wurden. |
| [SetImage](../../aspose.pdf/artifact/setimage)(Stream) | Legt das Bild des Artefakts fest. |
| [SetImage](../../aspose.pdf/artifact/setimage)(string) | Legt das Bild des Artefakts fest. |
| [SetLinesAndState](../../aspose.pdf/artifact/setlinesandstate)(string[], TextState) | Legen Sie Text und Texteigenschaften des Artefakts fest. Ermöglicht die Angabe mehrerer Zeilen. |
| [SetPdfPage](../../aspose.pdf/artifact/setpdfpage)(Page) | Legt die PDF-Seite fest, die auf der Dokumentseite als Artefakt platziert wird. |
| [SetText](../../aspose.pdf/artifact/settext)(FormattedText) | Legt den Text des Artefakts fest. |
| [SetTextAndState](../../aspose.pdf/artifact/settextandstate)(string, TextState) | Legen Sie Text und Texteigenschaften des Artefakts fest. |
| [SetValue](../../aspose.pdf/artifact/setvalue)(string, string) | Legt den benutzerdefinierten Wert des Artefakts fest. |

### Siehe auch

* class [Artifact](../artifact)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
