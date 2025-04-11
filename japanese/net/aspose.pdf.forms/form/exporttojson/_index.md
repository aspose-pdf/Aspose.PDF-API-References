---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。PDFフォームフィールドをJSON形式にエクスポートし、結果を指定されたストリームに書き込みます。
type: docs
weight: 240
url: /ja/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

PDFフォームフィールドをJSON形式にエクスポートし、結果を指定されたストリームに書き込みます。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | JSON出力を書き込むストリーム。 |
| options | ExportFieldsToJsonOptions | フォームフィールドをJSONにエクスポートするためのオプション設定。 |

### 戻り値

各フォームフィールドのエクスポート操作の結果を示す[`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)のコレクション。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### 参照

* クラス [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* クラス [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

PDFフォームフィールドをJSON形式にエクスポートし、結果を指定されたファイルに書き込みます。

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | String | JSON出力を書き込むファイルの名前。 |
| options | ExportFieldsToJsonOptions | フォームフィールドをJSONにエクスポートするためのオプション設定。 |

### 戻り値

各フォームフィールドのエクスポート操作の結果を示す[`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)のコレクション。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### 参照

* クラス [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* クラス [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)