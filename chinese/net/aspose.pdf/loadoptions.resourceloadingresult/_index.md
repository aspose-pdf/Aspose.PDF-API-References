---
title: Class LoadOptions.ResourceLoadingResult
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.LoadOptionsResourceLoadingResult 类。自定义加载资源的结果
type: docs
weight: 6150
url: /zh/net/aspose.pdf/loadoptions.resourceloadingresult/
---
## LoadOptions.ResourceLoadingResult 类

自定义加载资源的结果

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
| [Data](../../aspose.pdf/loadoptions.resourceloadingresult/data) { get; } | 使用自定义加载器加载的二进制数据 - 必须在加载后设置 |

## 字段

| 名称 | 描述 |
| --- | --- |
| [EncodingIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/encodingifknown) | 有时资源的编码在加载后或加载期间是已知的。在这种情况下，自定义代码可以通过此参数向转换器提供该知识。如果编码未知或不重要，可以将此参数留空。 |
| [ExceptionOfLoadingIfAny](../../aspose.pdf/loadoptions.resourceloadingresult/exceptionofloadingifany) | 有时由于某种原因无法加载请求的资源。资源不可用通常不会导致转换崩溃，结果文档仍然可以创建（但可能质量稍差，没有图像等）。如果在加载过程中发生异常，请捕获它并放入此参数 - 有时该信息对转换器渲染结果是有用的。 |
| [LoadingCancelled](../../aspose.pdf/loadoptions.resourceloadingresult/loadingcancelled) | 有时由于某些原因，加载不应发生自定义代码。在这种情况下，请将此标志设置为 True。在这种情况下，转换器将尝试使用内部默认资源加载器来获取该结果（就像在未提供自定义策略的情况下的行为）。 |
| [MIMETypeIfKnown](../../aspose.pdf/loadoptions.resourceloadingresult/mimetypeifknown) | 有时关于加载资源的 MIME 类型的知识对转换器是有用的。您可以在此参数中提供 MIME 类型（如果在加载后已知）。当 MIME 类型未知或不需要提供时，请将参数保持为 null。 |

### 另请参阅

* 类 [LoadOptions](../loadoptions/)
* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)