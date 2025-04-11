---
title: Class Operator
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Operator クラス。オペレーターを表す抽象クラス
type: docs
weight: 7070
url: /ja/net/aspose.pdf/operator/
---
## オペレーター クラス

オペレーターを表す抽象クラス。

```csharp
public abstract class Operator
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Index](../../aspose.pdf/operator/index/) { get; set; } | ページオペレーターリスト内のオペレーターインデックス。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| abstract [Accept](../../aspose.pdf/operator/accept/)(IOperatorSelector) | オペレーター処理を提供する訪問者 IOperatorSelector を受け入れます。 |
| override [ToString](../../aspose.pdf/operator/tostring/)() | オペレーターとそのパラメーターのテキストを返します。 |
| [ValueEquals](../../aspose.pdf/operator/valueequals/)(Operator) | このインスタンスを指定されたオブジェクトと比較します。 |
| static [IsTextShowOperator](../../aspose.pdf/operator/istextshowoperator/)(Operator) | オペレーターがテキスト出力（Tj、TJ など）を担当するオペレーターであるかどうかを判断します。 |

### 参照

* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)