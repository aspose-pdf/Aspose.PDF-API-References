---
title: "HtmlSaveOptions.ExplicitListOfSavedPages"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "HtmlSaveOptions プロパティ。このプロパティを使用すると、変換すべき文書のページを明示的に指定できます。このリスト内のページ番号は 1 から始まる必要があります。つまり、有効なページ番号は 1 から NumberOfPagesInConvertedDocument の範囲で取得しなければなりません。このリストにおけるページの出現順序は、結果の HTML ページの順序に影響しません。結果のページは常にソース PDF に存在する順序で表示されます。このリストが null（デフォルト）である場合、すべてのページが変換されます。このリストのページ番号が実際のページ数（amountOfPagesInDocument）を超えると例外がスローされます。"
type: docs
weight: 70
url: /ja/net/aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/
---
## HtmlSaveOptions.ExplicitListOfSavedPages property

このプロパティを使用すると、変換すべきドキュメントのページを明示的に指定できます。このリスト内のページは 1 から始まる番号でなければなりません。つまり、有効なページ番号は範囲 (1...[NumberOfPagesInConvertedDocument]) から取得する必要があります。このリストにおけるページの出現順序は、結果の HTML ページの順序に影響しません。結果のページは常にソース PDF に存在する順序で表示されます。このリストが null（デフォルト）の場合、すべてのページが変換されます。このリスト内のページ番号が実際のページ数の範囲 (1-[amountOfPagesInDocument]) を超えると例外がスローされます。

```csharp
public int[] ExplicitListOfSavedPages { get; set; }
```

### 関連項目

* class [HtmlSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


