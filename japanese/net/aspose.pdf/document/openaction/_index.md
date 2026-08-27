---
title: "Document.OpenAction"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Document プロパティ。ドキュメントを開く際に実行されるアクションを取得または設定します"
type: docs
weight: 410
url: /ja/net/aspose.pdf/document/openaction/
---
## Document.OpenAction property

document のオープン時に実行されるアクションを取得または設定します。

```csharp
public IAppointment OpenAction { get; set; }
```

## 例

例では CenterWindow フラグの取得方法を示します：

```csharp
Document document = new Document("sample.pdf");
IAppointment value = document.OpenAction;
```

### 関連項目

* interface [IAppointment](../../../aspose.pdf.annotations/iappointment/)
* class [Document](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


