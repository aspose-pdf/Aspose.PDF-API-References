---
title: SvgSaveOptions.TreatTargetFileNameAsDirectory
second_title: Aspose.PDF for .NET API Reference
description: SvgSaveOptions 字段。此选项定义是否会创建目标目录（如果尚不存在），其名称与请求的输出文件相同，而不是请求的输出文件本身。这样，目录将包含所有页面的输出 SVG 图像，如下所述。如果没有，除了第一个页面之外的页面输出文件将确切地在请求的目录中创建作为主输出文件，但文件名将包含后缀 _[2...n]，由页面编号定义，例如，如果您定义输出文件 "C:\AsposeTests\output.svg"，并且输出将包含多个页面的 svg 文件，则页面文件也将在目录 "C:\AsposeTests\" 中创建，并具有名称 'output.svg'、'output_2.svg'、'output_3.svg' 等。
type: docs
weight: 50
url: /zh/net/aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/
---
## SvgSaveOptions.TreatTargetFileNameAsDirectory 字段

此选项定义是否会创建目标目录（如果尚不存在），其名称与请求的输出文件相同，而不是请求的输出文件本身。这样，目录将包含所有页面的输出 SVG 图像（如下面所述）。如果没有，除了第一个页面之外的页面输出文件将确切地在请求的目录中创建作为主输出文件，但文件名将包含后缀 _[2...n]，由页面编号定义，例如，如果您定义输出文件 "C:\AsposeTests\output.svg"，并且输出将包含多个页面的 svg 文件，则页面文件也将在目录 "C:\AsposeTests\" 中创建，并具有名称 'output.svg'、'output_2.svg'、'output_3.svg' 等。

```csharp
public bool TreatTargetFileNameAsDirectory;
```

### 另请参阅

* 类 [SvgSaveOptions](../)
* 命名空间 [Aspose.Pdf](../../../aspose.pdf/)
* 程序集 [Aspose.PDF](../../../)