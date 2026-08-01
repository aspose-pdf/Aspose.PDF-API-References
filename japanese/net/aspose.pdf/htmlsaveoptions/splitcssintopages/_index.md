---
title: "HtmlSaveOptions.SplitCssIntoPages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "HtmlSaveOptions プロパティ。マルチページモード（すなわち SplitIntoPages が true）の場合、この属性は各結果 HTML ページごとに個別の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して 1 つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS の総サイズは、ページごとに 1 つの CSS を作成する場合、通常は 1 つの大きな CSS ファイルのサイズよりもはるかに大きくなります。なぜなら前者では CSS クラスが重複し、各ページごとに複数の CSS ファイルに同じクラスが含まれるためです。したがって、この設定は各 HTML ページを個別に処理したい場合、つまり各ページの CSS サイズが最も重要な課題となる場合にのみ使用すべきです。"
type: docs
weight: 190
url: /ja/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages property

マルチページモードが選択されている場合（つまり 'SplitIntoPages' が true の場合）、この属性は各結果 HTML ページごとに個別の CSS ファイルを作成するかどうかを定義します。デフォルトではこの属性は false で、すべてのページに対して 1 つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS（ページごとに 1 つの CSS）の総サイズは、通常、1 つの大きな CSS ファイルのサイズよりもはるかに大きくなります。なぜなら、前者の場合、CSS クラスが各ページの複数の CSS ファイルに重複して存在するためです。そのため、この設定は、各 HTML ページを個別に処理したい場合にのみ使用すべきであり、各ページごとの CSS サイズが最も重要な課題となります。

```csharp
public bool SplitCssIntoPages { get; set; }
```

### 関連項目

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


