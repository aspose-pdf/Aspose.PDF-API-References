---
title: Aspose::Pdf::Utils::DictionaryEditor::idx_set method
linktitle: idx_set
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Utils::DictionaryEditor::idx_set method. Sets the element with the specified key in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.utils/dictionaryeditor/idx_set/
---
## DictionaryEditor::idx_set method


Sets the element with the specified key.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Utils::DictionaryEditor::idx_set(const System::String &key, System::SharedPtr<PublicData::ICosPdfPrimitive> value) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of the element to get or set. |
| value | System::SharedPtr\<PublicData::ICosPdfPrimitive\> | The element with the specified key. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>key</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The key of the element to get or set.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The element with the specified key.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The key is null.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>KeyNotFoundException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The property is retrieved and key is not found.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Throw exception if key can't be edited/set.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ICosPdfPrimitive](../../../aspose.pdf.utils.publicdata/icospdfprimitive/)
* Class [DictionaryEditor](../)
* Namespace [Aspose::Pdf::Utils](../../)
* Library [Aspose.PDF for C++](../../../)
