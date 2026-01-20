---
title: Aspose::Pdf::Facades::Form::FillField method
linktitle: FillField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::FillField method. Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/form/fillfield/
---
## Form::FillField(System::String, bool) method


Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that [Aspose.Pdf.Facades](../../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, bool beChecked)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The field's name to be filled. |
| beChecked | bool | A boolean flag: true means to check the box, while false to uncheck it. |

### ReturnValue

true if field was found and successfully filled.

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, int32_t) method


Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that [Aspose.Pdf.Facades](../../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | Name of field to be filled. |
| index | int32_t | Index of chosen item. |

### ReturnValue

true if field was found and successfully filled.
## Remarks




```cpp
Form form = new Form("PdfForm.pdf");
form.FillField("listboxField", 2);
form.FillField("comboboxField", 2);
form.FillField("radiobuttonField", 2);
```

```cpp
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

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, System::ArrayPtr\<System::String\>) method


Fill a field with multiple selections.Note: only for AcroForm List Box Field.

```cpp
void Aspose::Pdf::Facades::Form::FillField(System::String fieldName, System::ArrayPtr<System::String> fieldValues)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The fully qualified field name. |
| fieldValues | System::ArrayPtr\<System::String\> | A string array which contains several items to be selected. |

## See Also

* Class [String](../../../system/string/)
* Typedef [ArrayPtr](../../../system/arrayptr/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, System::String) method


Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that [Aspose.Pdf.Facades](../../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, System::String fieldValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The field's name to be filled. |
| fieldValue | System::String | The field's value which must be a valid value for some fields. |

### ReturnValue

true if field is found and filled successfully.

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, System::String, bool) method


Fills field with specified value.

```cpp
bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, System::String value, bool fitFontSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | Name of field |
| value | System::String | New value of the field |
| fitFontSize | bool | If true, the font size in the edit boxes will be fitted. |

### ReturnValue

true if field was found and successfully filled.

## See Also

* Class [String](../../../system/string/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
