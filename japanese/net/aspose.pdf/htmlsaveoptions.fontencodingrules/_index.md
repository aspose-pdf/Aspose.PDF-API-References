---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.HtmlSaveOptionsFontEncodingRules 列挙型。この列挙型はエンコーディングロジックを調整するルールを定義します
type: docs
weight: 5620
url: /ja/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules 列挙型

この列挙型はエンコーディングロジックを調整するルールを定義します

```csharp
public enum FontEncodingRules : byte
```

### 値

| 名前 | 値 | 説明 |
| --- | --- | --- |
| Default | `0` | エンコーディングロジックを「そのまま」に保つ - PDF 仕様に従って |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode は入力コードをユニコード記号にデコードするのを助ける特別なメカニズムです。仕様によれば、特定の入力コードに対してユニコード記号を取得するための最初のメカニズムとして使用されなければなりません。しかし、一部の文書には非標準フォントがあり、これらの文書を正しく変換するためには、ToUnicode の優先度を下げて、他のメカニズムを使用して入力コードをデコードする必要があるかもしれません。 |

### 参照

* クラス [HtmlSaveOptions](../htmlsaveoptions/)
* 名前空間 [Aspose.Pdf](../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../)