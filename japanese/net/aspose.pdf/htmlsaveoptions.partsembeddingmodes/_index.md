---
title: "列挙型 HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.HtmlSaveOptionsPartsEmbeddingModes 列挙型。この列挙型は、HTML で参照されるファイルの埋め込みモードの可能性を列挙します。参照されたファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを制御できます。"
type: docs
weight: 5840
url: /ja/net/aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
## HtmlSaveOptions.PartsEmbeddingModes enumeration

この列挙型は、HTML で参照されるファイルの埋め込みモードの可能性を列挙します。参照されたファイル（HTML、フォント、画像、CSS）がメインの HTML ファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを制御できます。

```csharp
public enum PartsEmbeddingModes
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| EmbedAllIntoHtml | `0` | すべての参照ファイル（CSS、画像、フォント）を生成された HTML マークアップ（つまり HTML 自体）に埋め込むことを強制します。このアプローチは 1 つの HTML ファイルを生成しますが、出力の総サイズは大きくなります（バイナリが Base64 エンコードされるため）し、すべてのブラウザ（特にレガシー）は HTML に埋め込まれたバイナリを正常に処理できるわけではありません。ただし、追加ファイルなしで全体の結果を含む HTML を取得できます。 |
| EmbedCssOnly | `1` | CSS を除くすべての参照ファイル（画像とフォント）を別個に配置することを強制します。つまり、CSS は結果の HTML に埋め込まれ、他の参照ファイル（画像とフォント）は外部パーツとして処理されます。この方式は、幅広いブラウザに適した HTML を生成します。 |
| NoEmbedding | `2` | 参照ファイル（CSS、画像、フォント）を別個に配置することを強制します。このアプローチは複数のファイルを生成しますが、出力の総サイズは小さくなります（バイナリの Base64 エンコードを使用しないため）。また、この方式は幅広いブラウザに適した HTML を生成します。 |

### 関連項目

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


