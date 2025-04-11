---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。フォームにフィールドを追加します。
type: docs
weight: 190
url: /ja/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

フォームにフィールドを追加します。

```csharp
public void Add(Field field, int pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| field | Field | 追加するフィールド。 |
| pageNumber | Int32 | 追加されたフィールドが配置されるページインデックス。 |

### 参照

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

フォームにフィールドを追加します。

```csharp
public void Add(Field field)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| field | Field | 追加するフィールド。 |

### 参照

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

フォームに新しいフィールドを追加します。このフィールドが他のフォームまたはこのフォームに既に配置されている場合、フィールドのコピーが作成されます。

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| field | Field | フィールド名。 |
| partialName | String | フォーム上のフィールドの名前。 |
| pageNumber | Int32 | フィールドが追加されるページ番号。 |

### 戻り値

追加されたフィールドが返されます。フィールドのコピーが作成された場合、それが返されます。

### 参照

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)