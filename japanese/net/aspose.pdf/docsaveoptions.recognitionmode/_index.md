---
title: Enum DocSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.DocSaveOptionsRecognitionMode enum. PDFドキュメントがワードプロセッシングドキュメントに変換される方法を制御します
type: docs
weight: 3770
url: /ja/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode 列挙型

PDFドキュメントがワードプロセッシングドキュメントに変換される方法を制御します。

```csharp
public enum RecognitionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Textbox | `0` | このモードは高速で、PDFファイルの元の外観を最大限に保持するのに適していますが、結果のドキュメントの編集可能性は制限される可能性があります。 |
| Flow | `1` | 完全認識モードで、エンジンはグループ化と多層分析を行い、元のドキュメントの著者の意図を復元し、最大限に編集可能なドキュメントを生成します。欠点は、出力ドキュメントが元のPDFファイルとは異なる見た目になる可能性があることです。 |
| EnhancedFlow | `2` | テーブルの認識をサポートする代替のフローモードです。 |

## 備考

結果のドキュメントがさらに大幅に編集される予定がない場合は、Textboxモードを使用してください。テキストボックスは、あまり手を加えない場合に簡単に修正できます。

出力ドキュメントがさらに編集する必要がある場合は、Flowモードを使用してください。フローモードの段落とテキストラインは、テキストの簡単な修正を可能にしますが、サポートされていないフォーマットオブジェクトはTextboxモードよりも見栄えが悪くなります。

### 関連項目

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)