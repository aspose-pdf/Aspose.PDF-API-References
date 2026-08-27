---
title: "类 LoadOptions.ResourceLoadingResult"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.LoadOptionsResourceLoadingResult 类。自定义资源加载的结果"
type: docs
weight: 6290
url: /zh/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult class

自定义资源加载的结果

```csharp
public class ResourceLoadingResult
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [ResourceLoadingResult](../../aspose.pdf/loadoptions.resourceloadingresult/.ctor)(byte[]) | 创建加载结果的实例 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | 使用自定义加载器加载的二进制数据——必须在加载后设置 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | 有时资源的编码在加载后或加载期间才已知。在这种情况下，自定义代码可以通过此参数向转换器提供该信息。如果编码未知或无关紧要，可以将此参数设为 null。 |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | 有时由于某些原因无法加载请求的资源。资源不可用通常不会导致转换崩溃，仍然可以创建结果文档（但可能质量稍差，缺少图像等）。如果在加载期间发生异常，只需捕获并将其放入此参数——有时该信息对转换器渲染结果很有用。 |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | 有时出于某些原因不应由自定义代码进行加载。在这种情况下，请将此标志设为 True。此时转换器将尝试使用内部默认资源加载器获取结果（行为类似于未提供自定义策略的情况）。 |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | 有时已加载资源的 MIME 类型信息对转换器很有用。您可以在此参数中提供 MIME 类型（如果在加载后已知）。当 MIME 类型未知或无需提供时，请将参数设为 null。 |

### 另请参见

* class [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


