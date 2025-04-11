---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: 字段方法。从 JSON 流中根据字段全名的精确匹配将数据导入指定字段
type: docs
weight: 210
url: /zh/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

从 JSON 流中根据字段的全名的精确匹配将数据导入指定字段。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputJsonStream | Stream | 包含要导入到字段中的字段数据的输入 JSON 流。 |

### 返回值

如果在 JSON 流中找到字段，则为真；否则为假

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### 另请参阅

* 类 [Field](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

从 JSON 流中将数据导入指定字段，使用 'fieldFullNameInJSON' 变量中指定的全名进行匹配。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| inputJsonStream | Stream | 包含要导入到字段中的字段数据的输入 JSON 流。 |
| fieldFullNameInJSON | String | JSON 流中用于匹配的数据名称。如果 JSON 流中的数据具有嵌套结构，则应使用 '.' 分隔所有父项和子项来指定全名。 |

### 返回值

如果在 JSON 文件中找到字段，则为真；否则为假

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### 另请参阅

* 类 [Field](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)