---
title: Aspose::Pdf::OutputIntents::Add method
linktitle: Add
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::OutputIntents::Add method. Adds an output intent to the collection in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf/outputintents/add/
---
## OutputIntents::Add method


Adds an output intent to the collection.

```cpp
ASPOSE_PDF_SHARED_API void Aspose::Pdf::OutputIntents::Add(const System::SharedPtr<OutputIntent> &item) override
```


| Parameter | Type | Description |
| --- | --- | --- |
| item | const System::SharedPtr\<OutputIntent\>\& | The output intent to add to the collection. |
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>item</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The output intent to add to the collection.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="exception">
  <parameteritem>
    <parameternamelist>
      <parametername>ArgumentNullException</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The <emphasis>item</emphasis>  is null.</para>
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
