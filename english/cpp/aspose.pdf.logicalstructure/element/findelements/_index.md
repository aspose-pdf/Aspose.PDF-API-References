---
title: Aspose::Pdf::LogicalStructure::Element::FindElements method
linktitle: FindElements
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LogicalStructure::Element::FindElements method. Find Elements of a given type in C++.'
type: docs
weight: 300
url: /cpp/aspose.pdf.logicalstructure/element/findelements/
---
## Element::FindElements method


Find Elements of a given type.

```cpp
template<typename T> System::SharedPtr<System::Collections::Generic::List<T>> Aspose::Pdf::LogicalStructure::Element::FindElements(bool recursiveSearch=false)
```


| Parameter | Description |
| --- | --- |
| T | Type of [Structure](../../../aspose.pdf.structure/)[Element](../) for search |

| Parameter | Type | Description |
| --- | --- | --- |
| recursiveSearch | bool | (Optional) Recursive Search (default false, search only from direct children) |

### ReturnValue

List of found Elements
## Remarks


<parameterlist kind="templateparam">
  <parameteritem>
    <parameternamelist>
      <parametername>T</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Type of <ref refid="namespace_aspose_1_1_pdf_1_1_structure" kindref="compound">Structure</ref><ref refid="class_aspose_1_1_pdf_1_1_logical_structure_1_1_element" kindref="compound">Element</ref> for search</para>
    </parameterdescription>
  </parameteritem>
</parameterlist><parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>recursiveSearch</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>(Optional) Recursive Search (default false, search only from direct children)</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [Element](../)
* Namespace [Aspose::Pdf::LogicalStructure](../../)
* Library [Aspose.PDF for C++](../../../)
