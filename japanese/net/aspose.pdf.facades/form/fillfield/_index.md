---
title: "Form.FillField"
second_title: "Aspose.PDF for .NET API リファレンス"
description: "Form メソッド。完全修飾フィールド名に従って、有効な値でフィールドを埋めます。フィールドを埋める前に、すべてのフィールド名とそれに対応する有効な値を把握しておく必要があります。フィールド名と値は大文字小文字を区別します。Aspose.Pdf.Facades は完全なフィールド名のみをサポートし、Aspose.Pdf.Kit とは対照的に部分的なフィールド名は使用できないことに注意してください。例えば、フィールドの完全名が Form.Subform.TextField の場合、TextField ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。"
type: docs
weight: 130
url: /ja/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

完全修飾フィールド名に従って、フィールドに有効な値を設定します。フィールドに入力する前に、すべてのフィールド名と対応する有効な値が分かっている必要があります。フィールド名と値は大文字小文字を区別します。Aspose.Pdf.Facades は完全修飾フィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が "Form.Subform.TextField" の場合、"TextField" ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 埋めるフィールドの名前です。 |
| fieldValue | String | フィールドの値で、いくつかのフィールドに対して有効な値である必要があります。 |

### 戻り値

フィールドが見つかり、正常に埋められた場合は true。

## 例

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//部分名でフィールドを検索する方法：
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

完全修飾フィールド名に従って、ラジオボックスフィールドに有効なインデックス値を設定します。フィールドに入力する前に、フィールド名のみが分かっていれば構いません。値はインデックスで指定できます。注意: ラジオボックス、コンボボックス、リストボックスフィールドにのみ適用されます。Aspose.Pdf.Facades は完全修飾フィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が "Form.Subform.ListBoxField" の場合、"ListBoxField" ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。

```csharp
public bool FillField(string fieldName, int index)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 埋めるフィールドの名前です。 |
| インデックス | Int32 | 選択された項目のインデックスです。 |

### 戻り値

フィールドが見つかり、正常に埋められた場合は true。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//部分名でフィールドを検索する方法：
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

チェックボックスフィールドにブール値を設定します。注意: チェックボックスにのみ適用されます。Aspose.Pdf.Facades は完全修飾フィールド名のみをサポートし、Aspose.Pdf.Kit とは異なり部分的なフィールド名は使用できません。例えば、フィールドの完全名が "Form.Subform.CheckBoxField" の場合、"CheckBoxField" ではなく完全名を指定する必要があります。既存のフィールド名を調べ、部分名で目的のフィールドを検索するには FieldNames プロパティを使用できます。

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 埋めるフィールドの名前です。 |
| beChecked | Boolean | ブールフラグ：true はチェックボックスをオンにし、false はオフにします。 |

### 戻り値

フィールドが見つかり、正常に埋められた場合は true。

## 例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//部分名でフィールドを検索する方法：
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

複数選択でフィールドに入力します。注意: AcroForm のリストボックスフィールドのみ対象です。

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | 完全修飾フィールド名。 |
| fieldValues | String[] | 選択可能な複数の項目を含む文字列配列です。 |

## 例

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

指定された値でフィールドに入力します。

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| パラメーター | タイプ | 説明 |
| --- | --- | --- |
| fieldName | String | フィールド名 |
| 値 | String | フィールドの新しい値 |
| fitFontSize | Boolean | true の場合、編集ボックス内のフォントサイズが調整されます。 |

### 戻り値

フィールドが見つかり、正常に埋められた場合は true。

### 関連項目

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


