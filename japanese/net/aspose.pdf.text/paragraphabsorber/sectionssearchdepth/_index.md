---
title: ParagraphAbsorber.SectionsSearchDepth
second_title: Aspose.PDF for .NET API Reference
description: ParagraphAbsorberプロパティ。構造のより細かい要素のために連続検索を何回行うかを指示する値を取得または設定します。デフォルトの検索深度は3です。これは、水平方向に分割されたセクション（ヘッダー、段落など）に対して3回の検索を行い、垂直方向に分割されたもの（列）に対しても3回の検索を行うことを意味します。
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepthプロパティ

構造のより細かい要素のために連続検索を何回行うかを指示する値を取得または設定します。デフォルトの検索深度は3です。これは、水平方向に分割されたセクション（ヘッダー、段落など）に対して3回の検索を行い、垂直方向に分割されたもの（列）に対しても3回の検索を行うことを意味します。

```csharp
public int SectionsSearchDepth { get; set; }
```

## 備考

この値を増加させると、検索結果に目に見える変化がないまま、パフォーマンスがわずかに低下する可能性があります。この値を減少させると、セクション内の段落の不正確な特定につながる可能性があります。ページ構造の「粗い」要素のみを取得したい場合を除き、デフォルト未満の値を設定することはお勧めしません。

### 関連項目

* クラス [ParagraphAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)