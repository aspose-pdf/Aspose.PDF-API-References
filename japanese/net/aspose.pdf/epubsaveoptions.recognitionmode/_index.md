---
title: Enum EpubSaveOptions.RecognitionMode
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.EpubSaveOptionsRecognitionMode enum。通常、固定レイアウトを持つPDFファイルが変換されるとき、変換エンジンは元の文書の著者の意図を復元し、フローレイアウトで結果を生成するために、グルーピングと多層分析を行おうとします。このプロパティは、コンテンツの認識のための望ましい方法に合わせてその変換を調整します。
type: docs
weight: 4070
url: /ja/net/aspose.pdf/epubsaveoptions.recognitionmode/
---
## EpubSaveOptions.RecognitionMode 列挙型

PDFファイル（通常は固定レイアウトを持つ）が変換されるとき、変換エンジンは元の文書の著者の意図を復元し、フローレイアウトで結果を生成するために、グルーピングと多層分析を行おうとします。このプロパティは、コンテンツの認識のための望ましい方法に合わせてその変換を調整します。

```csharp
public enum RecognitionMode
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Flow | `0` | 完全認識モード。エンジンはグルーピングと多層分析を行い、元の文書の著者の意図を復元し、フローレイアウトでxhtmlを生成しようとします。 |
| PdfFlow | `1` | この変換の主なアイデアは、PDF文書の処理中に形成される「自然な」コンテンツレンダリングの順序を保存することに基づいています。一般的な場合、PDF文書は上から下、左から右のレンダリング順序を保持します（添付のdirections.pngを参照）。この仮定により、位置（固定レイアウト）を持つAps要素をHTML、EPUB、DOCなどのフローフォーマットに変換する単一路径アルゴリズムを作成できます。このモードは、EPUB形式がKindleやスマートフォンのような電子リーダー向けに開発されたため、PDF（APS）からEPUBへの変換に特に便利です。これらのデバイスの画面サイズは通常、普通のPCの画面サイズよりも小さいため、異なるサイズの画面で正しくレンダリングするために、EPUB文書のコンテンツはフローフォーマットで保存する方が良いです。このモードでは、各列が前の列の末尾に追加され、EPUBリーダーでの「ページネーション」中に変換された文書の論理構造を保持できます。この成果により、科学的または雑誌の記事を正しくレンダリングできます。 |
| Fixed | `2` | このモードは高速で、元のページの外観を最大限に保持するのに適していますが、残念ながら多くのEPUBリーダーは固定レイアウトのxhtmlをサポートしていません。 |

### 参照

* class [EpubSaveOptions](../epubsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)