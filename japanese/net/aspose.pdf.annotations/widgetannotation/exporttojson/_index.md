---
title: "WidgetAnnotation.ExportToJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "WidgetAnnotation メソッド。指定された PDF フォームフィールドを JSON 形式にエクスポートし、結果を提供されたストリームに書き込みます。"
type: docs
weight: 120
url: /ja/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

指定された PDF フォームフィールドを JSON 形式でエクスポートし、結果を提供されたストリームに書き込みます。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | JSON 出力を書き込むストリームです。 |
| オプション | ExportFieldsToJsonOptions | フォームフィールドを JSON にエクスポートするためのオプション設定。 |

### 戻り値

指定されたフォームフィールドとその子要素（存在する場合）のエクスポート操作の結果を示す [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) のコレクション。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### 関連項目

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

指定された PDF フォームフィールドを JSON 形式でエクスポートし、結果を指定されたファイルに書き込みます。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fileName | String | JSON 出力を書き込むファイル名です。 |
| オプション | ExportFieldsToJsonOptions | フォームフィールドを JSON にエクスポートするためのオプション設定。 |

### 戻り値

指定されたフォームフィールドとその子要素（存在する場合）のエクスポート操作の結果を示す [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) のコレクション。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### 関連項目

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


