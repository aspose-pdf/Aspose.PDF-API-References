---
title: Font.IsAccessible
second_title: Aspose.PDF for .NET API Reference
description: フォントプロパティ。フォントがシステムにインストールされているかどうかを示します
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/font/isaccessible/
---
## Font.IsAccessible プロパティ

フォントがシステムに存在する（インストールされている）かどうかを示します。

```csharp
public bool IsAccessible { get; }
```

## 備考

システムで見つからないフォントでは、一部の操作が利用できません。

## 例

この例では、最初のページでテキストを検索し、フォントがシステムにインストールされているかどうかを示す値を取得する方法を示します。

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// View font's IsSubset value of first text occurrence
if(absorber.TextFragments[1].TextState.Font.IsAccessible)
   Console.Out.WriteLine("the font is installed in the system");
```

### 関連項目

* クラス [TextFragmentAbsorber](../../textfragmentabsorber/)
* クラス [Document](../../../aspose.pdf/document/)
* クラス [Font](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)