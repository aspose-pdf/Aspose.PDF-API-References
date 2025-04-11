---
title: Class MarkdownDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator クラス。テキストの違いのマークダウン表現を生成するためのクラスを表します。マークダウン構文のため、空白文字の変更を表示することはできません。変更の選択により、フォーマットの周りに空白文字を追加することができ、さもなければマークダウンビューアはテキストを正しく表示しません。削除された改行は段落マークで示されます。
type: docs
weight: 3250
url: /ja/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator クラス

テキストの違いのマークダウン表現を生成するためのクラスを表します。マークダウン構文のため、空白文字の変更を表示することはできません。変更の選択により、フォーマットの周りに空白文字を追加することができ、さもなければマークダウンビューアはテキストを正しく表示しません。削除された改行は - 段落マークで示されます。

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | デフォルトのコンストラクタ。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |

### 参照

* インターフェース [IFileOutputGenerator](../ifileoutputgenerator/)
* インターフェース [IStringOutputGenerator](../istringoutputgenerator/)
* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)