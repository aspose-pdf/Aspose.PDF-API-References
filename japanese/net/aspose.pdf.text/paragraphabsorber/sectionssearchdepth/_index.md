---
title: "ParagraphAbsorber.SectionsSearchDepth"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "ParagraphAbsorber プロパティ。構造のより細かい要素に対する連続検索の回数を指示する値を取得または設定します。デフォルトの検索深度は 3 です。これは、水平に分割されたセクション、ヘッダー、段落などに対して 3 回の検索を行い、垂直に分割された列に対しても 3 回の検索を行うことを意味します。"
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/paragraphabsorber/sectionssearchdepth/
---
## ParagraphAbsorber.SectionsSearchDepth property

構造のより細かい要素に対する連続検索を実行する回数を指示する値を取得または設定します。既定の検索深度は 3 です。これは、水平に分割されたセクション（ヘッダー、段落など）に対して 3 回の検索を行い、垂直に分割されたセクション（列）に対しても 3 回の検索を行うことを意味します。

```csharp
public int SectionsSearchDepth { get; set; }
```

## 備考

この値を増加させると、検索結果に目に見える変化がなく、パフォーマンスがわずかに低下する可能性があります。この値を減少させると、セクション内の段落の判定が正しく行われなくなる可能性があります。ページ構造の「大まかな」要素だけを取得したい場合を除き、デフォルトより小さい値に設定することは推奨しません。

### 関連項目

* class [ParagraphAbsorber](../)
* namespace [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../../)


