---
title: Delegate LoadOptions.ResourceLoadingStrategy
second_title: Aspose.PDF for .NET API Reference
description: 有时需要避免使用内部加载器加载外部资源（如图像或CSS），并提供自定义方法来从某处获取请求的资源。例如，在云中使用Aspose.Pdf时，无法直接访问引用的文件，因此应该使用放入特殊方法中的一些自定义代码。此委托定义了此类自定义方法的签名。
type: docs
weight: 6160
url: /zh/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

有时需要避免使用内部加载器加载外部资源（如图像或CSS），并提供自定义方法来从某处获取请求的资源。例如，在云中使用Aspose.Pdf时，无法直接访问引用的文件，因此应该使用放入特殊方法中的一些自定义代码。此委托定义了此类自定义方法的签名。

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceURI | String | 资源URI。 |

### 返回值

ResourceLoadingResult对象。

### 另请参见

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)