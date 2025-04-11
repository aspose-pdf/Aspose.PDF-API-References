---
title: HtmlSaveOptions.SplitCssIntoPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions プロパティ。マルチページモードが選択されている場合（つまり、SplitIntoPages が true の場合）、この属性は各結果 HTML ページのために別々の CSS ファイルを作成する必要があるかどうかを定義します。デフォルトではこの属性は false であるため、作成されたすべてのページのために 1 つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS の合計サイズ（1 ページあたり 1 CSS）は、通常 1 つの大きな CSS ファイルのサイズよりもはるかに大きくなります。なぜなら、前者の場合、CSS クラスが重複しているため、各ページのために複数の CSS ファイルに存在するからです。したがって、この設定は、各 HTML ページを独立して将来的に処理することに興味がある場合にのみ使用するのが望ましく、そのため、各ページの CSS のサイズが最も重要な問題となります。
type: docs
weight: 190
url: /ja/net/aspose.pdf/htmlsaveoptions/splitcssintopages/
---
## HtmlSaveOptions.SplitCssIntoPages プロパティ

マルチページモードが選択されている場合（つまり、'SplitIntoPages' が 'true' の場合）、この属性は各結果 HTML ページのために別々の CSS ファイルを作成する必要があるかどうかを定義します。デフォルトではこの属性は false であるため、作成されたすべてのページのために 1 つの大きな共通 CSS が作成されます。このモードで生成されるすべての CSS の合計サイズ（1 ページあたり 1 CSS）は、通常 1 つの大きな CSS ファイルのサイズよりもはるかに大きくなります。なぜなら、前者の場合、CSS クラスが重複しているため、各ページのために複数の CSS ファイルに存在するからです。したがって、この設定は、各 HTML ページを独立して将来的に処理することに興味がある場合にのみ使用するのが望ましく、そのため、各ページの CSS のサイズが最も重要な問題となります。

```csharp
public bool SplitCssIntoPages { get; set; }
```

### 関連項目

* クラス [HtmlSaveOptions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)