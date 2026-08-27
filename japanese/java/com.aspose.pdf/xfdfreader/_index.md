---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "<p> XFDF 形式の読み取りを実行するクラスです。 </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /ja/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> XFDF フォーマットの読み取りを実行するクラスです。 </p> <hr> <p> <code> Document doc = new Document(\"example.pdf\"); InputStream xfdfStream = new FileInputStream(\"filename\"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save(\"example_out.pdf\"); </code> </p>

## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## メソッド

| メソッド | 説明 |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | XFDF ファイルを解析し、情報をハッシュテーブルとして返します。 |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | XFDF ファイルから注釈をインポートし、ドキュメントに配置します。 |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | XFDF ファイルからフィールド値をインポートします。 |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
XFDF ファイルを解析し、情報をハッシュテーブルとして返します。

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
XFDF ファイルから注釈をインポートし、ドキュメントに配置します。

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
XFDF ファイルからフィールド値をインポートします。
