---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Permissions 枚举。此枚举表示用户对 PDF 的权限
type: docs
weight: 8480
url: /zh/net/aspose.pdf/permissions/
---
## 权限枚举

此枚举表示用户对 PDF 的权限。

```csharp
[Flags]
public enum Permissions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PrintDocument | `4` | （修订版 2 的安全处理程序）打印文档。 （修订版 3 或更高版本的安全处理程序）打印文档（可能不是最高质量级别，具体取决于是否也设置了 PrintingQuality）。 |
| ModifyContent | `8` | 通过其他操作修改文档的内容，而不是由 ModifyTextAnnotations、FillForm 和 11 控制的操作。 |
| ExtractContent | `10` | （修订版 2 的安全处理程序）从文档中复制或以其他方式提取文本和图形，包括提取文本和图形（以支持残疾用户的可访问性或其他目的）。 （修订版 3 或更高版本的安全处理程序）通过其他操作从文档中复制或以其他方式提取文本和图形，而不是由 ExtractContentWithDisabilities 控制的操作。 |
| ModifyTextAnnotations | `20` | 添加或修改文本注释，填写交互式表单字段，并且如果 ModifyContent 也被设置，则创建或修改交互式表单字段（包括签名字段）。 |
| FillForm | `100` | （修订版 3 或更高版本的安全处理程序）填写现有的交互式表单字段（包括签名字段），即使 ModifyTextAnnotations 被清除。 |
| ExtractContentWithDisabilities | `200` | （修订版 3 或更高版本的安全处理程序）提取文本和图形（以支持残疾用户的可访问性或其他目的）。 |
| AssembleDocument | `400` | （修订版 3 或更高版本的安全处理程序）组装文档（插入、旋转或删除页面并创建书签或缩略图），即使 ModifyContent 被清除。 |
| PrintingQuality | `800` | （修订版 3 或更高版本的安全处理程序）将文档打印为可以生成 PDF 内容的忠实数字副本的表示形式。当此位被清除（并且位 3 被设置）时，打印限制为外观的低级表示，可能质量下降。 |

### 另请参阅

* 命名空间 [Aspose.Pdf](../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../)