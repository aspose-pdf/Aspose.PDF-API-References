---
title: Aspose::Pdf::OutputIntents::CopyTo method
linktitle: CopyTo
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OutputIntents::CopyTo method. Copies the elements of the collection to the array ,starting at the particular arrayIndex  into the array in C++.'
type: docs
weight: 600
url: /cpp/aspose.pdf/outputintents/copyto/
---
## OutputIntents::CopyTo method


Copies the elements of the collection to the *array* ,starting at the particular *arrayIndex*  into the array.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OutputIntents::CopyTo(System::ArrayPtr<System::SharedPtr<OutputIntent>> array, int32_t arrayIndex) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| array | System::ArrayPtr\<System::SharedPtr\<OutputIntent\>\> | The one-dimensional array that is the destination of the output intents copied from the collection. The array must have zero-based indexing. |
| arrayIndex | int32_t | The zero-based index in *array*  at which copying begins. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>array</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The one-dimensional array that is the destination of the output intents copied from the collection. The array must have zero-based indexing. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>arrayIndex</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The zero-based index in <emphasis>array</emphasis>  at which copying begins.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <emphasis>array</emphasis>  is null.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentOutOfRangeException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <emphasis>arrayIndex</emphasis>  is less than 0.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The number of elements in the source <ref refid="class_aspose_1_1_pdf_1_1_output_intents" kindref="compound">OutputIntents</ref> is greater than the available space from <emphasis>arrayIndex</emphasis>  to the end of the destination <emphasis>array</emphasis> . </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [OutputIntent](../../outputintent/)
* Class [OutputIntents](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
