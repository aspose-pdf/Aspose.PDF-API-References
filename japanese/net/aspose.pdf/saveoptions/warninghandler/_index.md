---
title: "SaveOptions.WarningHandler"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "SaveOptions プロパティ。生成された警告を処理するコールバック。WarningHandler は ReturnAction 列挙体の項目を返し、Continue または Abort を指定します。Continue はデフォルトのアクションで、Save 操作は継続しますが、ユーザーが Abort を返すこともでき、その場合 Save 操作は停止すべきです。"
type: docs
weight: 40
url: /ja/net/aspose.pdf/saveoptions/warninghandler/
---
## SaveOptions.WarningHandler property

生成された警告を処理するコールバックです。WarningHandler は Continue または Abort を指定する ReturnAction 列挙体項目を返します。Continue はデフォルトの動作で、保存操作は続行されますが、ユーザーが Abort を返した場合は保存操作を中止する必要があります。

```csharp
public IWarningCallback WarningHandler { get; set; }
```

### 関連項目

* interface [IWarningCallback](../../iwarningcallback/)
* class [SaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


