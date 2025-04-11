---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: フォームメソッド。完全修飾フィールド名に従って、フィールドに有効な値を入力します。フィールドを入力する前に、すべてのフィールド名とそれに対応する有効な値を知っている必要があります。フィールド名と値は大文字と小文字を区別します。Aspose.Pdf.Facadesは完全なフィールド名のみをサポートし、Aspose.Pdf.Kitとは対照的に部分フィールド名では機能しないことに注意してください。たとえば、フィールドの完全名がForm.Subform.TextFieldの場合、完全名を指定する必要があり、TextFieldではありません。FieldNamesプロパティを使用して既存のフィールド名を探索し、部分名によって必要なフィールドを検索できます。
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

指定された値でフィールドを入力します。

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの名前 |
| value | String | フィールドの新しい値 |
| fitFontSize | Boolean | trueの場合、編集ボックス内のフォントサイズが調整されます。 |

### 戻り値

フィールドが見つかり、正常に入力された場合はtrue。

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

完全修飾フィールド名に従って、フィールドに有効な値を入力します。フィールドを入力する前に、すべてのフィールド名とそれに対応する有効な値を知っている必要があります。フィールド名と値は大文字と小文字を区別します。Aspose.Pdf.Facadesは完全なフィールド名のみをサポートし、Aspose.Pdf.Kitとは対照的に部分フィールド名では機能しないことに注意してください。たとえば、フィールドの完全名が"Form.Subform.TextField"の場合、完全名を指定する必要があり、"TextField"ではありません。FieldNamesプロパティを使用して既存のフィールド名を探索し、部分名によって必要なフィールドを検索できます。

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 入力されるフィールドの名前。 |
| fieldValue | String | フィールドの値で、いくつかのフィールドに対して有効な値である必要があります。 |

### 戻り値

フィールドが見つかり、正常に入力された場合はtrue。

## 例

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

完全修飾フィールド名に従って、有効なインデックス値でラジオボックスフィールドを入力します。フィールドを入力する前に、フィールド名のみを知っている必要があります。値はインデックスによって指定できます。注意：これはラジオボックス、コンボボックス、およびリストボックスフィールドにのみ適用されます。Aspose.Pdf.Facadesは完全なフィールド名のみをサポートし、Aspose.Pdf.Kitとは対照的に部分フィールド名では機能しないことに注意してください。たとえば、フィールドの完全名が"Form.Subform.ListBoxField"の場合、完全名を指定する必要があり、"ListBoxField"ではありません。FieldNamesプロパティを使用して既存のフィールド名を探索し、部分名によって必要なフィールドを検索できます。

```csharp
public bool FillField(string fieldName, int index)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 入力されるフィールドの名前。 |
| index | Int32 | 選択されたアイテムのインデックス。 |

### 戻り値

フィールドが見つかり、正常に入力された場合はtrue。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

ブール値でチェックボックスフィールドを入力します。注意：これはチェックボックスにのみ適用されます。Aspose.Pdf.Facadesは完全なフィールド名のみをサポートし、Aspose.Pdf.Kitとは対照的に部分フィールド名では機能しないことに注意してください。たとえば、フィールドの完全名が"Form.Subform.CheckBoxField"の場合、完全名を指定する必要があり、"CheckBoxField"ではありません。FieldNamesプロパティを使用して既存のフィールド名を探索し、部分名によって必要なフィールドを検索できます。

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 入力されるフィールドの名前。 |
| beChecked | Boolean | ブールフラグ：trueはボックスをチェックすることを意味し、falseはチェックを外すことを意味します。 |

### 戻り値

フィールドが見つかり、正常に入力された場合はtrue。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//how to search field by its partial name:
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

複数の選択肢でフィールドを入力します。注意：AcroFormリストボックスフィールドのみに適用されます。

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |
| fieldValues | String[] | 選択される複数のアイテムを含む文字列配列。 |

## 例

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

指定された値でフィールドを入力します。

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| パラメーター | 型 | 説明 |
| --- | --- | --- |
| fieldName | String | フィールドの名前 |
| value | String | フィールドの新しい値 |
| fitFontSize | Boolean | trueの場合、編集ボックス内のフォントサイズが調整されます。 |

### 戻り値

フィールドが見つかり、正常に入力された場合はtrue。

### 参照

* クラス [Form](../)
* 名前空間 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* アセンブリ [Aspose.PDF](../../../)