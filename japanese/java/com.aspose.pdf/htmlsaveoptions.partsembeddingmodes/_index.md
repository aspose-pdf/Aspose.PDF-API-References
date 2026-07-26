---
title: "HtmlSaveOptions.PartsEmbeddingModes"
linktitle: "HtmlSaveOptions.PartsEmbeddingModes"
second_title: "Java 用 Aspose.PDF API リファレンス"
description: "この列挙型は HTML で参照されるファイルの埋め込みモードを列挙します。参照されたファイル (HTML、フォント、画像、CSS) をメインに埋め込むかどうかを制御できます。"
type: docs
weight: 2130
url: /ja/java/com.aspose.pdf/htmlsaveoptions.partsembeddingmodes/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes, com.aspose.ms.System.Enum, com.aspose.pdf.HtmlSaveOptions.PartsEmbeddingModes

```
public static final class HtmlSaveOptions.PartsEmbeddingModes extends com.aspose.ms.System.Enum
```

この列挙体はHTMLで参照されるファイルの埋め込みモードの可能な種類を列挙します。これにより、参照されたファイル（HTML、フォント、画像、CSS）がメインHTMLファイルに埋め込まれるか、別個のバイナリエンティティとして生成されるかを制御できます

## フィールド

| フィールド | 説明 |
| --- | --- |
| [EmbedAllIntoHtml](#EmbedAllIntoHtml) | すべての参照ファイル（Css、Images、Fonts）を生成された HTML マークアップ（つまり HTML 自体）に埋め込むことを強制します。このアプローチは 1 つの HTML ファイルを生成しますが、出力の総サイズは大きくなります（バイナリの Base64 エンコードが使用されるため）し、すべてのブラウザ（特にレガシー）は HTML に埋め込まれたバイナリを正常に処理できるわけではありません。ただし、追加ファイルなしで全体の結果を含む HTML を取得できます。 |
| [EmbedCssOnly](#EmbedCssOnly) | CSS を除くすべての参照ファイル（Images と Fonts）を分離することを強制します。つまり、CSS は結果の HTML に埋め込まれ、他の参照ファイル（Images と Fonts）は外部パーツとして処理されます。この方式は幅広いブラウザで適用可能な HTML を生成します。 |
| [NoEmbedding](#NoEmbedding) | 参照ファイル（Css、Images、Fonts）を分離することを強制します。このアプローチは複数のファイルを生成しますが、出力の総サイズは小さくなります（バイナリの Base64 エンコードが使用されないため）。また、この方式は幅広いブラウザで適用可能な HTML を生成します。 |

### EmbedAllIntoHtml {#EmbedAllIntoHtml}
```
public static final int EmbedAllIntoHtml
```

すべての参照ファイル（Css、Images、Fonts）を生成された HTML マークアップ（つまり HTML 自体）に埋め込むことを強制します。このアプローチは 1 つの HTML ファイルを生成しますが、出力の総サイズは大きくなります（バイナリの Base64 エンコードが使用されるため）し、すべてのブラウザ（特にレガシー）は HTML に埋め込まれたバイナリを正常に処理できるわけではありません。ただし、追加ファイルなしで全体の結果を含む HTML を取得できます。

### EmbedCssOnly {#EmbedCssOnly}
```
public static final int EmbedCssOnly
```

CSS を除くすべての参照ファイル（Images と Fonts）を分離することを強制します。つまり、CSS は結果の HTML に埋め込まれ、他の参照ファイル（Images と Fonts）は外部パーツとして処理されます。この方式は幅広いブラウザで適用可能な HTML を生成します。

### NoEmbedding {#NoEmbedding}
```
public static final int NoEmbedding
```

参照ファイル（Css、Images、Fonts）を分離することを強制します。このアプローチは複数のファイルを生成しますが、出力の総サイズは小さくなります（バイナリの Base64 エンコードが使用されないため）。また、この方式は幅広いブラウザで適用可能な HTML を生成します。
