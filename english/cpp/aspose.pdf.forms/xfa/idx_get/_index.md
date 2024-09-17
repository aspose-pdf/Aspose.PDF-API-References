---
title: Aspose::Pdf::Forms::XFA::idx_get method
linktitle: idx_get
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Forms::XFA::idx_get method. Gets of sets data node value according path  in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.forms/xfa/idx_get/
---
## XFA::idx_get method


Gets of sets data node value according *path* .

```cpp
ASPOSE_PDF_SHARED_API System::String Aspose::Pdf::Forms::XFA::idx_get(System::String path)
```


| Parameter | Type | Description |
| --- | --- | --- |
| path | System::String | Data node path, e.g. form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Be sure to include indices even if data contains only single occurences of each nodes, i.e. write node1[0].node2[0]... instead of node1.node2... |

### ReturnValue

Data node value.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>path</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Data node path, e.g. form1[0].Subform1[0].Subform2[0].Subform3[0].TextField[0]. Be sure to include indices even if data contains only single occurences of each nodes, i.e. write node1[0].node2[0]... instead of node1.node2... </para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [XFA](../)
* Namespace [Aspose::Pdf::Forms](../../)
* Library [Aspose.PDF for C++](../../../)
