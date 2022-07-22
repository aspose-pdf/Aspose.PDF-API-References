---
title: SvgSaveOptions
second_title: Aspose.PDF für .NET-API-Referenz
description: Speicheroptionen für den Export in das SVG-Format
type: docs
weight: 6450
url: /de/net/aspose.pdf/svgsaveoptions/
---
## SvgSaveOptions class

Speicheroptionen für den Export in das SVG-Format

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, dass das Antwortobjekt geschlossen wird, nachdem das Dokument in der Antwort gespeichert wurde. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bild oder Text für PDF-Dokumente mit OCR-Unterebene. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format der Datenspeicherung. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Rückruf zur Behandlung von generierten Warnungen. Der WarningHandler gibt das ReturnAction-Aufzählungselement zurück, das entweder Continue oder Abort angibt. Continue ist die Standardaktion und der Speichervorgang wird fortgesetzt, der Benutzer kann jedoch auch Abbrechen zurückgeben, in diesem Fall sollte der Speichervorgang beendet werden. |

## Felder

| Name | Beschreibung |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive) | Gibt an, ob die Ausgabe als ein Zip-Archiv erstellt wird. Bitte beachten Sie den Kommentar zu den 'TreatTargetFileNameAsDirectory'-Optionen, um Regeln zur Benennung von SVG-Dateien von Seiten für mehrseitige Quelldokumente anzuzeigen, die auch auf gezippte Ausgabedateien angewendet werden. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving) | Dieses Feld kann eine Speicherstrategie enthalten, die (falls vorhanden) während der Konvertierung für die angepasste Handhabung von erstellten referenzierten externen Bildern Dateien (wie eingebettete BMP- oder JPEG-Dateien) verwendet werden muss, die in gespeicherte SVG-Dateien eingebettet sind. Diese Strategie muss Ressourcen verarbeiten und die Zeichenfolge zurückgeben stellt den gewünschten URI der gespeicherten Ressource im generierten SVG dar. Wenn die Verarbeitung für diese oder jene Datei aus irgendeinem Grund durch den Code des Konverters selbst und nicht im benutzerdefinierten Code erfolgen muss, setzen Sie bitte das benutzerdefinierte Code-Flag 'CustomProcessingCancelled' der Variable des Parameters 'imageSavingInfo' Es signalisiert dem Konverter, dass alle notwendigen Schritte zur Verarbeitung dieser Ressource im Konverter selbst durchgeführt werden müssen, als ob es keinen externen benutzerdefinierten Code gäbe. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels) | Gibt an, ob das Ausgabedokument von typografischen Punkten auf Pixel skaliert werden soll. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory) | Diese Option definiert, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit dem gleichen Namen wie die angeforderte Ausgabedatei anstelle der angeforderten Ausgabedatei selbst erstellt wird. Dieses Verzeichnis enthält also alle ausgegebenen SVG-Bilder der Seiten (wie unten beschrieben). . Wenn nein, werden Ausgabedateien von anderen Seiten als der ersten genau im angeforderten Verzeichnis als Hauptausgabedatei erstellt, enthalten aber im Dateinamen das Suffix _[2...n], das wird durch die Seitennummer definiert, z Sie definieren die Ausgabedatei "C:\AsposeTests\output.svg" und die Ausgabe enthält mehrere SVG-Dateien von Seiten, dann werden Seitendateien auch im Verzeichnis "C:\AsposeTests\" erstellt und haben die Namen "output. svg', 'output_2.svg', 'output_3.svg' etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen) die aus mehreren, nebeneinander angeordneten, gleichen Hintergrundbildern bestehen. In solchen Fällen erzeugen Renderer von Zielformaten (z. B. MsWord für DOCS-Format) manchmal sichtbare Grenzen zwischen Teilen von Hintergrundbildern , weil sich ihre Techniken der Bildkantenglättung (Anti-Aliasing) von Acrobat Reader unterscheiden. Wenn es so aussieht, als ob das exportierte Dokument solche sichtbaren Grenzen zwischen Teilen derselben Hintergrundbilder enthält, versuchen Sie bitte, diese Einstellung zu verwenden, um davon zu befreien unerwünschte Wirkung. ACHTUNG! Diese Qualitätsoptimierung verlangsamt normalerweise die Konvertierung erheblich, also verwenden Sie diese Option bitte nur, wenn es wirklich notwendig ist. |

### Siehe auch

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* namensraum [Aspose.Pdf](../../aspose.pdf)
* Montage [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
