---
title: Aspose::Pdf::Facades::FormEditor::SetFieldAlignment method
linktitle: SetFieldAlignment
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::FormEditor::SetFieldAlignment method. Set the alignment style of a text field in C++.'
type: docs
weight: 5700
url: /cpp/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor::SetFieldAlignment method


Set the alignment style of a text field.

```cpp
ASPOSE_PDF_SHARED_API bool Aspose::Pdf::Facades::FormEditor::SetFieldAlignment(System::String fieldName, int32_t alignment)
```


| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | System::String | The qualified field name. |
| alignment | int32_t | The alignment style definition, including [FormFieldFacade.AlignLeft](../../formfieldfacade/alignleft/), [FormFieldFacade.AlignCenter](../../formfieldfacade/aligncenter/) and [FormFieldFacade.AlignRight](../../formfieldfacade/alignright/). |

### ReturnValue

true if true if field was found and alignment was set.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>fieldName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The qualified field name.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>alignment</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The alignment style definition, including <ref refid="class_aspose_1_1_pdf_1_1_facades_1_1_form_field_facade_1a7c4ccde91650cbc5216d425c3ddedef4" kindref="member">FormFieldFacade.AlignLeft</ref>, <ref refid="class_aspose_1_1_pdf_1_1_facades_1_1_form_field_facade_1a17075cdd1c59a5677c2d4577d6308c1b" kindref="member">FormFieldFacade.AlignCenter</ref> and <ref refid="class_aspose_1_1_pdf_1_1_facades_1_1_form_field_facade_1ad16ee85548c5d117ac2d45541e7c14a3" kindref="member">FormFieldFacade.AlignRight</ref>.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [FormEditor](../)
* Namespace [Aspose::Pdf::Facades](../../)
* Library [Aspose.PDF for C++](../../../)
