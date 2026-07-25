---
title: "LoadOptions.ResourceLoadingStrategy"
linktitle: "LoadOptions.ResourceLoadingStrategy"
second_title: "Aspose.PDF for Java API 参考"
description: "有时需要避免使用内部加载器加载外部资源（如图像或 CSS），并提供自定义方法，以便从某处获取请求的资源。"
type: docs
weight: 2830
url: /zh/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

有时需要避免使用内部加载器来加载外部资源（如图像或 CSS），并提供自定义方法，以从某处获取请求的资源。例如，在云端使用 Aspose.PDf 时无法直接访问引用的文件，需要将一些自定义代码放入专用方法中使用。此委托定义了此类自定义方法的签名。

## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke](#invoke-java.lang.String-) |  |

### invoke {#invoke-java.lang.String-}
