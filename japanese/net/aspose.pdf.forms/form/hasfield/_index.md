---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。フォームに指定されたフィールドがすでに存在するか確認します。
type: docs
weight: 280
url: /ja/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

フォームに指定されたフィールドがすでに存在するか確認します。

```csharp
public bool HasField(Field field)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| field | Field | 確認するフィールド。 |

### 戻り値

指定されたフィールド名がフォームに追加されていれば `true`、そうでなければ `false` です。

### 参照

* クラス [Field](../../field/)
* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

指定された名前のフィールドがすでにフォームに追加されているかどうかを判断します。

```csharp
public bool HasField(string fieldName)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) または [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) のフィールド。 |

### 戻り値

指定されたフィールド名がフォームに追加されていれば `true`、そうでなければ `false` です。

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

指定された名前のフィールドがすでにフォームに追加されているかどうかを判断し、フィールドの子階層を検索する機能を持ちます。

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) または [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) のフィールド。 |
| searchChildren | Boolean | `true` に設定すると、要求された *fieldName* のためにフォームフィールドの全階層が検索されます（この場合、必要なフィールドの [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) を *fieldName* として渡す必要があります）。 |

### 戻り値

指定されたフィールド名がフォームに追加されていれば `true`、そうでなければ `false` です。

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* アセンブリ [Aspose.PDF](../../../)