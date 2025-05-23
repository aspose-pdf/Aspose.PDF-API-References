---
title: Class TextElement
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Structure.TextElement クラス。文書の論理構造の一般的なテキスト要素
type: docs
weight: 10190
url: /ja/net/aspose.pdf.structure/textelement/
---
## TextElement クラス

文書の論理構造の一般的なテキスト要素です。

```csharp
public class TextElement : Element
```

## プロパティ

| 名前 | 説明 |
| --- | --- |
| virtual [ActualText](../../aspose.pdf.structure/element/actualtext/) { get; set; } | （オプション; PDF 1.4）構造要素とその子要素の正確な置き換えとなるテキスト。この置き換えテキスト（できるだけ小さなコンテンツに適用されるべき）は、障害のあるユーザーのアクセシビリティをサポートするためやその他の目的で文書の内容を抽出する際に便利です。 |
| virtual [Alt](../../aspose.pdf.structure/element/alt/) { get; set; } | （オプション）構造要素とその子要素の人間が読みやすい形式の代替説明で、障害のあるユーザーのアクセシビリティをサポートするためやその他の目的で文書の内容を抽出する際に便利です。 |
| [Children](../../aspose.pdf.structure/element/children/) { get; } | 子要素コレクションを取得します。 |
| virtual [E](../../aspose.pdf.structure/element/e/) { get; set; } | （オプション; PDF 1.5）略語の展開形。 |
| virtual [Lang](../../aspose.pdf.structure/element/lang/) { get; set; } | （オプション; PDF 1.4）構造要素内のすべてのテキストの自然言語を指定する言語で、ネストされた構造要素やマークされたコンテンツの言語仕様によって上書きされない限り適用されます。 |
| [Text](../../aspose.pdf.structure/textelement/text/) { get; } | テキスト構造要素の値を取得します。 |

## メソッド

| 名前 | 説明 |
| --- | --- |
| [Remove](../../aspose.pdf.structure/element/remove/)() | 要素を削除します。 |

### 参照

* クラス [Element](../element/)
* 名前空間 [Aspose.Pdf.Structure](../../aspose.pdf.structure/)
* アセンブリ [Aspose.PDF](../../)