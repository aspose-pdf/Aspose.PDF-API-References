---
title: "类 OcrDetail"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.AI.OcrDetail 类。表示文档单页或单个图像文件的 OCR 结果"
type: docs
weight: 860
url: /zh/net/aspose.pdf.ai/ocrdetail/
---
## OcrDetail class

表示文档单页或单个图像文件的 OCR 结果。

```csharp
public class OcrDetail : IComparable<OcrDetail>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [OcrDetail](ocrdetail/)() | 默认构造函数。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [ErrorMessage](../../aspose.pdf.ai/ocrdetail/errormessage/) { get; set; } | 如果 Success 为 false，则为描述此页面 OCR 失败原因的错误消息；否则为 Null。 |
| [ExtractedText](../../aspose.pdf.ai/ocrdetail/extractedtext/) { get; set; } | 页面提取的文本内容。如果 Success 为 false 或未找到文本，则为 Null。 |
| [PageNumber](../../aspose.pdf.ai/ocrdetail/pagenumber/) { get; set; } | 源文档中基于 1 的页面编号。对于单页图像，此值始终为 1。 |
| [Success](../../aspose.pdf.ai/ocrdetail/success/) { get; set; } | 指示此特定页面的 OCR 提取是否成功。 |
| [Usage](../../aspose.pdf.ai/ocrdetail/usage/) { get; set; } | 获取或设置使用统计信息。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [CompareTo](../../aspose.pdf.ai/ocrdetail/compareto/)(OcrDetail) | 根据 PageNumber 属性比较当前 OcrDetail 实例与另一个 OcrDetail 对象。 |

### 另请参见

* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


