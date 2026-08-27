---
title: "列挙体 PdfFileEditor.ConcatenateCorruptedFileAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Facades.PdfFileEditorConcatenateCorruptedFileAction 列挙体。結合プロセスで破損したファイルに遭遇したときに実行されるアクション"
type: docs
weight: 4590
url: /ja/net/aspose.pdf.facades/pdffileeditor.concatenatecorruptedfileaction/
---
## PdfFileEditor.ConcatenateCorruptedFileAction enumeration

結合プロセスで破損したファイルに遭遇したときに実行されるアクションです。

```csharp
public enum ConcatenateCorruptedFileAction
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| StopWithError | `0` | 破損したファイルに遭遇した場合、結合プロセスを停止しエラーを返します。 |
| ConcatenateIgnoringCorrupted | `1` | 破損したファイルに遭遇した場合、結合を停止せず、破損したファイルを処理しません。破損したファイルの一覧は Failures プロパティで取得できます。 |
| ConcatenateIgnoringCorruptedObjects | `2` | ソース ドキュメントで破損したオブジェクトに遭遇した場合、プロセスは停止せず、破損したオブジェクトだけが無視されます。 |

### 関連項目

* class [PdfFileEditor](../pdffileeditor/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


