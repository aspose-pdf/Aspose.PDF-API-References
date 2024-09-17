---
title: Aspose::Pdf::Facades::Form::FillFields method
linktitle: FillFields
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form::FillFields method. Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to Text Box. Both the fields'' name and values are case sensitive in C++.'
type: docs
weight: 2400
url: /cpp/aspose.pdf.facades/form/fillfields/
---
## Form::FillFields method


Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to [Text](../../../aspose.pdf.text/) Box. Both the fields' name and values are case sensitive.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::Form::FillFields(System::ArrayPtr<System::String> fieldNames, System::ArrayPtr<System::String> fieldValues, System::SharedPtr<System::IO::Stream> &output)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldNames | System::ArrayPtr\<System::String\> | Names of fields. |
| fieldValues | System::ArrayPtr\<System::String\> | New values of the fields. |
| output | System::SharedPtr\<System::IO::Stream\>\& | Stream where document will be saved. |

### ReturnValue

true if fields was found and successfully filled.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldNames</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Names of fields.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>fieldValues</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>New values of the fields.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>output</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Stream where document will be saved.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Form](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
