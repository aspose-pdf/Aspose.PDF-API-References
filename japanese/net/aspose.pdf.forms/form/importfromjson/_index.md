---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。ストリームで提供されたJSON形式からPDFフォームフィールドをインポートします
type: docs
weight: 290
url: /ja/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

ストリームで提供されたJSON形式からPDFフォームフィールドをインポートします。

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| stream | Stream | JSON入力を読み取るためのストリーム。 |

### 戻り値

各フォームフィールドのインポート操作の結果を示す[`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)のコレクション。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### 参照

* クラス [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

指定されたファイルからJSON形式のPDFフォームフィールドをインポートします。

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fileName | String | JSON入力を読み取るファイルの名前。 |

### 戻り値

各フォームフィールドのインポート操作の結果を示す[`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/)のコレクション。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### 参照

* クラス [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)