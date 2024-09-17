---
title: Aspose::Pdf::DestinationCollection::GetExplicitDestination method
linktitle: GetExplicitDestination
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DestinationCollection::GetExplicitDestination method. Returns the explicit destination by the name in C++.'
type: docs
weight: 500
url: /cpp/aspose.pdf/destinationcollection/getexplicitdestination/
---
## DestinationCollection::GetExplicitDestination method


Returns the explicit destination by the name.

```cpp
ASPOSE_PDF_SHARED_API System::SharedPtr<Annotations::ExplicitDestination> Aspose::Pdf::DestinationCollection::GetExplicitDestination(System::String destinameName, bool useCache)
```


| Parameter | Type | Description |
| --- | --- | --- |
| destinameName | System::String | The name of destination. |
| useCache | bool | Determines whether cached version of collection is used or not. |

### ReturnValue

The ExplicitDestination object for destination found; otherwise, null.
## Remarks


<parameterlist kind="param">
  <parameteritem>
    <parameternamelist>
      <parametername>destinameName</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>The name of destination.</para>
    </parameterdescription>
  </parameteritem>
  <parameteritem>
    <parameternamelist>
      <parametername>useCache</parametername>
    </parameternamelist>
    <parameterdescription>
      <para>Determines whether cached version of collection is used or not.</para>
    </parameterdescription>
  </parameteritem>
</parameterlist>
## See Also

* Class [ExplicitDestination](../../../aspose.pdf.annotations/explicitdestination/)
* Class [DestinationCollection](../)
* Namespace [Aspose::Pdf](../../)
* Library [Aspose.PDF for C++](../../../)
