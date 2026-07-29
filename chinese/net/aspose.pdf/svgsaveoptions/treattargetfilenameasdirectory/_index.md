---
title: "SvgSaveOptions.TreatTargetFileNameAsDirectory"
second_title: "Aspose.PDF for .NET API 参考"
description: "SvgSaveOptions 字段。此选项定义是否在目标目录不存在时创建一个与请求的输出文件同名的目标目录，而不是直接创建请求的输出文件本身。这样，目录将包含所有页面的输出 SVG 图像，如下所述。如果除第一页之外的页面输出文件不会在请求的目录中创建为主输出文件，而是会在文件名后添加由页码定义的后缀 _2...n。例如，如果您定义输出文件 CAsposeTestsoutput.svg，并且输出将包含多个页面的 svg 文件，则页面文件也会在目录 CAsposeTests 中创建，名称为 output.svg、output_2.svg、output_3.svg 等。"
type: docs
weight: 50
url: /zh/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory field

此选项定义是否在目标输出文件不存在时创建与请求的输出文件同名的目标目录，而不是直接创建输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下所述）。如果选择否，则除第一页之外的页面输出文件将直接在请求的目录中创建，文件名会带有 _[2...n] 后缀，由页码决定。例如，如果您将输出文件定义为 "C:\\AsposeTests\\output.svg"，且输出包含多个页面的 SVG 文件，则页面文件也会在目录 "C:\\AsposeTests\\" 中创建，名称分别为 'output.svg'、'output_2.svg'、'output_3.svg' 等。

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### 另请参见

* class [SvgSaveOptions](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


