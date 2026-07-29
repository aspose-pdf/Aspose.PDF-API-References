---
title: "Form.ImportFromJson"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将流中提供的 JSON 格式的 PDF 表单字段导入。"
type: docs
weight: 310
url: /zh/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

从流中提供的 JSON 格式导入 PDF 表单字段。

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于读取 JSON 输入的流。 |

### 返回值

一个集合，包含每个表单字段的导入操作结果，见 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### 另请参见

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

从指定文件中提供的 JSON 格式导入 PDF 表单字段。

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 用于读取 JSON 输入的文件名。 |

### 返回值

一个集合，包含每个表单字段的导入操作结果，见 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### 另请参见

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


