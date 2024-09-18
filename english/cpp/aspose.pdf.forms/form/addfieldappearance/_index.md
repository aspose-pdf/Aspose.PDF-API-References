---
title: Aspose::Pdf::Forms::Form::AddFieldAppearance method
linktitle: AddFieldAppearance
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::Form::AddFieldAppearance method. Adds additional appearance of the field to specified page of the document in the specified location in C++.'
type: docs
weight: 3100
url: /cpp/aspose.pdf.forms/form/addfieldappearance/
---
## Form::AddFieldAppearance method


Adds additional appearance of the field to specified page of the document in the specified location.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Forms::Form::AddFieldAppearance(System::SharedPtr<Field> field, int32_t pageNumber, System::SharedPtr<Rectangle> rect)
```


| Parameter | Type | Description |
| --- | --- | --- |
| field | System::SharedPtr\<Field\> | [Field](../../field/) which appearance should be added on form. |
| pageNumber | int32_t | Number of the page where field must be placed. |
| rect | System::SharedPtr\<Rectangle\> | [Rectangle](../../../aspose.pdf/rectangle/) where field will be placed. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>field</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_forms_1_1_field" kindref="compound">Field</ref> which appearance should be added on form.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNumber</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Number of the page where field must be placed.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>rect</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_rectangle" kindref="compound">Rectangle</ref> where field will be placed.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Field](../../field/)
* Class [Rectangle](../../../aspose.pdf/rectangle/)
* Class [Form](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
