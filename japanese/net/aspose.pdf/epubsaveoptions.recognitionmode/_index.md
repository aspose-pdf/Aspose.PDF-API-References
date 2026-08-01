---
title: "列挙型 EpubSaveOptions.RecognitionMode"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.EpubSaveOptionsRecognitionMode 列挙型。通常固定レイアウトの PDF ファイルが変換される際、変換エンジンはグループ化と多層分析を行い、元の文書作者の意図を復元し、フロー レイアウトで結果を生成しようとします。このプロパティは、コンテンツ認識の望ましい方法に合わせてその変換を調整します。"
type: docs
weight: 4190
url: /ja/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode enumeration

PDF ファイル（通常は固定レイアウト）を変換する際、変換エンジンはグルーピングと多層解析を実行して、元の Document 作者の意図を復元し、フロー レイアウトで結果を生成しようとします。このプロパティは、コンテンツ認識の望ましい方法に合わせてその変換を調整します。

```csharp
public enum RecognitionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Flow | `0` | 完全認識モードでは、エンジンがグループ化と多層分析を行い、元の文書作者の意図を復元し、フロー レイアウトで XHTML を生成しようとします。 |
| PdfFlow | `1` | この変換の主な考え方は、PDF 文書の処理中に形成されるコンテンツ描画の "natural" 順序を保持することに基づいています。一般的に PDF 文書は上から下へ、左から右への描画順序を保ちます（添付の directions.png を参照）。この前提により、位置情報（固定レイアウト）を持つ Aps 要素を HTML、EPUB、DOC などのフロー形式に変換する単一パスアルゴリズムを作成できます。このモードは、PDF（APS）から EPUB への変換に特に有用です。EPUB 形式は Kindle やスマートフォンなどの電子書籍リーダー向けに開発されたため、これらのデバイスの画面サイズは通常の PC より小さくなります。したがって、EPUB 文書のコンテンツはフロー形式で保存した方が、異なるサイズの画面で正しく表示されます。このモードでは、各列が前の列の末尾に追加されるため、EPUB リーダーでの "pagination" 中に変換された文書の論理構造を保持できます。この成果により、学術論文や雑誌記事を正しくレンダリングできます。 |
| Fixed | `2` | このモードは高速で、元のページの外観を最大限に保持するのに適していますが、残念ながら多くの EPUB リーダーは固定レイアウトの XHTML をサポートしていません。 |

### 関連項目

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


