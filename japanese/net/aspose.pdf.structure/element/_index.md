---
title: "クラス Element"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Aspose.Pdf.Structure.Element クラス。論理構造の基本要素を表すクラス"
type: docs
weight: 10320
url: /ja/net/aspose.pdf.structure/element/
---
## Element class

論理構造の基本要素を表すクラスです。

```csharp
public abstract class Element
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | (オプション; PDF 1.4) 構造要素とその子要素の正確な置き換えとなるテキスト。この置き換えテキストは（可能な限り小さなコンテンツ単位に適用すべき）文書の内容を抽出し、障害を持つユーザーへのアクセシビリティ支援やその他の目的に役立ちます。 |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | (オプション) 構造要素とその子要素の代替説明（人が読める形式）。この説明は文書の内容を抽出し、障害を持つユーザーへのアクセシビリティ支援やその他の目的に役立ちます。 |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | 子要素コレクションを取得します。 |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | (オプション; PDF 1.5) 略語の展開形です。 |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | (オプション; PDF 1.4) 構造要素内のすべてのテキストに対する自然言語を指定する言語。ただし、入れ子構造要素やマーク付きコンテンツの言語指定で上書きされる場合を除きます。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | 要素を削除します。 |

### 関連項目

* namespace [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* assembly [Aspose.PDF](../../)


