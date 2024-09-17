---
title: Aspose::Pdf::Utils::DictionaryEditor::Remove method
linktitle: Remove
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Utils::DictionaryEditor::Remove method. Removes the element with the specified key from the DictionaryEditor in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf.utils/dictionaryeditor/remove/
---
## DictionaryEditor::Remove(const System::String\&) method


Removes the element with the specified key from the [DictionaryEditor](../).

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Utils::DictionaryEditor::Remove(const System::String &key) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of the element to remove. |

### ReturnValue

True if the element is successfully removed; otherwise, false. This method also returns false if key was not found in the original dictionary or key the key is not editable
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The key of the element to remove.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
## DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<PublicData::ICosPdfPrimitive\>\>\&) method


Removes the first occurrence of a specific object from the [DictionaryEditor](../).

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Utils::DictionaryEditor::Remove(const System::Collections::Generic::KeyValuePair<System::String, System::SharedPtr<PublicData::ICosPdfPrimitive>> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::Collections::Generic::KeyValuePair\<System::String, System::SharedPtr\<PublicData::ICosPdfPrimitive\>\>\& | The object to remove from the [DictionaryEditor](../). |

### ReturnValue

true if item was successfully removed from the [DictionaryEditor](../); otherwise, false. This method also returns false if item is not found in the original [DictionaryEditor](../).
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The object to remove from the <ref refid="class_aspose_1_1_pdf_1_1_utils_1_1_dictionary_editor" kindref="compound">DictionaryEditor</ref>.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ICosPdfPrimitive](../../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
