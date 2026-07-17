---
title: FdfReader
linktitle: FdfReader
second_title: Aspose.PDF for Java API Reference
description: Class which performs reading of FDF format. Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream.
type: docs
weight: 1370
url: /java/com.aspose.pdf/fdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FdfReader

```
public final class FdfReader extends Object
```

Class which performs reading of FDF format. Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf");

## Methods

| Method | Description |
| --- | --- |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-) | Import annotations from FDF file and put them into document. |

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-}
Import annotations from FDF file and put them into document.
