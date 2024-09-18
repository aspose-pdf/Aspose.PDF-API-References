---
title: Aspose::Pdf::Annotations::PDF3DCrossSectionArray::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PDF3DCrossSectionArray::idx_get method. Gets the PDF3DCrossSection at the specified index in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf.annotations/pdf3dcrosssectionarray/idx_get/
---
## PDF3DCrossSectionArray::idx_get method


Gets the [PDF3DCrossSection](../../pdf3dcrosssection/) at the specified index.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<PDF3DCrossSection> Aspose::Pdf::Annotations::PDF3DCrossSectionArray::idx_get(int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index. |

### ReturnValue

Cross section.
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
      <para>Invalid index: index should be in the range [1..n] where n equals to the cross sections count. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [PDF3DCrossSection](../../pdf3dcrosssection/)
* Class [PDF3DCrossSectionArray](../)
* Namespace [Aspose::Pdf::Annotations](../../)
* Library [Aspose.PDF for C++](../../../)
