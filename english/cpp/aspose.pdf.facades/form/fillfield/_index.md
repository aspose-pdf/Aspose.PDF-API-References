---
title: Aspose::Pdf::Facades::Form::FillField method
linktitle: FillField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::FillField method. Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field''s names and its corresponding valid values must be known. Both the fields'' name and values are case sensitive. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name in C++.'
type: docs
weight: 2300
url: /cpp/aspose.pdf.facades/form/fillfield/
---
## Form::FillField(System::String, System::String) method


Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that [Aspose.Pdf.Facades](../../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, System::String fieldValue)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The field's name to be filled. |
| fieldValue | System::String | The field's value which must be a valid value for some fields. |

### ReturnValue

true if field is found and filled successfully.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The field's name to be filled.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fieldValue</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The field's value which must be a valid value for some fields.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, int32_t) method


Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that [Aspose.Pdf.Facades](../../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | Name of field to be filled. |
| index | int32_t | Index of chosen item. |

### ReturnValue

true if field was found and successfully filled.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of field to be filled.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Index of chosen item.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>


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

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, bool) method


Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that [Aspose.Pdf.Facades](../../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, bool beChecked)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The field's name to be filled. |
| beChecked | bool | A boolean flag: true means to check the box, while false to uncheck it. |

### ReturnValue

true if field was found and successfully filled.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The field's name to be filled.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>beChecked</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A boolean flag: true means to check the box, while false to uncheck it.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, System::ArrayPtr\<System::String\>) method


Fill a field with multiple selections.Note: only for AcroForm List Box Field.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::Form::FillField(System::String fieldName, System::ArrayPtr<System::String> fieldValues)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The fully qualified field name. |
| fieldValues | System::ArrayPtr\<System::String\> | A string array which contains several items to be selected. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The fully qualified field name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fieldValues</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A string array which contains several items to be selected.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::FillField(System::String, System::String, bool) method


Fills field with specified value.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::Form::FillField(System::String fieldName, System::String value, bool fitFontSize)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | Name of field |
| value | System::String | New value of the field |
| fitFontSize | bool | If true, the font size in the edit boxes will be fitted. |

### ReturnValue

true if field was found and successfully filled.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of field</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>New value of the field</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fitFontSize</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>If true, the font size in the edit boxes will be fitted.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
