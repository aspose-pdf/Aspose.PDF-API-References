---
title: Aspose::Pdf::Annotations::PDF3DViewArray::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PDF3DViewArray::idx_get method. Gets the PDF3DView to view array at the specified index in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf.annotations/pdf3dviewarray/idx_get/
---
## PDF3DViewArray::idx_get method


Gets the [PDF3DView](../../pdf3dview/) to view array at the specified index.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<PDF3DView> Aspose::Pdf::Annotations::PDF3DViewArray::idx_get(int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index. |

### ReturnValue

[PDF3DView](../../pdf3dview/).
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The index.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>IndexOutOfRangeException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Invalid index: index should be in the range [1..n] where n equals to the views count. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PDF3DView](../../pdf3dview/)
* Class [PDF3DViewArray](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
