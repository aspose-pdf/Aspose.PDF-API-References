---
title: "Field.ImportValueFromJson"
second_title: "Aspose.PDF for .NET API 参考"
description: "Field 方法。从 JSON 流中导入数据到指定字段，基于字段完整名称的精确匹配。"
type: docs
weight: 210
url: /zh/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

从 JSON 流中导入数据到指定字段，基于字段完整名称的精确匹配。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputJsonStream | Stream | 包含要导入到字段的字段数据的输入 JSON 流。 |

### 返回值

如果在 JSON 流中找到字段则为 True；否则为 false

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### 另请参见

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

从 JSON 流中导入数据到指定字段，使用 'fieldFullNameInJSON' 变量中指定的完整名称进行匹配。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputJsonStream | Stream | 包含要导入到字段的字段数据的输入 JSON 流。 |
| fieldFullNameInJSON | String | 用于匹配的 JSON 流中数据的名称。如果 JSON 流中的数据具有嵌套结构，则应使用由 '.' 分隔的所有父项和子项的完整名称。 |

### 返回值

如果在 json 文件中找到该字段则为 True；否则为 false。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### 另请参见

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


