---
title: "委托 LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF for .NET API 参考"
description: "有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法从某处获取请求的资源。例如，在云环境中使用 Aspose.Pdf 时，无法直接访问引用的文件，需要将一些自定义代码放入专用方法中。此委托定义了此类自定义方法的签名。"
type: docs
weight: 6300
url: /zh/net/aspose.pdf/loadoptions.resourceloadingstrategy/
---
## LoadOptions.ResourceLoadingStrategy delegate

有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法以从某处获取请求的资源。例如，在云环境中使用 Aspose.Pdf 时，无法直接访问引用的文件，需要将一些自定义代码放入专用方法中。此委托定义了此类自定义方法的签名。

```csharp
public delegate ResourceLoadingResult ResourceLoadingStrategy(string resourceURI);
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| resourceURI | String | 资源 URI。 |

### 返回值

ResourceLoadingResult 对象。

### 另请参见

* class [ResourceLoadingResult](../loadoptions.resourceloadingresult/)
* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


