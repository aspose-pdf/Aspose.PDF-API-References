---
title: Aspose::Pdf::Forms::Form::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Form::Add method. Adds field on the form in C++.'
type: docs
weight: 3000
url: /cpp/aspose.pdf.forms/form/add/
---
## Form::Add(System::SharedPtr\<Field\>, int32_t) method


Adds field on the form.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Forms::Form::Add(System::SharedPtr<Field> field, int32_t pageNumber)
```


| Parameter | Type | Description |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) which must be added. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) index where added field will be placed. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>field</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_field" kindref="compound">Field</ref> which must be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> index where added field will be placed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(const System::SharedPtr\<Field\>\&) method


Adds field on the form.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Forms::Form::Add(const System::SharedPtr<Field> &field)
```


| Parameter | Type | Description |
| --- | --- | --- |
| field | const System::SharedPtr\<Field\>\& | [Field](../../field/) which must be added. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>field</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_field" kindref="compound">Field</ref> which must be added.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
## Form::Add(System::SharedPtr\<Field\>, System::String, int32_t) method


Adds new field to the form; If this field is already placed on other or this form, the copy of field is created.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Field> Aspose::Pdf::Forms::Form::Add(System::SharedPtr<Field> field, System::String partialName, int32_t pageNumber)
```


| Parameter | Type | Description |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) name. |
| partialName | System::String | Name of field on the form. |
| pageNumber | int32_t | [Page](../../../aspose.pdf/page/) number where field will be added. |

### ReturnValue

Added field returned. If copy of the field was created it will be returned.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>field</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_field" kindref="compound">Field</ref> name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>partialName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of field on the form.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_page" kindref="compound">Page</ref> number where field will be added.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Field](../../field/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
