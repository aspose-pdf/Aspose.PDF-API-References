---
title: "クラス TextShowOperator"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Operators.TextShowOperator クラス。テキスト Tj TJ などを出力するために使用されるすべての演算子の抽象基底クラス。"
type: docs
weight: 8060
url: /ja/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator class

テキストを出力するために使用されるすべての演算子（Tj、TJ など）用の抽象基底クラスです。

```csharp
public class TextShowOperator : TextOperator
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | TextShowOperator を初期化します。 |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | TextProperties を渡すことができる TextShowOperator を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | Page operators list の演算子インデックス。 |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | ページ上で演算子が出力するテキストを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | 演算子を処理するためのビジタオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | 演算子とそのパラメータのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 関連項目

* class [TextOperator](../textoperator/)
* namespace [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* assembly [Aspose.PDF](../../)


