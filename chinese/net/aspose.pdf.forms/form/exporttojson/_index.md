---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。将 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流
type: docs
weight: 240
url: /zh/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

将 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要写入 JSON 输出的流。 |
| options | ExportFieldsToJsonOptions | 导出表单字段到 JSON 的可选设置。 |

### 返回值

一个 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 集合，指示每个表单字段导出操作的结果。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### 另见

* 类 [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* 类 [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

将 PDF 表单字段导出为 JSON 格式，并将结果写入指定的文件。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 要写入 JSON 输出的文件名。 |
| options | ExportFieldsToJsonOptions | 导出表单字段到 JSON 的可选设置。 |

### 返回值

一个 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 集合，指示每个表单字段导出操作的结果。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### 另见

* 类 [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* 类 [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* 程序集 [Aspose.PDF](../../../)