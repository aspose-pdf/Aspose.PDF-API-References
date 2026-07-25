---
title: "FdfReader"
linktitle: "FdfReader"
second_title: "Aspose.PDF for Java API 参考"
description: "执行读取 FDF 格式的类。Document doc = new Document(\\\"example.pdf\\\"); InputStream fdfStream = FileInputStream(\\\"file.fdf\\\"); FdfReader.readAnnotations(fdfStream."
type: docs
weight: 1370
url: /zh/java/com.aspose.pdf/fdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FdfReader

```
public final class FdfReader extends Object
```

执行 FDF 格式读取的类。Document doc = new Document(\"example.pdf\"); InputStream fdfStream = FileInputStream(\"file.fdf\"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save(\"example_out.pdf\");

## 方法

| 方法 | 描述 |
| --- | --- |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-) | 从 FDF 文件导入注释并将其放入文档中。 |

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-}
从 FDF 文件导入注释并将其放入文档中。
