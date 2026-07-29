---
title: "枚举 Permissions"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Permissions 枚举。此枚举表示用户对 PDF 的权限。"
type: docs
weight: 8610
url: /zh/net/aspose.pdf/permissions/
---
## Permissions enumeration

此枚举表示用户对 PDF 的权限。

```csharp
[Flags]
public enum Permissions
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| PrintDocument | `4` | (修订版 2 的安全处理程序) 打印文档。 (修订版 3 或更高的安全处理程序) 打印文档（可能未达到最高质量水平，取决于是否也设置了 PrintingQuality）。 |
| ModifyContent | `8` | 通过除 ModifyTextAnnotations、FillForm 和 11 控制之外的操作修改文档内容。 |
| ExtractContent | `10` | (修订版 2 的安全处理程序) 复制或以其他方式从文档中提取文本和图形，包括提取文本和图形（以支持残障用户的可访问性或用于其他目的）。 (修订版 3 或更高的安全处理程序) 通过除 ExtractContentWithDisabilities 控制之外的操作复制或以其他方式从文档中提取文本和图形。 |
| ModifyTextAnnotations | `20` | 添加或修改文本批注，填写交互式表单字段，并且如果同时设置了 ModifyContent，则创建或修改交互式表单字段（包括签名字段）。 |
| FillForm | `100` | (修订版 3 或更高的安全处理程序) 填写现有的交互式表单字段（包括签名字段），即使 ModifyTextAnnotations 已清除。 |
| ExtractContentWithDisabilities | `200` | (修订版 3 或更高的安全处理程序) 提取文本和图形（以支持残障用户的可访问性或用于其他目的）。 |
| AssembleDocument | `400` | (修订版 3 或更高的安全处理程序) 组装文档（插入、旋转或删除页面并创建书签或缩略图），即使 ModifyContent 已清除。 |
| PrintingQuality | `800` | （修订版 3 或更高的安全处理程序）将文档打印为一种可以生成 PDF 内容忠实数字副本的表示形式。当此位被清除（且第 3 位被设置）时，打印仅限于外观的低级表示，可能质量下降。 |

### 另请参见

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


