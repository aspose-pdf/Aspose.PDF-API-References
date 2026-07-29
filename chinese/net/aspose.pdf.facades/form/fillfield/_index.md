---
title: "Form.FillField"
second_title: "Aspose.PDF for .NET API 参考"
description: "Form 方法。根据完全限定的字段名称填充值。填充字段之前，必须已知每个字段的名称及其对应的有效值。字段名称和数值均区分大小写。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，不像 Aspose.Pdf.Kit 那样支持部分字段名称。例如，如果字段的完整名称为 Form.Subform.TextField，则应指定完整名称而不是 TextField。您可以使用 FieldNames 属性来浏览现有字段名称并通过其部分名称搜索所需字段。"
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

根据完全限定字段名使用有效值填写字段。填写字段前，必须了解每个字段的名称及其对应的有效值。字段名称和数值均区分大小写。请注意 Aspose.Pdf.Facades 仅支持完整字段名称，且不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 "Form.Subform.TextField"，则应指定完整名称而不是 "TextField"。您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 要填充的字段名称。 |
| fieldValue | String | 字段的值，必须是某些字段的有效值。 |

### 返回值

如果找到并成功填充字段，则为 true。

## 示例

```csharp
Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
form.FillField("FirstName", "John");
form.FillField("LastName",  "Smith");
```

```csharp
//如何通过部分名称搜索字段：
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("TextField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

根据完全限定字段名使用有效的索引值填写单选框字段。填写字段前，只需知道字段名称即可，值可以通过其索引指定。注意：仅适用于单选框、下拉框和列表框字段。请注意 Aspose.Pdf.Facades 仅支持完整字段名称，且不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 "Form.Subform.ListBoxField"，则应指定完整名称而不是 "ListBoxField"。您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。

```csharp
public bool FillField(string fieldName, int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 要填充的字段名称。 |
| index | Int32 | 所选项目的索引。 |

### 返回值

如果找到并成功填充字段，则为 true。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```csharp
//如何通过部分名称搜索字段：
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("ListBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

使用布尔值填写复选框字段。注意：仅适用于复选框。请注意 Aspose.Pdf.Facades 仅支持完整字段名称，且不像 Aspose.Pdf.Kit 那样支持部分字段名称；例如，如果字段的完整名称为 "Form.Subform.CheckBoxField"，则应指定完整名称而不是 "CheckBoxField"。您可以使用 FieldNames 属性来浏览现有字段名称并通过部分名称搜索所需字段。

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 要填充的字段名称。 |
| beChecked | Boolean | 布尔标志：true 表示选中复选框，false 表示取消选中。 |

### 返回值

如果找到并成功填充字段，则为 true。

## 示例

```csharp
Form form = new Form("PdfForm.pdf");
form.FillField("checkboxField", true);
```

```csharp
//如何通过部分名称搜索字段：
Form form = new Form("input.pdf", "output.pdf"); 
foreach(string fieldName in form.FieldNames)
{
  if (fieldName.EndsWith("CheckBoxField"))
  {
    Console.WriteLine("Full name is: " + fieldName);
  }
}
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

使用多个选择填充字段。注意：仅适用于 AcroForm 列表框字段。

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 完全限定的字段名称。 |
| fieldValues | String[] | 包含多个待选项目的字符串数组。 |

## 示例

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

使用指定的值填写字段。

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | String | 字段名称 |
| 值 | String | 字段的新值 |
| fitFontSize | Boolean | 如果为 true，编辑框中的字体大小将自动适配。 |

### 返回值

如果找到并成功填充字段，则为 true。

### 另请参见

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


