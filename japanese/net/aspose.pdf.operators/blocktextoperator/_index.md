---
title: Class BlockTextOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.BlockTextOperator クラス。テキストブロックオペレーターの抽象基底クラス、つまり開始および終了テキストオペレーター BT/ET
type: docs
weight: 7170
url: /ja/net/aspose.pdf.operators/blocktextoperator/
---
## BlockTextOperator クラス

テキストブロックオペレーターの抽象基底クラス、つまり開始および終了テキストオペレーター (BT/ET)

```csharp
public class BlockTextOperator : TextOperator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [BlockTextOperator](blocktextoperator/#constructor)() | オペレーターを初期化します。 |
| [BlockTextOperator](blocktextoperator/#constructor_1)(TextProperties) | TextProperties を受け入れる BlockTextOperator を初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックス。 |

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