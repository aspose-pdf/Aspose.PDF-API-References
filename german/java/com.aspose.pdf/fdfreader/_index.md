---
title: "FdfReader"
linktitle: "FdfReader"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Klasse, die das Lesen des FDF-Formats durchführt. Document doc = new Document(\\\"example.pdf\\\"); InputStream fdfStream = FileInputStream(\\\"file.fdf\\\"); FdfReader.readAnnotations(fdfStream."
type: docs
weight: 1370
url: /de/java/com.aspose.pdf/fdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FdfReader

```
public final class FdfReader extends Object
```

Klasse, die das Lesen des FDF-Formats durchführt. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf");

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-) | Importiert Anmerkungen aus einer FDF-Datei und fügt sie in das Dokument ein. |

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-}
Importiert Anmerkungen aus einer FDF-Datei und fügt sie in das Dokument ein.
