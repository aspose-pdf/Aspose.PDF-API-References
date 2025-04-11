---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: フィールドメソッド。フィールドの完全な名前の正確な一致に基づいて、JSONストリームから指定されたフィールドにデータをインポートします。
type: docs
weight: 210
url: /ja/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

フィールドの完全な名前の正確な一致に基づいて、JSONストリームから指定されたフィールドにデータをインポートします。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputJsonStream | Stream | フィールドにインポートされるフィールドデータを含む入力JSONストリーム。 |

### 戻り値

JSONストリームでフィールドが見つかった場合はtrue; それ以外の場合はfalse

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### 参照

* クラス [Field](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

'fieldFullNameInJSON'変数で指定された完全な名前を使用して、JSONストリームから指定されたフィールドにデータをインポートします。

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| パラメータ | 型 | 説明 |
| --- | --- | --- |
| inputJsonStream | Stream | フィールドにインポートされるフィールドデータを含む入力JSONストリーム。 |
| fieldFullNameInJSON | String | 一致のためのJSONストリーム内のデータの名前。JSONストリーム内のデータがネストされた構造を持つ場合、完全な名前はすべての親アイテムと子アイテムを'.'で区切って指定する必要があります。 |

### 戻り値

JSONファイルでフィールドが見つかった場合はtrue; それ以外の場合はfalse

## 例

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### 参照

* クラス [Field](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)