---
title: Aspose::Pdf::Utils::DictionaryEditor::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Utils::DictionaryEditor::CopyTo method. Copies the elements of the DictionaryEditor to an Array, starting at a particular Array index in C++.'
type: docs
weight: 1500
url: /cpp/aspose.pdf.utils/dictionaryeditor/copyto/
---
## DictionaryEditor::CopyTo method


Copies the elements of the [DictionaryEditor](../) to an [Array](../../../aspose.pdf/xmpfieldtype/), starting at a particular [Array](../../../aspose.pdf/xmpfieldtype/) index.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Utils::DictionaryEditor::CopyTo(System::ArrayPtr<System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<PublicData::ICosPdfPrimitive>>> array, int32_t arrayIndex) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | System::ArrayPtr\<System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<PublicData::ICosPdfPrimitive\>\>\> | The one-dimensional [Array](../../../aspose.pdf/xmpfieldtype/) that is the destination of the elements copied from [DictionaryEditor](../). The [Array](../../../aspose.pdf/xmpfieldtype/) must have zero-based indexing. |
| arrayIndex | int32_t | The zero-based index in array at which copying begins. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>array</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The one-dimensional <ref refid="namespace_aspose_1_1_pdf_1adf4a5d7036332fe0c63b49667e07208ba4410ec34d9e6c1a68100ca0ce033fb17" kindref="member">Array</ref> that is the destination of the elements copied from <ref refid="class_aspose_1_1_pdf_1_1_utils_1_1_dictionary_editor" kindref="compound">DictionaryEditor</ref>. The <ref refid="namespace_aspose_1_1_pdf_1adf4a5d7036332fe0c63b49667e07208ba4410ec34d9e6c1a68100ca0ce033fb17" kindref="member">Array</ref> must have zero-based indexing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>arrayIndex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The zero-based index in array at which copying begins.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The array is null.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentOutOfRangeException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The arrayIndex is less than 0.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of elements in the source <ref refid="class_aspose_1_1_pdf_1_1_utils_1_1_dictionary_editor" kindref="compound">DictionaryEditor</ref> is greater than the available space from arrayIndex to the end of the destination array. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ICosPdfPrimitive](../../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
