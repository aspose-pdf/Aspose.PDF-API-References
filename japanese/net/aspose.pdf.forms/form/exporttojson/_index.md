---
title: "Form.ExportToJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。 PDF フォームフィールドを JSON 形式でエクスポートし、結果を提供されたストリームに書き込みます。"
type: docs
weight: 260
url: /ja/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

PDF フォームフィールドを JSON 形式でエクスポートし、結果を提供されたストリームに書き込みます。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | JSON 出力を書き込むストリームです。 |
| オプション | ExportFieldsToJsonOptions | フォームフィールドを JSON にエクスポートするためのオプション設定です。 |

### 戻り値

各フォームフィールドのエクスポート操作の結果を示す [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) のコレクションです。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### 関連項目

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

PDF フォーム フィールドを JSON 形式でエクスポートし、結果を指定されたファイルに書き込みます。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fileName | String | JSON 出力を書き込むファイル名です。 |
| オプション | ExportFieldsToJsonOptions | フォームフィールドを JSON にエクスポートするためのオプション設定です。 |

### 戻り値

各フォームフィールドのエクスポート操作の結果を示す [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) のコレクションです。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### 関連項目

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


