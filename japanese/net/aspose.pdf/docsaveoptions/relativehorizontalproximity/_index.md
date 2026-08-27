---
title: "DocSaveOptions.RelativeHorizontalProximity"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "DocSaveOptions プロパティ。Pdf では、単語が文字や音節を個別に印刷する演算子で内部的に表現されることがあります。そのため、単語を検出するには、実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース Pdf の単語認識時に、テキスト要素（文字・音節）間の空白幅を単語間の距離として扱う幅を定義します。文字間にこの幅以上の空白が存在すると、そのテキスト要素は別々の単語に属するとみなされます。フォントサイズを基準に正規化され、1.0 はフォントサイズの 100% を意味します。注意：このパラメータは、フォントから最適値を算出できない、特定の希少フォントが含まれるソース Pdf の場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。"
type: docs
weight: 120
url: /ja/net/aspose.pdf/docsaveoptions/relativehorizontalproximity/
---
## DocSaveOptions.RelativeHorizontalProximity property

Pdf では、単語が文字や音節を個別に印刷する演算子で内部的に表現されることがあります。そのため、単語を検出する際には、実際には単語である独立した文字のグループを検出する必要があります。この設定は、ソース PDF の単語認識時に、テキスト要素（文字、音節）間の空白幅を単語間の距離として扱うべき幅を定義します。（文字間にこの幅以上の空白が存在する場合、そのテキスト要素は別々の単語に属するとみなされます）。フォントサイズに正規化されており、1.0 は想定される単語のフォントサイズの 100% を意味します。ATTENTION! この設定は、フォントから最適値を算出できない、非常に稀に使用されるフォントがソース PDF に含まれる場合にのみ使用されます。したがって、ほとんどの場合、このパラメータは結果文書に影響を与えません。

```csharp
public float RelativeHorizontalProximity { get; set; }
```

### 関連項目

* class [DocSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


