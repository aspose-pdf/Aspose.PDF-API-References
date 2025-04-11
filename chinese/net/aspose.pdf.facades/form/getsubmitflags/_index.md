---
title: Form.GetSubmitFlags
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。返回提交按钮的提交标志
type: docs
weight: 270
url: /zh/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags 方法

返回提交按钮的提交标志

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 合格的字段名称。 |

### 返回值

按钮的提交标志。

## 示例

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### 另请参阅

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)