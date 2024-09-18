---
title: Aspose::Pdf::Outlines::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Outlines::CopyTo method. Copies the outline entries to an System.Array, starting at a particular System.Array index in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/outlines/copyto/
---
## Outlines::CopyTo method


Copies the outline entries to an **System.Array**, starting at a particular **System.Array** index.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Outlines::CopyTo(System::ArrayPtr<System::SharedPtr<OutlineItemCollection>> array, int32_t arrayIndex) override=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | System::ArrayPtr\<System::SharedPtr\<OutlineItemCollection\>\> | The one-dimensional **System.Array** that is the destination. Must have zero-based indexing. |
| arrayIndex | int32_t | The zero-based index in array at which copying begins. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>array</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The one-dimensional <ref refid="class_system_1_1_array" kindref="compound">System.Array</ref> that is the destination. Must have zero-based indexing.</para>
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
</parameterlist>
## See Also

* Class [OutlineItemCollection](../../outlineitemcollection/)
* Class [Outlines](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
