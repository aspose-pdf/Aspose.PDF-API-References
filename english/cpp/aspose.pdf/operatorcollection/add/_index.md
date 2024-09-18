---
title: Aspose::Pdf::OperatorCollection::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OperatorCollection::Add method. Adds new operator into collection in C++.'
type: docs
weight: 700
url: /cpp/aspose.pdf/operatorcollection/add/
---
## OperatorCollection::Add(const System::SharedPtr\<Operator\>\&) method


Adds new operator into collection.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<Operator> &op) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| op | const System::SharedPtr\<Operator\>\& | [Operator](../../operator/) which must be added |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>op</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <ref refid="class_aspose_1_1_pdf_1_1_operator" kindref="compound">Operator</ref> which must be added</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\&) method


Add operators at the end of the contents operators.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OperatorCollection::Add(const System::ArrayPtr<System::SharedPtr<Operator>> &ops)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ops | const System::ArrayPtr\<System::SharedPtr\<Operator\>\>\& | Array of operators to be added. Each operator can have any index (by default -1) because they come to the end of the contents operators i.e. indices are assigned automatically. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>ops</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Array of operators to be added. Each operator can have any index (by default -1) because they come to the end of the contents operators i.e. indices are assigned automatically.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
## OperatorCollection::Add(const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\&) method


Adds to collection all operators from other collection.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OperatorCollection::Add(const System::SharedPtr<System::Collections::Generic::ICollection<System::SharedPtr<Operator>>> &ops)
```


| Parameter | Type | Description |
| --- | --- | --- |
| ops | const System::SharedPtr\<System::Collections::Generic::ICollection\<System::SharedPtr\<Operator\>\>\>\& | collection whitch contains operators which will be added. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>ops</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>collection whitch contains operators which will be added.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Operator](../../operator/)
* Class [OperatorCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
