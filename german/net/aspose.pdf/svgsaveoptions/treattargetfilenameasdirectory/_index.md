---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions-Feld. Diese Option definiert, ob ein Zielverzeichnis erstellt wird, falls es noch nicht vorhanden ist, mit demselben Namen wie die angeforderte Ausgabedatei anstelle der angeforderten Ausgabedatei selbst. So wird das Verzeichnis alle Ausgab SVG-Bilder der Seiten enthalten, wie unten beschrieben. Wenn keine Ausgabedateien von Seiten außer der ersten erstellt werden, werden diese genau im angeforderten Verzeichnis als Hauptausgabedatei erstellt, enthalten jedoch im Dateinamen den Suffix _2...n, der durch die Seitennummer definiert ist, z.B. wenn Sie die Ausgabedatei "C:\AsposeTests\output.svg" definieren und die Ausgabe mehrere SVG-Dateien von Seiten enthält, dann werden die Dateien der Seiten auch im Verzeichnis "C:\AsposeTests\" erstellt und haben die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw.
type: docs
weight: 50
url: /de/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory-Feld

Diese Option definiert, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei anstelle der angeforderten Ausgabedatei selbst erstellt wird. So wird das Verzeichnis alle Ausgab SVG-Bilder der Seiten enthalten (wie unten beschrieben). Wenn nicht, werden Ausgabedateien von Seiten, die nicht die erste sind, genau im angeforderten Verzeichnis als Hauptausgabedatei erstellt, enthalten jedoch im Dateinamen den Suffix _[2...n], der durch die Seitennummer definiert ist, z.B. wenn Sie die Ausgabedatei "C:\AsposeTests\output.svg" definieren und die Ausgabe mehrere SVG-Dateien von Seiten enthält, dann werden die Dateien der Seiten auch im Verzeichnis "C:\AsposeTests\" erstellt und haben die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw.

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### Siehe auch

* Klasse [SvgSaveOptions](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)