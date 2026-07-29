---
title: "FormDataConverter.ConvertFdfToXml"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormDataConverter. تحويل ملف FDF إلى XML"
type: docs
weight: 120
url: /ar/net/aspose.pdf.facades/formdataconverter/convertfdftoxml/
---
## FormDataConverter.ConvertFdfToXml method

تحويل ملف FDF إلى XML.

```csharp
public static void ConvertFdfToXml(Stream sourceFdf, Stream destXml)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| sourceFdf | Stream | دفق يحتوي على FDF للتحويل. |
| destXml | Stream | المصدر حيث سيتم وضع XML الناتج. |

## أمثلة

```csharp
src = new FileStream("test.fdf", FileMode.Open);
dest = new FileStream("converted_fdf.xml", FileMode.Create);
FormDataConverter.ConvertFdfToXml(src, dest);
src.Close();
dest.Close();
```

### انظر أيضًا

* class [FormDataConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


