---
title: Form.FillField
second_title: Aspose.PDF for .NET API Reference
description: Form method. Fills the field with a valid value according to a fully qualified field name. Before filling the fields every fields names and its corresponding valid values must be known. Both the fields name and values are case sensitive. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit For example if field has full name Form.Subform.TextField you should specify full name and not TextField. You can use FieldNames property to explore existing field names and search required field by its partial name
type: docs
weight: 130
url: /net/aspose.pdf.facades/form/fillfield/
---
## FillField(string, string) {#fillfield_2}

Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```csharp
public bool FillField(string fieldName, string fieldValue)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The field's name to be filled. |
| fieldValue | String | The field's value which must be a valid value for some fields. |

### Return Value

true if field is found and filled successfully.

## Examples

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

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, int) {#fillfield_1}

Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```csharp
public bool FillField(string fieldName, int index)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field to be filled. |
| index | Int32 | Index of chosen item. |

### Return Value

true if field was found and successfully filled.

## Examples

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

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, bool) {#fillfield}

Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```csharp
public bool FillField(string fieldName, bool beChecked)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The field's name to be filled. |
| beChecked | Boolean | A boolean flag: true means to check the box, while false to uncheck it. |

### Return Value

true if field was found and successfully filled.

## Examples

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

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string[]) {#fillfield_4}

Fill a field with multiple selections.Note: only for AcroForm List Box Field.

```csharp
public void FillField(string fieldName, string[] fieldValues)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |
| fieldValues | String[] | A string array which contains several items to be selected. |

## Examples

```csharp
Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf", "Form_Updated.pdf");
form.FillField("ListBox1", new String[] { "Three", "One" });
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillField(string, string, bool) {#fillfield_3}

Fills field with specified value.

```csharp
public bool FillField(string fieldName, string value, bool fitFontSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field |
| value | String | New value of the field |
| fitFontSize | Boolean | If true, the font size in the edit boxes will be fitted. |

### Return Value

true if field was found and successfully filled.

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


