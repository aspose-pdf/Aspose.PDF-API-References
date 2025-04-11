---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XfdfReader-Klasse. Klasse, die das Lesen des XFDF-Formats durchführt
type: docs
weight: 2740
url: /de/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader-Klasse

Klasse, die das Lesen des XFDF-Formats durchführt.

```csharp
public sealed class XfdfReader
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Der Standardkonstruktor. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Analysiert die XFDF-Datei und gibt Informationen als Hashtable zurück. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importiert Anmerkungen aus der XFDF-Datei und fügt sie in das Dokument ein. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importiert Feldwerte aus der XFDF-Datei. |

## Beispiele

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Siehe auch

* Namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* Assembly [Aspose.PDF](../../)