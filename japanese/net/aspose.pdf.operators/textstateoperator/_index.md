---
title: Class TextStateOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextStateOperator クラス。現在のテキスト状態を変更するオペレーターの抽象基本クラス (Tc, Tf, TL など)。
type: docs
weight: 7930
url: /ja/net/aspose.pdf.operators/textstateoperator/
---
## TextStateOperator クラス

現在のテキスト状態 (Tc, Tf, TL など) を変更するオペレーターの抽象基本クラスです。

```csharp
public class TextStateOperator : TextOperator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextStateOperator](textstateoperator/#constructor)() | TextStateOperator を初期化します。 |
| [TextStateOperator](textstateoperator/#constructor_1)(TextProperties) | TextProperties を渡すことを可能にする TextStateOperator を初期化します。 |

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