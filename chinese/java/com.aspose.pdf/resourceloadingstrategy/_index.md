---
title: LoadOptions.ResourceLoadingStrategy
second_title: 用于 Java API 参考的 Aspose.PDF
description: 有时有必要避免使用外部资源（如图像或 CSS）的内部加载器，并提供从某处获取请求资源的自定义方法。
type: docs
weight: 13
url: /zh/java/com.aspose.pdf/loadoptions.resourceloadingstrategy/
---
```
public static interface LoadOptions.ResourceLoadingStrategy
```

有时有必要避免使用外部资源（如图像或 CSS）的内部加载器并提供自定义方法，这将从某处获取请求的资源。例如，在云中使用 Aspose.PDF 时，不可能直接访问引用的文件，而应该使用一些放入特殊方法的客户代码。此委托定义此类自定义方法的签名。
## 方法

| 方法 | 描述 |
| --- | --- |
| [invoke(String resourceURI)](#invoke-java.lang.String-) |  |
### invoke(String resourceURI) {#invoke-java.lang.String-}
```
public abstract LoadOptions.ResourceLoadingResult invoke(String resourceURI)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| resourceURI | java.lang.String |  |

**退货：**
[ResourceLoadingResult](../../com.aspose.pdf/resourceloadingresult)