---
title: Aspose::Pdf::OperatorCollection::Replace method
linktitle: Replace
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorCollection::Replace method. Replace operators in collection with other operators in C++.'
type: docs
weight: 1000
url: /cpp/aspose.pdf/operatorcollection/replace/
---
## OperatorCollection::Replace method


Replace operators in collection with other operators.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OperatorCollection::Replace(System::SharedPtr<System::Collections::Generic::IList<System::SharedPtr<Operator>>> operators)
```


| Parameter | Type | Description |
| --- | --- | --- |
| operators | System::SharedPtr\<System::Collections::Generic::IList\<System::SharedPtr\<Operator\>\>\> | [Operators](../../../aspose.pdf.operators/) list which will replace operators currently contained in the collection. Eash operator from the list must have correct index in range [1..N] where N is count of operators in the collection |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>operators</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="namespace_aspose_1_1_pdf_1_1_operators" kindref="compound">Operators</ref> list which will replace operators currently contained in the collection. Eash operator from the list must have correct index in range [1..N] where N is count of operators in the collection</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
