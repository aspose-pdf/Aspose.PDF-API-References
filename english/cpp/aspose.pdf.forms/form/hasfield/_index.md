---
title: Aspose::Pdf::Forms::Form::HasField method
linktitle: HasField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Form::HasField method. Check if the form already has specified field in C++.'
type: docs
weight: 3400
url: /cpp/aspose.pdf.forms/form/hasfield/
---
## Form::HasField(System::SharedPtr\<Field\>) method


Check if the form already has specified field.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Forms::Form::HasField(System::SharedPtr<Field> field)
```


| Parameter | Type | Description |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) to check. |

### ReturnValue

**true** if the specified field name added to [Form](../); otherwise, **false**.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>field</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_field" kindref="compound">Field</ref> to check.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(System::String) method


Determines if the field with specified name already added to the [Form](../).

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Forms::Form::HasField(System::String fieldName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | [Field::PartialName](../) or [Annotation::FullName](../) of the field. |

### ReturnValue

**true**
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="" kindref="compound">Field::PartialName</ref> or <ref refid="" kindref="compound">Annotation::FullName</ref> of the field.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
if the specified field name added to [Form](../); otherwise, **false**

. 
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::HasField(System::String, bool) method


Determines if the field with specified name already added to the [Form](../), with ability to look into children hierarchy of fields.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Forms::Form::HasField(System::String fieldName, bool searchChildren)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | [Field::PartialName](../) or [Annotation::FullName](../) of the field. |
| searchChildren | bool | When set to **true**

the whole hierarchy of form fields would be searched for the requested *fieldName*  (note that in this case the [Annotation::FullName](../) of the required field should be passed as *fieldName* ). |

### ReturnValue

**true**
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="" kindref="compound">Field::PartialName</ref> or <ref refid="" kindref="compound">Annotation::FullName</ref> of the field.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>searchChildren</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>When set to <computeroutput>true</computeroutput></para>
      <para>the whole hierarchy of form fields would be searched for the requested <emphasis>fieldName</emphasis>  (note that in this case the <ref refid="" kindref="compound">Annotation::FullName</ref> of the required field should be passed as <emphasis>fieldName</emphasis> ). </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
if the specified field name added to [Form](../); otherwise, **false**

. 
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
