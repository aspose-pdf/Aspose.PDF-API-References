---
title: Aspose::Pdf::Facades::FormEditor::CopyInnerField method
linktitle: CopyInnerField
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor::CopyInnerField method. Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field in C++.'
type: docs
weight: 4600
url: /cpp/aspose.pdf.facades/formeditor/copyinnerfield/
---
## FormEditor::CopyInnerField(System::String, System::String, int32_t) method


Copies an existing field to the same position in specified page number. A new document will be produced, which contains everything the source document has except for the newly copied field.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::FormEditor::CopyInnerField(System::String fieldName, System::String newFieldName, int32_t pageNum)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The old fully qualified field name. |
| newFieldName | System::String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int32_t | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The old fully qualified field name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newFieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The new fully qualified field name. If null, it will be set as fieldName + "~".</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNum</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::CopyInnerField(System::String, System::String, int32_t, float, float) method


Copies an existing field to a new position specified by both page number and ordinates. A new document will be produced, which contains everything the source document has except for the newly copied field.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::FormEditor::CopyInnerField(System::String fieldName, System::String newFieldName, int32_t pageNum, float abscissa, float ordinate)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The old fully qualified field name. |
| newFieldName | System::String | The new fully qualified field name. If null, it will be set as fieldName + "~". |
| pageNum | int32_t | The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted. |
| abscissa | float | The abscissa of the new field. If -1, the abscissa will be equaled to the original one. |
| ordinate | float | The ordinate of the new field. If -1, the ordinate will be equaled to the original one. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The old fully qualified field name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>newFieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The new fully qualified field name. If null, it will be set as fieldName + "~".</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>pageNum</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of page to hold the new field. If -1, new field will be copid to the same page as old one hosted.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>abscissa</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The abscissa of the new field. If -1, the abscissa will be equaled to the original one.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ordinate</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The ordinate of the new field. If -1, the ordinate will be equaled to the original one.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
