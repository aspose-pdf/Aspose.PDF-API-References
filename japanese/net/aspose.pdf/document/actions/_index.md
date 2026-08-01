---
title: "Document.Actions"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document プロパティ。ドキュメントのアクションを取得します。このプロパティは DocumentActions クラスのインスタンスで、BeforClosing、BeforSaving などのアクションを取得/設定できます。"
type: docs
weight: 30
url: /ja/net/aspose.pdf/document/actions/
---
## Document.Actions property

Document のアクションを取得します。このプロパティは DocumentActions クラスのインスタンスで、BeforClosing、BeforSaving などのアクションを取得/設定できます。

```csharp
public DocumentActionCollection Actions { get; }
```

## 例

この例では、ドキュメントのオープン後アクションを取得する方法を示します。

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### 関連項目

* class [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


