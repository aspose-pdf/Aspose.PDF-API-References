---
title: "Field.ImportValueFromJson"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Field メソッド。フィールドの完全名と完全一致する JSON ストリームから、指定されたフィールドへデータをインポートします。"
type: docs
weight: 210
url: /ja/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

フィールドの完全名が完全一致することに基づき、JSON ストリームから指定されたフィールドにデータをインポートします。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputJsonStream | Stream | フィールドにインポートされるフィールドデータを含む入力 JSON ストリームです。 |

### 戻り値

JSON ストリームでフィールドが見つかった場合は true、そうでない場合は false です。

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### 関連項目

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

JSON ストリームから指定されたフィールドにデータをインポートします。マッチングには 'fieldFullNameInJSON' 変数で指定された完全名を使用します。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| inputJsonStream | Stream | フィールドにインポートされるフィールドデータを含む入力 JSON ストリームです。 |
| fieldFullNameInJSON | String | The name of the data within the JSON stream for matching. If the data within the JSON stream has a nested structure, the full name should be specified with all parent and child items separated by '.' |

### 戻り値

json ファイルでフィールドが見つかった場合は true、そうでなければ false

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### 関連項目

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


