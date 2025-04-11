---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: WidgetAnnotation 方法。将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流
type: docs
weight: 120
url: /zh/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入提供的流。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| stream | Stream | 要写入 JSON 输出的流。 |
| options | ExportFieldsToJsonOptions | 导出表单字段到 JSON 的可选设置。 |

### 返回值

一个 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 的集合，指示指定表单字段及其子元素（如果存在）的导出操作结果。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### 另请参阅

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

将指定的 PDF 表单字段导出为 JSON 格式，并将结果写入指定的文件。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 要写入 JSON 输出的文件名。 |
| options | ExportFieldsToJsonOptions | 导出表单字段到 JSON 的可选设置。 |

### 返回值

一个 [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) 的集合，指示指定表单字段及其子元素（如果存在）的导出操作结果。

## 示例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### 另请参阅

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)