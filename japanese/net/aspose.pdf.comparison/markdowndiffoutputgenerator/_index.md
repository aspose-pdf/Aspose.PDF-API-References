---
title: "クラス MarkdownDiffOutputGenerator"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Comparison.MarkdownDiffOutputGenerator クラス。テキスト差分の Markdown 表現を生成するクラスを表します。Markdown 構文のため、空白文字の変更を表示することはできません。変更の選択により、フォーマットの周囲に空白文字を追加する必要があります。さもなければ Markdown ビューアはテキストを正しく表示できません。削除された改行は段落記号で示されます。"
type: docs
weight: 3360
url: /ja/net/aspose.pdf.comparison/markdowndiffoutputgenerator/
---
## MarkdownDiffOutputGenerator class

テキスト差分の Markdown 表現を生成するクラスを表します。Markdown の構文上、空白文字の変更を表示することはできません。変更の選択により、書式の前後に空白文字を追加します。そうしないと Markdown ビューアがテキストを正しく表示できません。削除された改行は - 段落記号で示されます。

```csharp
public class MarkdownDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [MarkdownDiffOutputGenerator](markdowndiffoutputgenerator/)() | デフォルトコンストラクタです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |
| [GenerateOutput](../../aspose.pdf.comparison/markdowndiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | テキスト間の差分に基づいて出力を生成し、ファイルに保存します。 |

### 関連項目

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


