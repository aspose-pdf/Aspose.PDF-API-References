---
title: "FdfReader"
linktitle: "FdfReader"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "FDF 形式の読み取りを実行するクラス。 Document doc = new Document(\\\"example.pdf\\\"); InputStream fdfStream = FileInputStream(\\\"file.fdf\\\"); FdfReader.readAnnotations(fdfStream."
type: docs
weight: 1370
url: /ja/java/com.aspose.pdf/fdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FdfReader

```
public final class FdfReader extends Object
```

FDF 形式の読み取りを実行するクラス。 Document doc = new Document("example.pdf"); InputStream fdfStream = FileInputStream("file.fdf"); FdfReader.readAnnotations(fdfStream, doc); fdfStream.close(); doc.save("example_out.pdf");

## メソッド

| メソッド | 説明 |
| --- | --- |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-) | FDF ファイルからアノテーションをインポートし、ドキュメントに配置します。 |

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.Document-}
FDF ファイルからアノテーションをインポートし、ドキュメントに配置します。
