---
title: Aspose::Pdf::Utils::DictionaryEditor::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Utils::DictionaryEditor::idx_get method. Gets the element with the specified key in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.utils/dictionaryeditor/idx_get/
---
## DictionaryEditor::idx_get method


Gets the element with the specified key.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<PublicData::ICosPdfPrimitive> Aspose::Pdf::Utils::DictionaryEditor::idx_get(const System::String &key) const override
```


| Parameter | Type | Description |
| --- | --- | --- |
| key | const System::String\& | The key of the element to get or set. |

### ReturnValue

The element with the specified key.
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
