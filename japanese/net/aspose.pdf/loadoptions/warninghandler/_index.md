---
title: LoadOptions.WarningHandler
second_title: Aspose.PDF for .NET API Reference
description: LoadOptions プロパティ。生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型の項目を返します。Continue はデフォルトのアクションであり、Load 操作は続行されますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止する必要があります。
type: docs
weight: 30
url: /ja/net/aspose.pdf/loadoptions/warninghandler/
---
## LoadOptions.WarningHandler プロパティ

生成された警告を処理するためのコールバック。WarningHandler は、Continue または Abort のいずれかを指定する ReturnAction 列挙型の項目を返します。Continue はデフォルトのアクションであり、Load 操作は続行されますが、ユーザーは Abort を返すこともでき、その場合 Load 操作は停止する必要があります。

```csharp
public IWarningCallback WarningHandler { get; set; }
```

### 参照

* interface [IWarningCallback](../../iwarningcallback/)
* class [LoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)