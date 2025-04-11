---
title: Document.Actions
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントプロパティ。ドキュメントアクションを取得します。このプロパティは DocumentActions クラスのインスタンスであり、BeforClosing、BeforSaving などのアクションを取得/設定することができます。
type: docs
weight: 30
url: /ja/net/aspose.pdf/document/actions/
---
## Document.Actions プロパティ

ドキュメントアクションを取得します。このプロパティは DocumentActions クラスのインスタンスであり、BeforClosing、BeforSaving などのアクションを取得/設定することができます。

```csharp
public DocumentActionCollection Actions { get; }
```

## 例

この例では、ドキュメントのオープン後のアクションを取得する方法を示します。

```csharp
Aspose.Pdf.Document document = new Aspose.Pdf.Document("d:\\work\\aspose\\aspose.pdf.kit.net.new\\trunk\\testdata\\Aspose.Pdf\\PdfWithOpenAction.pdf");
Aspose.Pdf.Annotations.DocumentActionCollection actions = document.Actions;
Aspose.Pdf.Annotations.PdfAction afterSavingAction = actions.AfterSaving;
```

### 関連項目

* クラス [DocumentActionCollection](../../../aspose.pdf.annotations/documentactioncollection/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)