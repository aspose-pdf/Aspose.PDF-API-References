---
title: Enum PdfFileEditor.ConcatenateCorruptedFileAction
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction 列挙型。結合プロセスで破損したファイルに遭遇したときに実行されるアクション
type: docs
weight: 4470
url: /ja/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction 列挙型

結合プロセスで破損したファイルに遭遇したときに実行されるアクション。

```csharp
public enum ConcatenateCorruptedFileAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| StopWithError | `0` | 破損したファイルに遭遇した場合、結合プロセスを停止し、エラーを返します。 |
| ConcatenateIgnoringCorrupted | `1` | 破損したファイルに遭遇した場合、結合を停止せず、破損したファイルを処理しません。破損したファイルのリストは Failures プロパティでアクセスできます。 |
| ConcatenateIgnoringCorruptedObjects | `2` | ソースドキュメントで破損したオブジェクトに遭遇した場合、プロセスは停止せず、破損したオブジェクトのみが無視されます。 |

### 参照

* クラス [PdfFileEditor](../pdffileeditor/)
* 名前空間 [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../)