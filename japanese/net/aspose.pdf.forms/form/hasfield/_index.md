---
title: "Form.HasField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。フォームに指定されたフィールドが既に存在するか確認します。"
type: docs
weight: 300
url: /ja/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

フォームに指定されたフィールドがすでに存在するか確認します。

```csharp
public bool HasField(Field field)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| フィールド | フィールド | チェックするフィールド。 |

### 戻り値

`true` は、指定されたフィールド名が Form に追加された場合です。そうでなければ `false` です。

### 関連項目

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

指定された名前のフィールドがすでにフォームに追加されているかどうかを判断します。

```csharp
public bool HasField(string fieldName)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) または [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) のフィールド。 |

### 戻り値

`true` は、指定されたフィールド名が Form に追加された場合です。そうでなければ `false` です。

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

指定された名前のフィールドがすでにフォームに追加されているかどうかを判断し、フィールドの子階層も参照できるようにします。

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) または [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) のフィールド。 |
| searchChildren | Boolean | `true` に設定すると、要求された *fieldName* のためにフォームフィールド全体の階層が検索されます（この場合、必要なフィールドの [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) を *fieldName* として渡す必要があることに注意してください）。 |

### 戻り値

`true` は、指定されたフィールド名が Form に追加された場合です。そうでなければ `false` です。

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


