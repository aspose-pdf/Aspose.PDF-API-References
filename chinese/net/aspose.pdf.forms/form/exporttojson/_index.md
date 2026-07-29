---
title: "Form.ExportToJson"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。将 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流。"
type: docs
weight: 260
url: /zh/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

将 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流中。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 用于写入 JSON 输出的流。 |
| options | ExportFieldsToJsonOptions | 导出表单字段为 JSON 的可选设置。 |

### 返回值

一个集合，包含每个表单字段的导出操作结果，见 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### 另请参见

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

将 PDF 表单字段导出为 JSON 格式，并将结果写入指定的文件。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 用于写入 JSON 输出的文件名。 |
| options | ExportFieldsToJsonOptions | 导出表单字段为 JSON 的可选设置。 |

### 返回值

一个集合，包含每个表单字段的导出操作结果，见 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### 另请参见

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


