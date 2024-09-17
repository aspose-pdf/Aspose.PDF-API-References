---
title: Aspose::Pdf::Facades::FormEditor::AddListItem method
linktitle: AddListItem
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor::AddListItem method. Adds new item to the list box in C++.'
type: docs
weight: 5200
url: /cpp/aspose.pdf.facades/formeditor/addlistitem/
---
## FormEditor::AddListItem(System::String, System::String) method


Adds new item to the list box.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::FormEditor::AddListItem(System::String fieldName, System::String itemName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | Name of the field ot which new item will be added. |
| itemName | System::String | Name if new item. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of the field ot which new item will be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>itemName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name if new item.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
## FormEditor::AddListItem(System::String, System::ArrayPtr\<System::String\>) method


Add a new item with Export value to the existing list box field, only for AcroForm combo box field.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Facades::FormEditor::AddListItem(System::String fieldName, System::ArrayPtr<System::String> exportName)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | Name of field to which items will be added. |
| exportName | System::ArrayPtr\<System::String\> | A string array denoting a new list item with Export Value, i.e. (Item Label, Export Value). |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Name of field to which items will be added.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>exportName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>A string array denoting a new list item with Export Value, i.e. (Item Label, Export Value).</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
