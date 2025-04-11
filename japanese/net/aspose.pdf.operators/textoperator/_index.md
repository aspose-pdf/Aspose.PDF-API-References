---
title: Class TextOperator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operators.TextOperator クラス。テキスト関連のオペレーター TJ Tj Tm BT ET などの抽象基底クラス
type: docs
weight: 7900
url: /ja/net/aspose.pdf.operators/textoperator/
---
## TextOperator クラス

テキスト関連のオペレーター (TJ, Tj, Tm, BT, ET など) の抽象基底クラスです。

```csharp
public abstract class TextOperator : Operator
```

## コンストラクター

| 名前 | 説明 |
| --- | --- |
| [TextOperator](textoperator/#constructor)() | オペレーターを初期化します。 |
| [TextOperator](textoperator/#constructor_1)(TextProperties) | テキストプロパティを受け入れるテキストオペレーターです。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックスです。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| override [Accept](../../aspose.pdf.operators/textoperator/accept/)(IOperatorSelector) | オペレーターを処理するためのビジターオブジェクトを受け入れます。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | オペレーターとそのパラメーターのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |

### 参照

* クラス [Operator](../../aspose.pdf/operator/)
* 名前空間 [Aspose.Pdf.Operators](../../aspose.pdf.operators/)
* アセンブリ [Aspose.PDF](../../)