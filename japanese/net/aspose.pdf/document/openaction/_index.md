---
title: Document.OpenAction
second_title: Aspose.PDF for .NET API Reference
description: ドキュメントプロパティ。ドキュメントを開くときに実行されるアクションを取得または設定します
type: docs
weight: 390
url: /ja/net/aspose.pdf/document/openaction/
---
## Document.OpenAction プロパティ

ドキュメントを開くときに実行されるアクションを取得または設定します。

```csharp
public IAppointment OpenAction { get; set; }
```

## 例

例は、CenterWindow フラグを取得する方法を示しています。

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### 関連項目

* インターフェース [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* クラス [Document](../)
* 名前空間 [Aspose.Pdf](../../../aspose.pdf/)
* アセンブリ [Aspose.PDF](../../../)