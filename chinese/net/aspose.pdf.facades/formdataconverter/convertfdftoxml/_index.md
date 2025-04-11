---
title: FormDataConverter.ConvertFdfToXml
second_title: Aspose.PDF for .NET API Reference
description: FormDataConverter 方法。将 FDF 文件转换为 XML
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml 方法

将 FDF 文件转换为 XML。

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFdf | Stream | 包含要转换的 FDF 的流。 |
| destXml | Stream | 结果 XML 将放置的源。 |

## 示例

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### 另请参阅

* 类 [FormDataConverter](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)