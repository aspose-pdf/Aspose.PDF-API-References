---
title: "列挙型 DocSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.DocSaveOptionsRecognitionMode 列挙型。PDF ドキュメントがワードプロセッシング ドキュメントに変換される方法を制御できます。"
type: docs
weight: 3890
url: /ja/net/aspose.pdf/docsaveoptions.recognitionmode/
---
## DocSaveOptions.RecognitionMode enumeration

PDF ドキュメントがワードプロセッシング文書に変換される方法を制御できるようにします。

```csharp
public enum RecognitionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Textbox | `0` | このモードは高速で、PDF ファイルの元の外観を最大限に保持するのに適していますが、生成されたドキュメントの編集可能性が制限される可能性があります。 |
| Flow | `1` | フル認識モードでは、エンジンがグルーピングと多層解析を実行し、元の Document 作成者の意図を復元して最大限に編集可能な Document を生成します。欠点は、出力 Document が元の PDF ファイルと見た目が異なる可能性があることです。 |
| EnhancedFlow | `2` | テーブルの認識をサポートする代替の Flow モードです。 |

## 備考

結果のドキュメントが今後大幅に編集されない場合は、Textbox モードを使用してください。テキストボックスは、作業量が少ないときに簡単に修正できます。

出力ドキュメントがさらに編集される必要がある場合は、Flow モードを使用してください。Flow モードの段落やテキスト行はテキストの簡単な修正を可能にしますが、サポートされていない書式設定オブジェクトは Textbox モードよりも見栄えが悪くなります。

### 関連項目

* class [DocSaveOptions](../docsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


