---
title: Aspose::Pdf::OutputIntents::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OutputIntents::idx_get method. Gets the output intent at the specified index  in C++.'
type: docs
weight: 900
url: /cpp/aspose.pdf/outputintents/idx_get/
---
## OutputIntents::idx_get method


Gets the output intent at the specified *index* .

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<OutputIntent> Aspose::Pdf::OutputIntents::idx_get(int32_t index)
```


| Parameter | Type | Description |
| --- | --- | --- |
| index | int32_t | The zero-based index of the output intent to get. |

### ReturnValue

The output intent at the specified *index* .
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>index</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The zero-based index of the output intent to get.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentOutOfRangeException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>
        <emphasis>index</emphasis>  is less than 0 or <emphasis>index</emphasis>  is equal to or greater than <ref refid="" kindref="compound">Count</ref>. </para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>InvalidOperationException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The document that contains the collection has no catalog to access the <ref refid="class_aspose_1_1_pdf_1_1_output_intents" kindref="compound">OutputIntents</ref>. </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [OutputIntent](../../outputintent/)
* Class [OutputIntents](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
