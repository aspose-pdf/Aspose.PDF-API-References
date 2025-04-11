---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Comparison.HtmlDiffOutputGenerator クラス。テキストの違いの HTML 表現を生成するためのクラスを表します。削除された改行は段落マークで示されます。
type: docs
weight: 3200
url: /ja/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator クラス

テキストの違いの HTML 表現を生成するためのクラスを表します。削除された改行は段落マークで示されます。

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | `HtmlDiffOutputGenerator` クラスのインスタンスを作成します。 |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | `HtmlDiffOutputGenerator` クラスのインスタンスを作成します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | 削除操作のための CSS スタイル文字列を取得および設定します。例: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | 等しい操作のための CSS スタイル文字列を取得および設定します。例: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | 挿入操作のための CSS スタイル文字列を取得および設定します。例: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | 削除操作のための text-decoration: line-through スタイルを取得または設定します。デフォルト値は `False` です。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | テキスト間の違いに基づいて出力を生成し、ファイルに保存します。 |

### 参照

* インターフェース [IFileOutputGenerator](../ifileoutputgenerator/)
* インターフェース [IStringOutputGenerator](../istringoutputgenerator/)
* 名前空間 [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* アセンブリ [Aspose.PDF](../../)