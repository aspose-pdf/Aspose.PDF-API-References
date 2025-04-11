---
title: Class BoundsCheckableListT
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Generator.BoundsCheckableList1T クラス。System.Collections.Generic.List のラッパーである BoundsCheckableList を表します。
type: docs
weight: 5340
url: /ja/net/aspose.pdf.generator/boundscheckablelist-1/
---
## BoundsCheckableList&lt;T&gt; クラス

BoundsCheckableList - System.Collections.Generic.List のラッパーを表します。

```csharp
public class BoundsCheckableList<T> : IList<T>
    where T : IBoundsCheckableItem
```

## コンストラクタ

| 名前 | 説明 |
| --- | --- |
| [BoundsCheckableList](boundscheckablelist/#constructor)() | BoundsCheckableList クラスの新しいインスタンスを初期化します。 |
| [BoundsCheckableList](boundscheckablelist/#constructor_1)(BoundsCheckMode, double, double) | BoundsCheckableList クラスの新しいインスタンスを初期化します。 |

## プロパティ

| 名前 | 説明 |
| --- | --- |
| [Count](../../aspose.pdf.generator/boundscheckablelist-1/count/) { get; } | System.Collections.Generic.List に含まれる要素の数を取得します。 |
| [IsReadOnly](../../aspose.pdf.generator/boundscheckablelist-1/isreadonly/) { get; } | コレクションが読み取り専用であるかどうかを示す値を取得します。 |
| [Item](../../aspose.pdf.generator/boundscheckablelist-1/item/) { get; set; } | コレクションからまたはコレクションに段落を取得または設定します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Add](../../aspose.pdf.generator/boundscheckablelist-1/add/)(T) | "boundsCheckMode" パラメータに応じて、System.Collections.Generic.List の末尾にオブジェクトを追加します。 |
| [Clear](../../aspose.pdf.generator/boundscheckablelist-1/clear/)() | System.Collections.Generic.List からすべての要素を削除します。 |
| [Contains](../../aspose.pdf.generator/boundscheckablelist-1/contains/)(T) | 要素が System.Collections.Generic.List に含まれているかどうかを判断します。 |
| [CopyTo](../../aspose.pdf.generator/boundscheckablelist-1/copyto/)(T[], int) |  |
| [GetEnumerator](../../aspose.pdf.generator/boundscheckablelist-1/getenumerator/)() | System.Collections.Generic.List を反復処理する列挙子を返します。 |
| [IndexOf](../../aspose.pdf.generator/boundscheckablelist-1/indexof/)(T) | 指定されたオブジェクトを検索し、System.Collections.Generic.List 内の最初の出現のゼロベースのインデックスを返します。 |
| [Insert](../../aspose.pdf.generator/boundscheckablelist-1/insert/)(int, T) | 指定されたインデックスで System.Collections.Generic.List に要素を挿入します。 |
| [Remove](../../aspose.pdf.generator/boundscheckablelist-1/remove/)(T) | System.Collections.Generic.List から特定のオブジェクトの最初の出現を削除します。 |
| [RemoveAt](../../aspose.pdf.generator/boundscheckablelist-1/removeat/)(int) | System.Collections.Generic.List の指定されたインデックスの要素を削除します。 |
| [UpdateBoundsCheckMode](../../aspose.pdf.generator/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode)(BoundsCheckMode) | 初期化されたコレクションの boundsCheckMode パラメータを更新します。 |
| [UpdateBoundsCheckMode](../../aspose.pdf.generator/boundscheckablelist-1/updateboundscheckmode/#updateboundscheckmode_1)(BoundsCheckMode, double, double) | 初期化されたコレクションの boundsCheckMode パラメータを更新します。 |

### 参照

* インターフェース [IBoundsCheckableItem](../iboundscheckableitem/)
* 名前空間 [Aspose.Pdf.Generator](../../aspose.pdf.generator/)
* アセンブリ [Aspose.PDF](../../)