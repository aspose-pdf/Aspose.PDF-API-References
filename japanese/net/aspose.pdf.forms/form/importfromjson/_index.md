---
title: "Form.ImportFromJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。 ストリームで提供される JSON 形式から PDF フォームフィールドをインポートします。"
type: docs
weight: 310
url: /ja/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

ストリームで提供された JSON 形式から PDF フォーム フィールドをインポートします。

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| stream | Stream | JSON 入力を読み取るストリームです。 |

### 戻り値

各フォームフィールドのインポート操作の結果を示す [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) のコレクションです。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### 関連項目

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

指定されたファイルで提供された JSON 形式から PDF フォーム フィールドをインポートします。

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fileName | String | JSON 入力を読み取るファイル名です。 |

### 戻り値

各フォームフィールドのインポート操作の結果を示す [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) のコレクションです。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### 関連項目

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


