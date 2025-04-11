---
title: HtmlLoadOptions.CustomLoaderOfExternalResources
second_title: Aspose.PDF for .NET API Reference
description: HtmlLoadOptions 字段。有时需要避免使用内部加载器加载外部资源（如图像或 CSS），并提供自定义方法从某处获取请求的资源。例如，在云中使用 Aspose.PDF 时，无法直接访问引用的文件：在这种情况下，应使用放入特殊方法中的一些自定义代码，并将引用该方法的委托分配给此属性。
type: docs
weight: 100
url: /zh/net/aspose.pdf/htmlloadoptions/customloaderofexternalresources/
---
## HtmlLoadOptions.CustomLoaderOfExternalResources 字段

有时需要避免使用内部加载器加载外部资源（如图像或 CSS），并提供自定义方法从某处获取请求的资源。例如，在云中使用 Aspose.PDF 时，无法直接访问引用的文件：在这种情况下，应使用放入特殊方法中的一些自定义代码，并将引用该方法的委托分配给此属性。

```csharp
public ResourceLoadingStrategy CustomLoaderOfExternalResources;
```

### 另请参阅

* delegate [ResourceLoadingStrategy](../../loadoptions.resourceloadingstrategy/)
* class [HtmlLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)