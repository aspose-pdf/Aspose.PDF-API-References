---
title: Class TextShowOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextShowOperator クラス。テキストを出力するためのすべてのオペレーターの抽象基本クラス (Tj, TJ など)。
type: docs
weight: 7920
url: /ja/net/aspose.pdf.operators/textshowoperator/
---
## TextShowOperator クラス

テキストを出力するためのすべてのオペレーターの抽象基本クラス (Tj, TJ など)。

```csharp
public class TextShowOperator : TextOperator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextShowOperator](textshowoperator/#constructor)() | TextShowOperator を初期化します。 |
| [TextShowOperator](textshowoperator/#constructor_1)(TextProperties) | TextProperties を渡すことを許可する TextShowOperator を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックス。 |
| virtual [Text](../../aspose.pdf.operators/textshowoperator/text/) { get; set; } | オペレーターがページに出力するテキストを取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | オペレーターを処理するためにビジターオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | オペレーターとそのパラメーターのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [TextOperator](../textoperator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)