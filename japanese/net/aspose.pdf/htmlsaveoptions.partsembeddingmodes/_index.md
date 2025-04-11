---
title: Enum HtmlSaveOptions.PartsEmbeddingModes
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes enum。この列挙型は、HTMLで参照されるファイルの埋め込みの可能なモードを列挙します。参照されたファイル（HTML、フォント、画像、CSS）がメインのHTMLファイルに埋め込まれるか、別のバイナリエンティティとして生成されるかを制御できます。
type: docs
weight: 5710
url: /ja/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes 列挙型

この列挙型は、HTMLで参照されるファイルの埋め込みの可能なモードを列挙します。参照されたファイル（HTML、フォント、画像、CSS）がメインのHTMLファイルに埋め込まれるか、別のバイナリエンティティとして生成されるかを制御できます。

```csharp
public enum PartsEmbeddingModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | すべての参照ファイル（CSS、画像、フォント）を生成されたHTMLマークアップ（つまりHTML自体）に埋め込むことを強制します。このアプローチは1つのHTMLファイルを生成しますが、出力の合計サイズは大きくなります（バイナリのBase64エンコーディングが使用されるため）し、すべてのブラウザ（特にレガシーなもの）がHTMLに埋め込まれたバイナリを正常に処理できるわけではありません。しかし、追加のファイルなしで全体の結果を含むHTMLを取得できます。 |
| EmbedCssOnly | `1` | CSS（画像とフォント）を除くすべての参照ファイルを別にすることを強制します。つまり、CSSは結果のHTMLに埋め込まれ、他のすべての参照ファイル（画像とフォント）は外部部分として処理されます。これは、広範なブラウザセットに適したHTMLを生成します。 |
| NoEmbedding | `2` | 参照ファイル（CSS、画像、フォント）を別にすることを強制します。このアプローチはファイルのセットを生成しますが、出力の合計サイズは小さくなります（バイナリのBase64エンコーディングが使用されないため）。また、このアプローチは広範なブラウザセットに適したHTMLを生成します。 |

### 参照

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)