---
title: TextAbsorber.Text
second_title: Aspose.PDF for .NET API Reference
description: TextAbsorber プロパティ。PDF ドキュメントまたはページから TextAbsorber が抽出したテキストを取得します。
type: docs
weight: 50
url: /ja/net/aspose.pdf.text/textabsorber/text/
---
## TextAbsorber.Text プロパティ

[`TextAbsorber`](../) が PDF ドキュメントまたはページから抽出したテキストを取得します。

```csharp
public virtual string Text { get; }
```

## 例

この例では、PDF ドキュメントのすべてのページからテキストを抽出する方法を示します。

```csharp
// open document
Document doc = new Document(inFile);

// create TextAbsorber object to extract text
TextAbsorber absorber = new TextAbsorber();

// accept the absorber for all document's pages
doc.Pages.Accept(absorber);

// get the extracted text
string extractedText = absorber.Text;

```

### 関連項目

* クラス [TextAbsorber](../)
* 名前空間 [Aspose.Pdf.Text](../../../aspose.pdf.text/)
* アセンブリ [Aspose.PDF](../../../)