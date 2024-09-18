---
title: Aspose::Pdf::Annotations::PDF3DViewArray::idx_set method
linktitle: idx_set
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PDF3DViewArray::idx_set method. Sets the PDF3DView to view array at the specified index in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.annotations/pdf3dviewarray/idx_set/
---
## PDF3DViewArray::idx_set method


Sets the [PDF3DView](../../pdf3dview/) to view array at the specified index.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::PDF3DViewArray::idx_set(int32_t index, System::SharedPtr<PDF3DView> value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index. |
| value | System::SharedPtr\<PDF3DView\> | [PDF3DView](../../pdf3dview/). |
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
  <parameteritem>
    <parameternamelist>
      <parametername>value</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_annotations_1_1_p_d_f3_d_view" kindref="compound">PDF3DView</ref>.</para>
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
