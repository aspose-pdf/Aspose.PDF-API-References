---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "Aspose.PDF for .NET API 参考"
description: "FormDataConverter 方法。将 FDF 文件转换为 XML"
type: docs
weight: 120
url: /zh/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

将 FDF 文件转换为 XML。

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sourceFdf | Stream | 包含待转换 FDF 的流。 |
| destXml | Stream | 放置结果 XML 的位置。 |

## 示例

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### 另请参见

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


