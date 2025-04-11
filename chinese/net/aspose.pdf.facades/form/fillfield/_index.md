---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: 表单方法。根据完全限定的字段名称填充字段的有效值。在填充字段之前，必须知道每个字段的名称及其对应的有效值。字段名称和值均区分大小写。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，这与 Aspose.Pdf.Kit 相对。例如，如果字段的完整名称为 Form.Subform.TextField，则应指定完整名称，而不是 TextField。您可以使用 FieldNames 属性来探索现有字段名称，并通过其部分名称搜索所需字段。
type: docs
weight: 130
url: /zh/net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string, bool) {#fillfield_3}

使用指定的值填充字段。

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段名称 |
| value | 字符串 | 字段的新值 |
| fitFontSize | 布尔值 | 如果为 true，则编辑框中的字体大小将被调整。 |

### 返回值

如果找到字段并成功填充，则返回 true。

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FillField(string, string) {#fillfield_2}

根据完全限定的字段名称填充字段的有效值。在填充字段之前，必须知道每个字段的名称及其对应的有效值。字段名称和值均区分大小写。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，这与 Aspose.Pdf.Kit 相对；例如，如果字段的完整名称为 "Form.Subform.TextField"，则应指定完整名称，而不是 "TextField"。您可以使用 FieldNames 属性来探索现有字段名称，并通过其部分名称搜索所需字段。

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 要填充的字段名称。 |
| fieldValue | 字符串 | 字段的值，必须是某些字段的有效值。 |

### 返回值

如果找到字段并成功填充，则返回 true。

## 示例

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

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

根据完全限定的字段名称使用有效的索引值填充单选框字段。在填充字段之前，仅需知道字段的名称。值可以通过其索引指定。注意：仅适用于单选框、组合框和列表框字段。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，这与 Aspose.Pdf.Kit 相对；例如，如果字段的完整名称为 "Form.Subform.ListBoxField"，则应指定完整名称，而不是 "ListBoxField"。您可以使用 FieldNames 属性来探索现有字段名称，并通过其部分名称搜索所需字段。

```csharp
public bool FillField(string fieldName, int index)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 要填充的字段名称。 |
| index | Int32 | 选择项的索引。 |

### 返回值

如果找到字段并成功填充，则返回 true。

## 示例

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

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

使用布尔值填充复选框字段。注意：仅适用于复选框。请注意，Aspose.Pdf.Facades 仅支持完整字段名称，而不支持部分字段名称，这与 Aspose.Pdf.Kit 相对；例如，如果字段的完整名称为 "Form.Subform.CheckBoxField"，则应指定完整名称，而不是 "CheckBoxField"。您可以使用 FieldNames 属性来探索现有字段名称，并通过其部分名称搜索所需字段。

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 要填充的字段名称。 |
| beChecked | 布尔值 | 布尔标志：true 表示选中复选框，false 表示取消选中。 |

### 返回值

如果找到字段并成功填充，则返回 true。

## 示例

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

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

使用多个选择填充字段。注意：仅适用于 AcroForm 列表框字段。

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 完全限定的字段名称。 |
| fieldValues | 字符串[] | 包含多个要选择的项的字符串数组。 |

## 示例

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)

--- 

## FillField(string, string, bool) {#fillfield_3}

使用指定的值填充字段。

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fieldName | 字符串 | 字段名称 |
| value | 字符串 | 字段的新值 |
| fitFontSize | 布尔值 | 如果为 true，则编辑框中的字体大小将被调整。 |

### 返回值

如果找到字段并成功填充，则返回 true。

### 另请参阅

* 类 [Form](../)
* 命名空间 [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* 程序集 [Aspose.PDF](../../../)