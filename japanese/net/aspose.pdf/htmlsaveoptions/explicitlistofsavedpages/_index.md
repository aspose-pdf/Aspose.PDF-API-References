---
title: HtmlSaveOptions.ExplicitListOfSavedPages
second_title: Aspose.PDF for .NET API Reference
description: HtmlSaveOptions プロパティ。このプロパティを使用すると、どのページのドキュメントを変換するかを明示的に定義できます。このリストのページは 1 ベースの番号でなければなりません。つまり、有効なページ番号は範囲 1...NumberOfPagesInConvertedDocument から取得する必要があります。このリストにおけるページの出現順序は、結果の HTML ページにおける順序に影響を与えません。結果のページは、常にソース PDF に存在する順序で表示されます。このリストが null の場合（デフォルトではそうです）、すべてのページが変換されます。このリストのページ番号が現在のページの範囲 （1-[amountOfPagesInDocument]） を超えると、例外がスローされます。
type: docs
weight: 70
url: /ja/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages プロパティ

このプロパティを使用すると、どのページのドキュメントを変換するかを明示的に定義できます。このリストのページは 1 ベースの番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果の HTML ページにおける順序に影響を与えません - 結果のページは常にソース PDF に存在する順序で表示されます。このリストが null の場合（デフォルトではそうです）、すべてのページが変換されます。このリストのページ番号が現在のページの範囲 (1-[amountOfPagesInDocument]) を超えると、例外がスローされます。

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### 関連項目

* クラス [HtmlSaveOptions](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)