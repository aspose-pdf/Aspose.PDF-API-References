---
title: "LoadOptions.WarningHandler"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "LoadOptions プロパティ。生成された警告を処理するコールバック。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体の項目を返します。Continue はデフォルトのアクションで、ロード操作は続行されますが、ユーザーが Abort を返した場合はロード操作を停止すべきです。"
type: docs
weight: 30
url: /ja/net/aspose.pdf/loadoptions/warninghandler/
---
## LoadOptions.WarningHandler property

生成された警告を処理するコールバックです。WarningHandler は ReturnAction 列挙型の項目を返し、Continue または Abort を指定します。Continue はデフォルトの動作で、Load 操作は継続しますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は中止されます。

```csharp
public IWarningCallback WarningHandler { get; set; }
```

### 関連項目

* interface [IWarningCallback](../../iwarningcallback/)
* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


