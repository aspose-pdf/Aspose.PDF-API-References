---
title: Aspose::Pdf::Annotations::PDF3DCrossSectionArray::idx_set method
linktitle: idx_set
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Annotations::PDF3DCrossSectionArray::idx_set method. Sets the PDF3DCrossSection at the specified index in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf.annotations/pdf3dcrosssectionarray/idx_set/
---
## PDF3DCrossSectionArray::idx_set method


Sets the [PDF3DCrossSection](../../pdf3dcrosssection/) at the specified index.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::Annotations::PDF3DCrossSectionArray::idx_set(int32_t index, System::SharedPtr<PDF3DCrossSection> value)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The index. |
| value | System::SharedPtr\<PDF3DCrossSection\> | Cross section. |
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
      <para>Cross section.</para>
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
