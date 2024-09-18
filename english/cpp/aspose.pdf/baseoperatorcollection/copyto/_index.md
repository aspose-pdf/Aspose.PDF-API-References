---
title: Aspose::Pdf::BaseOperatorCollection::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::BaseOperatorCollection::CopyTo method. Copies operators into operators list in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/baseoperatorcollection/copyto/
---
## BaseOperatorCollection::CopyTo method


Copies operators into operators list.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::BaseOperatorCollection::CopyTo(System::ArrayPtr<System::SharedPtr<Operator>> array, int32_t index) override=0
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | System::ArrayPtr\<System::SharedPtr\<Operator\>\> | Array with operators which must to be copied. This array must be Object[] or [Operator](../../operator/)[]. |
| index | int32_t | Starting index from which operators will be copied |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>array</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array with operators which must to be copied. This array must be Object[] or <ref refid="class_aspose_1_1_pdf_1_1_operator" kindref="compound">Operator</ref>[].</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Starting index from which operators will be copied</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Operator](../../operator/)
* Class [BaseOperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
