---
title: "PdfFileEditor.ConcatenateCorruptedFileAction"
linktitle: "PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "結合処理中に破損したファイルに遭遇したときに実行されるアクションです。"
type: docs
weight: 420
url: /ja/java/com.aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction, com.aspose.ms.System.Enum, com.aspose.pdf.facades.PdfFileEditor.ConcatenateCorruptedFileAction

```
public static final class PdfFileEditor.ConcatenateCorruptedFileAction extends com.aspose.ms.System.Enum
```

結合処理中に破損したファイルに遭遇したときに実行されるアクションです。

## フィールド

| フィールド | 説明 |
| --- | --- |
| [ConcatenateIgnoringCorrupted](#ConcatenateIgnoringCorrupted) | 破損したファイルが見つかった場合、連結を停止せず、破損したファイルは処理しません。破損したファイルの一覧は Failures プロパティで取得できます。 |
| [ConcatenateIgnoringCorruptedObjects](#ConcatenateIgnoringCorruptedObjects) | ソース文書で破損したオブジェクトが見つかった場合、処理は停止せず、破損したオブジェクトだけが無視されます。 |
| [StopWithError](#StopWithError) | 破損したファイルが見つかった場合、連結処理を停止しエラーを返します。 |

### ConcatenateIgnoringCorrupted {#ConcatenateIgnoringCorrupted}
```
public static final int ConcatenateIgnoringCorrupted
```

破損したファイルが見つかった場合、連結を停止せず、破損したファイルは処理しません。破損したファイルの一覧は Failures プロパティで取得できます。

### ConcatenateIgnoringCorruptedObjects {#ConcatenateIgnoringCorruptedObjects}
```
public static final int ConcatenateIgnoringCorruptedObjects
```

ソース文書で破損したオブジェクトが見つかった場合、処理は停止せず、破損したオブジェクトだけが無視されます。

### StopWithError {#StopWithError}
```
public static final int StopWithError
```

破損したファイルが見つかった場合、連結処理を停止しエラーを返します。
