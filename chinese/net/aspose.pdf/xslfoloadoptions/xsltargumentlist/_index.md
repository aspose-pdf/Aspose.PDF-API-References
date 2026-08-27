---
title: "XslFoLoadOptions.XsltArgumentList"
second_title: "Aspose.PDF for .NET API 参考"
description: "XslFoLoadOptions 属性。XsltArgumentList 用于向现有 xls 参数插入值。XLS 文件有 animal 参数但没有值。XsltArgumentList args = new XsltArgumentList(); args.AddParamanimal(\"cat\"); 现在转换器假设 XLS 文件中存在一个值为 cat 的 animal 参数。"
type: docs
weight: 30
url: /zh/net/aspose.pdf/xslfoloadoptions/xsltargumentlist/
---
## XslFoLoadOptions.XsltArgumentList property

XsltArgumentList 用于向现有的 xls 参数插入值。XLS 文件有一个没有值的 'animal' 参数：XsltArgumentList args = new XsltArgumentList(); args.AddParam(\"animal\", \"\", \"cat\"); 现在转换器假设 XLS 文件中存在值为 'cat' 的 'animal' 参数。

```csharp
public XsltArgumentList XsltArgumentList { get; set; }
```

### 另请参见

* class [XslFoLoadOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


